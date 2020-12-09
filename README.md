# HPG5250BIGSUR
Big Sur Hackintosh Project for HP G5 250
The laptop is pretty stable with this EFI/configuration

![Screenshot 2020-12-09 at 17 36 36](https://user-images.githubusercontent.com/75743188/101651582-e68bad00-3a45-11eb-88f7-25faad8a045c.png)


Specifications: 

CPU: Intel Core i5 6200U

iGPU: Intel HD520

dGPU: AMD Radeon R5 330M

Network: Realtek RTL8168H

Network: INTEL WI-FI( do not know the exact adapter but it is working+bluetooth)

RAM: 8GB DDR4 2133MHz

Audio: Realtek ALC282

BIOS: Insyde UEFI, vF.48

Board: HP 81EC

SSD: 128GB KINGSTON A400




What's working


Audio. (Speaker and Headphone jack)

Microphone. (Integrated and Headphone)

Audio controls.

LCD brightness.

CPU Power Management. (Oficially supported)

Metal. (Officially supported GPU)

SD Card reader.

Webcam.

Bluetooth. (Fully Working with audio support, etc.)

Ethernet.

WI-FI.

USB.

Sleep.

Trackpad (no gestures)

HDMI(partially working, after long sleep requires a reboot to start again)

Dual Booting (Windows and macOS)

iMessage, FaceTime, iCloud.






Not Working/Not tested


Dedicated Radeon GPU (disabled by bootargs in OpenCore)

HDMI Audio(not tested)

Trackpad gestures

Keyboard brightness control(WIP)





Not tested(may work):


VGA





List of Patches and kexts


RealtekRTL8100 Kext

AppleBacklightFixup

FakeSMC

Lilu

VoodooPS2Controller

WhateverGreen

Apple ALC

USBInjectAll.kext

Sleep fix : OpenCore

Thank for the creators of OpenIntelWireless.

