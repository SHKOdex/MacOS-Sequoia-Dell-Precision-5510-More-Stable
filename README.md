# MacOS-Sequoia-Dell-Precision-5510-More-Stable

_**-Setup:**_
* Dell Precision 5510 (Emulate: MacBook Pro (15-inch, 2016))
* CPU: Intel Core i7 6820HQ
* iGPU: Intel HD Graphics 530
* dGPU: Nvidia Quadro M1000M
* RAM: 8GBx2-DDR4@2133mhz
* Screen: 4K-touch (3840x2160)
* NVME M.2: 250GB
* SSD: 512GB

--------------------------------------------------------------

_**-Working:**_
* WI-FI (Always working, even in recovery mode, so you can install the operating system using wifi)
* Bluetooth (Airpods Pro 2, It sounds glitched)
* Siri
* iGPU acceleration
* Not overheat

--------------------------------------------------------------

_**-Not Working:**_
* dGPU -disabled- (Nvidia M1000M)
* Apple Music (Only works with AAC 256kbps transmission and downloads, Dolby Atmos off)

--------------------------------------------------------------

_**How to install:**_

**1- Preparing our usb**
- //_Make sure you back up your EFI, if you modify something save each version. (OPTIONAL): prepare a disk or partition to install MacOS, if everything installs correctly you should have a small 1GB FAT32 partition to save the EFI and boot without a USB_//
- Download Files.zip and extract (You will have two folders left, OC and BOOT)
- Move both folders to the root of a USB with FAT32 format
- Download the MacOS Installer from here https://mrmacintosh.com/macos-sequoia-full-installer-database-download-directly-from-apple/ or another web (The file name is **InstallAssistant.pkg**)
- Move InstallAssistant.pkg to the root of the USB
- You will have on your USB
*BOOT
*OC
*InstallAssistant.pkg

**2- Booting**
- Now, boot OpenCore (The USB that we prepared)
- We wait it loads and shows us a menu with the options Windows, Install Sequoia... We are interested in **Install Sequoia**, we start it by touching Enter
- The MacOS installer will start, once started here, we confirm that the Wi-Fi is working correctly
- We select install Sequoia
- We select the disk or partition where we will install MacOS 
- When it is downloading, we will see that the download time will increase, do not worry about that, that is normal and delayed, let's pay attention to the loading bar
- The system will do several reboots so let's make sure OpenCore starts and not Windows
- When the installation is complete, it will appear in the OpenCore menu, "Windows" and "**Macintosh HD**" menu (we start it)
- _This will start MacOS and its first configuration_

# **If you have questions in the middle of the process or an error, let me know so I can update the guide and explain it better. I no longer have this computer so I had to remember the process without trying it.**
