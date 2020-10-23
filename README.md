# Lenovo G40-80 Hackintosh
### Lenovo G40-80 Hackintosh with Opencore (0.6.2)

**Working:**
* Processor - Intel 5200U Broadwell
* Video - Intel HD 5500;
* Brightness;
* Audio - CONEXANT 20751/2;
* Touchpad and Keyboard;
* USB Devices;
* Wifi Dongle - TL WN725N - Download Driver and Install(Catalina and Older);
* Battery Status;

**What doesn't work yet:**
* Wifi and Bluetooth Card - RTL8723BE - Not Supported, need replacement
* SD-CardReader - Not Supported

**Fixes:**
* To configure shortcut keys for Brightness, first disable SSDT-BATT.aml through Opencore Configurator, or a Plist Editor. After configuration you can enable SSDT-BATT again. Recomended Keys: F1 and F2;

* To configure Trackpad on System Preferences, please download the Trackpad Pane Fix, open Hackintool under Utilities click on the House icon (Disable Gatekeeper), copy Trackpad.prefPane to /System/Library/PreferencePanes/ and Replace the one found in there.

**Downloads:**
* Opencore Configurator
https://mackie100projects.altervista.org/apps/opencoreconf/download-new-build.php?version=last
* Trackpad Pane Fix (Kext for touchpad already on EFI and added to config.plist)
https://drive.google.com/file/d/1nqvFKDfDNCfYNkZnA8fWYGY5nq4Xk9dw/view?usp=sharing
* Hackintool
https://github.com/headkaze/Hackintool/releases
* MaciASL
https://github.com/acidanthera/MaciASL/releases
* PlistEditor
https://www.fatcatsoftware.com/plisteditpro/
* TL WN725N Driver (Wifi Dongle) (Catalina and Older)
https://www.tp-link.com/br/support/download/tl-wn725n/#Driver
* TL WN725N Guide (Wifi Dongle) (Big Sur)
https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter
* EFI GUI (Put Resources Folder in EFI partition /EFI/OC/)
https://github.com/acidanthera/OcBinaryData

**References:**
* https://dortania.github.io
* https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
* https://opencore.slowgeek.com
