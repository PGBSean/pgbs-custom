# pgbs's custom

This repo lets you download your OpenCore EFI for my current build.

WARNING ⚠️: I  do not responsible for lost personal data, or damage personal property. **You are doing this at your own RISK.**

## Screenshot
![image](https://github.com/PGBSean/pgbs-custom/assets/97381104/134cdba8-f437-4358-8fe8-5aa18c4f4d0e)



## This EFI applys to:

|  Components             |         Requirements                |            Note                      |
|-------------------------|-------------------------------------|--------------------------------------|
| CPU                     |  AMD Zen-based CPU                  |  This EFI is using a 4 cores kernel patch. If your CPU have more or less cores than this EFI, change it and refer to the OpenCore guide. |
| GPU                     |  AMD Vegas iGPU        | Thanks to @ChefKissInc to get AMD iGPU support on this Hackintosh! Make sure that you don't have a dGPU in your system or add -wegnogpu into your boot-args |
| Motherboard             | B450 motherboards            |  This build will only work for the B450 motherboards (specifically ASRock B450M Pro4-F R2.0), for other, you're on your own.|


## Settings to change

|BIOS Settings|Toggle|
|-------------------------|-------------------------------------|
|Secure Boot|**OFF**|
|TPM|**OFF** (optional)|
|Above 4G Decoding|**ON**|
|VRAM for iGPU|Above 512M for best results|
|Fast Boot|**OFF**|
|CSM|**OFF**|
|Serial Port|**OFF**|
|IOMMU|**OFF**|

## Bugs
+ Calling on Discord broke
> Require a patch of AMDFriend from [this comment in Reddit](https://www.reddit.com/r/hackintosh/comments/15ke8vp/comment/jv8cc25/?utm_source=share&utm_medium=web2x&context=3)
+ Chromium browsers (Edge, Chrome, Opera, Arc Browser) glitchs

## Tested versions
+ macOS Big Sur
+ macOS Monterey
+ macOS Ventura
+ macOS Sonoma
+ **[BETA]** macOS Sequioa
> **DO NOT ATTEMPT TO UPGRADE TO SEQUIOA** as NootedRed is **NOT** a stable kext for beta updates like these. Follow updates from their side [here](https://github.com/ChefKissInc/NootedRed)

