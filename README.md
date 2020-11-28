# ASUS P8Z68-V PRO/GEN3 installing macOS High Sierra

Configuration and Post-Install Guides
You will need access to another macOS machine to follow this tutorial. 
Here is how I did it:

## Create a USB Bootable Installer Flash Drive
https://osxdaily.com/2017/09/27/create-macos-high-sierra-bootable-installer-usb/
<br><br>Download macOS High Sierra to /Applications folder on your Mac.
Once it has finished downloading, plug your flash drive into a USB slot.
Erase the USB drive with Disk Utility, making sure you format it as MacOS Extended Journaled with a GUID partition table.
Now, type the following command into your Terminal app. <br><br>
`sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/UNTITLED && say Boot Installer Complete`

Once that is done, install Clover to the USB flash drive.
