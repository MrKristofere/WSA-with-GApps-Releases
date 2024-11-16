This is the fork from which I compile [releases](https://github.com/MrKristofere/WSA-with-GApps-Releases/releases). Official repository: https://github.com/LSPosed/MagiskOnWSALocal

## Installation

 Drag the WSA installation package to `install.cmd`.
 Or do as in this instruction: https://www.nookery.ru/decided-error-0x800b0109/ and install the package as usual, without using "install.cmd"

 ⚠️***IMPORTANT!** The folder where the installation package is located, as well as subfolders and the installation package itself, should not have spaces or special characters in the name. (this item is required, only if you install via "install.cmd")*

## Requirements before installation:
- Windows version is at least Windows 11 version 22000.120.
- Enable "Developer Mode" in Windows settings.
- Enable Virtualization in UEFI/BIOS and "Virtual Machine Platform" in Windows Features
- Install components: `Microsoft.UI.Xaml.2.8_8.2310.30001.0, Microsoft.VCLibs.140.00_14.0.33519.0, Microsoft.VCLibs.140.00.UWPDesktop_14.0.33728.0` from the ***Deps.for.WSA.zip*** archive

## Build Features
**Added:**
- Root (Magisk 28.0)
- Google Services [(GApps-13.0 dated March 03, 2024)](https://github.com/LSPosed/WSA-Addon/releases/tag/v1)


## Credits

- [StoreLib](https://github.com/StoreDev/StoreLib): API for downloading WSA
- [Magisk](https://github.com/topjohnwu/Magisk): The most famous root solution on Android
- ~~[The Open GApps Project](https://opengapps.org): One of the most famous Google Apps packages solution~~
- [WSA-Kernel-SU](https://github.com/LSPosed/WSA-Kernel-SU) and [kernel-assisted-superuser](https://git.zx2c4.com/kernel-assisted-superuser/): The kernel `su` for debugging Magisk Integration
- ~~[WSAGAScript](https://github.com/ADeltaX/WSAGAScript): The first GApps integration script for WSA~~
- ~~[erofs-utils](https://github.com/sekaiacg/erofs-utils): Pre-build `erofs-utils` with erofsfuse enabled~~
- [WSAPackagingTool](https://github.com/MlgmXyysd/WSAPackagingTool): Packing the assembly into a .msixbundle

_The repository is provided as a utility._

_Android is a trademark of Google LLC. Windows is a trademark of Microsoft Corporation._
