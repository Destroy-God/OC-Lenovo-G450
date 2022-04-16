# OC-Lenovo-G450
OpenCore EFI For Lenovo G450
# Note
1.This Laptop is very old, this is just a test, please do not use it for daily use\
2.Windows won't start because DSDT needs to be modified\
3.Please use your own DSDT and change the EHC inside to EH0.\
4.Please make SSDT-EC yourself, here is the tutorial:\
https://dortania.github.io/Getting-Started-With-ACPI/Universal/ec-fix.html
\
5.ssdt1, ssdt2, ssdt3 are useless, you can delete them in the configurator.\
6.This Laptop Only Supported Legacy BIOS,Use Emulated UEFI Environment.\
# Information for this computer:
macOS version: 10.11.6 El Capitan(Last supported version, newer versions may require FakeCPUID, but I don't know how to use it for now)\
CPU: Intel Pentium T4300 (Penryn)\
GPU: Nvidia G210M(No Web Driver required)\
Memory: 2GB x2 Dual Channel\
Ethernet: Broadcom BCM5906M(Using BCM5722D or BCM5906MEthernet)\
Wireless: Qualcomm AR9285(Using ToledaARPT,Switched from Broadcom BCM4312 which is not available)\
Audio: Conexant CX20561(Using AppleALC)\
# Unusable/Unusual Hardware:
USB 1.1（Enabling it causes a kernel panic，This may render some mouse or keyboards unusable）\
Trackpad(Can't use gestures)\
Backlight Control(Can't be adjusted in settings, but you can use shortcut keys)
# Screenshot
Forgot. :)
