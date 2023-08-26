# pgbs's custom

This repo lets you download your OpenCore EFI for my current build.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**

**Starting in v0.4, security features like SecureBootModel, Vault, ApECID will be included in the v0.4 release. Bugs might expected, so be sure to report them in the GitHub's Issues tab!**

## Screenshot
![Screenshot 2023-08-07 at 13 03 41](https://github.com/PGBSean/pgbs-custom/assets/97381104/3b4977f0-60ee-41de-a3cf-be2f60b78089)


## This EFI applys to:

|  Components             |         Requirements                |            Note                      |
|-------------------------|-------------------------------------|--------------------------------------|
| CPU                     |  AMD Ryzen 5 3400G                  |  This CPU is using a 4 cores kernel patch. If your CPU have more or less cores than this EFI, change it and refer to the OpenCore guide. |
| GPU                     |  AMD Radeon RX Vegas 11 iGPU        | Thanks to NootedRed to get AMD iGPU support on this Hackintosh! Make sure that you don't have a dGPU in your system! |
| Motherboard             | ASRock B450M Pro4-F R2.0            |  This build will only work for the B450 motherboards, for other, please refer to the OpenCore Guide.|


## Settings to change

|BIOS Settings|Toggle|
|-------------------------|-------------------------------------|
|Secure Boot|**OFF**|
|TPM|**OFF** (optional)|
|Above 4G Decoding|**ON**|
|VRAM for iGPU|Above 512M for best results|
|Fast Boot|**OFF**|
|CSM|**OFF**|

## Bugs
+ Calling on Discord broke
> Require a patch of AMDFriend from [this comment in Reddit](https://www.reddit.com/r/hackintosh/comments/15ke8vp/comment/jv8cc25/?utm_source=share&utm_medium=web2x&context=3)
+ Chromium browsers (Edge, Chrome, Opera, Arc Browser) glitchs
> Known issue from NootedRed, please wait for the next patch from them.


## Tested versions
+ macOS Big Sur
+ macOS Monterey
+ macOS Ventura
+ macOS Sonoma

