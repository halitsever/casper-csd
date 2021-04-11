<h1>Casper CSD OpenCore 0.6.6 Big Sur</h1>
<img align="right" width="250" height="250" src="https://i.ibb.co/pWSYTSF/csd11.png">
<p align="left"> 
Repository contains configuration, kexts, etc for hackintosh on Casper CSD.
</p>
<h1>Supported Versions</h1>
macOS Big Sur <a href="https://github.com/murathasev/casper-csd/releases/tag/0.6.6">(checkout this release)</a><br>
macOS Catalina <a href="https://github.com/murathasev/casper-csd/releases/tag/0.6.6">(checkout this release)</a><br>
macOS Mojave <a href="https://github.com/murathasev/casper-csd/releases/tag/0.6.6">(checkout this release)</a><br><br><br><br>
<h1>Specs</h1>
<img align="left" width="250" height="250" src="https://i.ibb.co/kmBvSdn/casper.png">
<b>GPU:</b> integrated Intel HD Graphics 4600<br>
<b>RAM:</b> 8 GB<br>
<b>Processor:</b>i5-4210M<br>
<b>Chipset:</b> Intel 8 Series<br>
<b>EFI:</b> OpenCore<br>
<b>BIOS:</b> C15B (ver. 617)
<h1>Installation</h1>
<b>Notice:</b> you have to generate your own SMBIOS/SerialNumber, SMBIOS/BoardSerialNumber and SMBIOS/SmUUID.

You can either install your hackintosh all by yourself or you can use my EFI folders to install and run the hackintosh.
If your device have i7 or i3 processor you need create diffrent CpuFriendProvider.kext with <a href="https://github.com/fewtarius/CPUFriendFriend">CpuFriendFriend</a> tool.
<h1>Kexts</h1>
ACPIBatteryManager.kext 
<br>
AirPortAtheros40.kext 
<br>
AppleALC.kext 
<br>
AtherosWiFiInjector.kext 
<br>
CPUFriend.kext
<br>
CPUFriendDataProvider.kext
<br>
HS80211Family.kext 
<br>
Lilu.kext 
<br>
RTCMemoryFixup.kext
<br>
RealtekRTL8111.kext 
<br>
USBMap.kext 
<br>
VirtualSMC.kext 
<br>
VoodooI2CSynaptics.kext 
<br>
VoodooPS2Controller.kext 
<br>
WhateverGreen.kext 
