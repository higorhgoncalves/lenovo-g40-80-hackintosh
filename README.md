# Lenovo G40-80 Hackintosh
### Lenovo G40-80 Hackintosh with Opencore (0.6.2) (Outdated)

**Specs**
* CPU - Intel i5 5200U Broadwell;
* Video Card - Intel HD Graphics 5500;
* Audio Card - CONEXANT 20751/2;
* RAM - 8 GB;
* HDD - 1 TB;
* Wireless Card - RTL8723BE - Not Supported, need replacement;
* Wifi Dongle - TL WN725N;
* Bluetooth Dongle - Generic Bluetooth 4.0 Dongle;

**Working (Tested):**
* Graphics Acceleration;
* HDMI Video;
* Brightness control;
* Internal Audio;
* Internal Mic;
* Touchpad and Keyboard;
* USB Devices;
* Wifi Dongle;
* Bluetooth Dongle;
* Battery Status;
* DVD Reader;

**What doesn't work yet:**
* Wifi;
* Bluetooth;
* HDMI Audio;
* SD-CardReader;

**Fixes:**
* To configure shortcut keys for Brightness, first disable SSDT-BATT.aml through Opencore Configurator, or a Plist Editor. After configuration you can enable SSDT-BATT.aml again. Recomended Keys: Ctrl + F11 and Ctrl + F12;

*For Catalina and Older:*
* To configure Trackpad on System Preferences, please download the Trackpad Pane Fix, open Hackintool, under Utilities, click on the House icon (Disable Gatekeeper), copy Trackpad.prefPane to /System/Library/PreferencePanes/ and Replace the one found in there.

**Downloads:**
* [Opencore Configurator](https://mackie100projects.altervista.org/apps/opencoreconf/download-new-build.php?version=last)
* [Trackpad Pane Fix](https://drive.google.com/file/d/1nqvFKDfDNCfYNkZnA8fWYGY5nq4Xk9dw/view?usp=sharing) (For Catalina and Older)
* [Hackintool](https://github.com/headkaze/Hackintool/releases)
* [MaciASL](https://github.com/acidanthera/MaciASL/releases)
* [Clover.app](https://github.com/CloverHackyColor/CloverBootloader/releases) (Plist Editor/EFI Mounter)
* [TL WN725N Driver](https://www.tp-link.com/br/support/download/tl-wn725n/#Driver) (Wifi Dongle) (Catalina and Older)
* [TL WN725N Guide](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter) (Wifi Dongle) (Big Sur)
* [EFI GUI](https://github.com/acidanthera/OcBinaryData) (Put Resources Folder in EFI partition /EFI/OC/)


**References:**
* https://dortania.github.io
* https://opencore.slowgeek.com
