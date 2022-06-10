* Hackintosh on HP Omen 15 (ek0002nt)
#+HTML: <img src="https://raw.githubusercontent.com/emrebbozkurt/HP-OMEN15-Hackintosh/master/screenshot.png" align="right" width="70%"/>

- CPU: i7-10750H
- Audio: ALC245
- Ethernet: Realtek
- Wi-Fi: AX201
- iGPU: Intel UHD Graphics 630
- eGPU: GeForce RTX 2070 Max-Q

** Reference
- [[https://osxinfo.net][osxinfo]]
- [[https://tonymacx86.com][tonymacx86]]
- [[http://www.insanelymac.com][insanelymac]]

** Credits
- [[https://www.apple.com/][Apple]] for macOS
- [[https://github.com/acidanthera][Acidanthera]] for awesome kexts
- [[https://github.com/RehabMan][RehabMan]] for guides and kexts

** Alert
Do NOT directly use the file provided, you need to change something so
that it won't cause a problem. The best way to make your own Hackintosh
installed is to follow the guide list below step by step.

** Tools
*** ACPI
- [[https://github.com/acidanthera/MaciASL][MaciASL]]

*** Patch
- [[http://headsoft.com.au/download/mac/Hackintool.zip][Hackintool]]

*** Monitor
- [[https://software.intel.com/en-us/articles/intel-power-gadget][Intel® Power Gadget]]
- [[https://download.developer.apple.com/Developer_Tools/Additional_Tools_for_Xcode_11/Additional_Tools_for_Xcode_11.dmg][IO Registry Explorer]]
- [[https://bjango.com/mac/istatmenus/][iStat Menus]]
- [[https://github.com/kozlek/HWSensors][HWSensors]]

** Installation
[[https://github.com/dortania/OpenCore-Install-Guide][Dortania's OpenCore Install Guide]]

** Post Installation
[[https://github.com/dortania/OpenCore-Post-Install][OpenCore Post-Install]]

*** CPU
- [[https://github.com/stevezhengshiqi/one-key-cpufriend][one-key-cpufriend]]

*** Bluetooth
- [[https://github.com/OpenIntelWireless/IntelBluetoothFirmware][OpenIntelWireless/IntelBluetoothFirmware]]

*** USB
- [[https://www.tonymacx86.com/threads/guide-creating-a-custom-ssdt-for-usbinjectall-kext.211311/][(Guide) Creating a Custom SSDT for USBInjectAll.kext]]

*** iGPU
- [[https://www.tonymacx86.com/threads/guide-intel-framebuffer-patching-using-whatevergreen.256490/][(Guide) Intel Framebuffer patching using WhateverGreen]]
- [[https://github.com/xzhih/one-key-hidpi][one-key-hidpi]]

*** eGPU
- [[https://www.tonymacx86.com/threads/guide-disabling-discrete-graphics-in-dual-gpu-laptops.163772/][(Guide) Disabling discrete graphics in dual-GPU laptops]]
- [[https://www.tonymacx86.com/threads/guide-using-clover-to-hotpatch-acpi.200137/post-1308262][(Guide) Using Clover to "hotpatch" ACPI - Disabling discrete/switched GPU with Hotpatch]]
- [[https://www.insanelymac.com/forum/forums/topic/295584-disabling-nvidia-optimus-card-on-all-laptops/][Disabling NVIDIA Optimus card on all laptops]]

*** iCloud
- [[https://www.youtube.com/watch?v=JhA7e26dGgM][FIX iMessage, Facetime, and App Store 2018 Tutorial]]

** Others
*** Not Working
1. Mic (Intel SST)
2. Video Outputs (Nvidia)
3. Sleep

** Notes
- If you want to edit plist's =Data= type in Xcode, you should use format like =<01000000>=.
