# Hackintosh on HP Omen 15 (ek0002nt)

![Picture](https://raw.githubusercontent.com/emrebbozkurt/HP-OMEN15-Hackintosh/master/screenshot.png)

* CPU: i7-10750H
* Audio: ALC245
* Ethernet: Realtek
* Wi-Fi: AX201
* iGPU: Intel UHD Graphics 630
* eGPU: GeForce RTX 2070 Max-Q

## Reference
### [osxinfo](https://osxinfo.net)
### [lunjielee](https://github.com/lunjielee/Opencore-HP-Omen-15-2020)

## Credits
### [Apple](https://www.apple.com/) for macOS
### [Acidanthera](https://github.com/acidanthera) for awesome kexts
### [RehabMan](https://github.com/RehabMan) for guides and kexts

## Alert
Do NOT directly use the file provided, you need to change something so
that it won't cause a problem. The best way to make your own Hackintosh
installed is to follow the guide list below step by step.

## Tools

### Patch
* [Hackintool](http://headsoft.com.au/download/mac/Hackintool.zip)

### Monitor
* [Intel® Power Gadget](https://software.intel.com/en-us/articles/intel-power-gadget)
* [HWSensors](https://github.com/kozlek/HWSensors)

### Installation
* [Dortania's OpenCore Install Guide](https://github.com/dortania/OpenCore-Install-Guide)

### Post Installation
* [OpenCore Post-Install](https://github.com/dortania/OpenCore-Post-Install)

### CPU
* [one-key-cpufriend](https://github.com/stevezhengshiqi/one-key-cpufriend)

### Bluetooth
* [OpenIntelWireless/IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)

## Others
### Not Working
* Mic (Intel SST)
* Video Outputs (Nvidia)
* Sleep

## Notes
* If you want to edit plist's =Data= type in Xcode, you should use format like =<01000000>=.
