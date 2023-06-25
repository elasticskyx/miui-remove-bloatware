# Steps to remove MIUI Bloatware using Windows 10 or later
To protect my privacy, save space, optimize battery life and improve the user experience… I found an easy way to remove redundant system apps without root or unlocking the bootloader. This should work on MIUI version 12, 13, 14 or higher.

## Tools to be downloaded
- [Open JDK](https://adoptopenjdk.net/)
- [Universal ADB Drivers](https://xiaomifirmware.com/downloads/download-adb-installer-v1-4-3-drivers-adb-fastboot-tools/)
- [XiaomiADBFastbootTools.jar]()


## Videos for extra help
- [Remove System Apps on ANY Xiaomi Smartphone in 3 EASY steps!](https://www.youtube.com/watch?v=3_rqhoMpr_Y)


## Instructions
1. Enable `USB Debugging` on the MIUI Settings
   
3. Install the Windows tools
   - Download OpenJDK and install
   - Download Universal ADB Drivers and install
   - Save XiaomiADBFastbootTools.jar to Downloads folder
     
4. Run the `XiaomiADBFastbootTools.jar` using:
   > java -jar XiaomiADBFastbootTools.jar


   
### XiaomiADBFastbootTools Application

The Xiaomi ADB/Fastboot tool can be used to uninstall, reinstall, deactivate, and reactivate system apps and services on demand.

![Window](images/XiaomiADBFastbootTools-1.png)


