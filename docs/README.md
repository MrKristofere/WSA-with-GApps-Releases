This is the fork from which I compile [releases](https://github.com/MrKristofere/WSA-with-GApps-Releases/releases). Official repository: https://github.com/LSPosed/MagiskOnWSALocal

## Installation

 Drag the WSA installation package to `install.cmd`.
 Or do as in this instruction: https://www.nookery.ru/decided-error-0x800b0109/ and install the package as usual, without using "install.cmd"

 ***IMPORTANT!** The folder where the installation package is located, as well as subfolders and the installation package itself, should not have spaces or special characters in the name. (this item is required, only if you install via "install.cmd")*

 #### Requirements before installation:
- Windows version is at least Windows 11 version 22000.120.
- Enable "Developer Mode" in Windows settings.
- Enable Virtualization in UEFI/BIOS and "Virtual Machine Platform" in Windows Components
- Install components: `Microsoft.UI.Xaml.2.8_8.2212.15002.0`, `Microsoft.VCLibs.140.00_14.0.30704.0`, `Microsoft.VCLibs.140.00.UWPDesktop_14.0.30704.0` from the `Install.before.WSA.zip` archive

## Build Features
#### Added:
- Root (Magisk 25.2)
- Google Services (MindTheGApps dated August 29, 2022)
- VpnDialogs

#### Removed:
- Amazon Appstore
 
#### Edited:
- build.prop (the device is displayed as Pixel 6 Pro) - this is done so that Google does not require device certification to enter the account.

---

## Credits

- [StoreLib](https://github.com/StoreDev/StoreLib): API for downloading WSA
- [Magisk](https://github.com/topjohnwu/Magisk): The most famous root solution on Android
- [The Open GApps Project](https://opengapps.org): One of the most famous Google Apps packages solution
- [WSA-Kernel-SU](https://github.com/LSPosed/WSA-Kernel-SU) and [kernel-assisted-superuser](https://git.zx2c4.com/kernel-assisted-superuser/): The kernel `su` for debugging Magisk Integration
- [WSAGAScript](https://github.com/ADeltaX/WSAGAScript): The first GApps integration script for WSA
- [WSAPackagingTool](https://github.com/WSA-Community/WSAPackagingTool): Packing the assembly into a .msixbundle

_The repository is provided as a utility._

_Android is a trademark of Google LLC. Windows is a trademark of Microsoft LLC._
