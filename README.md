# macOS Catalina on Lenovo ThinkPad L440
  with OpenCore 0.6.3
  ![picture](https://github.com/agensosis/thinkpad-l440/blob/main/pic1.png)
##  Whats working
 - Intel HD4600
 - Audio + Mircophone (Need to switch manually)
 - Brightness (Brightness Fnkey not yet working)
 - Sleep, Shutdown/Restart
 - Battery status
 - Wlan + Bluetooth (Intel AC 7260)
 - LAN
 - Stock Touchpad with gesture
 - USB 2.0 + USB 3.0
 - DVD Drive
## Know issues
 - SD Card reader
 - "Unknown card" Notification on status bar
 
 ## Todo
 - Make SD Card reader work
 - Upgrade to 16GB RAM
 
 ## UEFI Configuration
 - Config > Network > Wake on LAN : Disabled
 - Config > USB > USB 3.0 Mode : Enable
 - Config > Serial ATA > Mode : AHCI
 - Config > Intel (R) Smart Connect Technology : Disable
 - Security - Security Chip : Disabled
 - Security - Virtualization : Enabled
 - Security - IO Port Access > Fingerprint : disabled
 - Security - Internal Device Access : Disabled
 - Security - Anti theft : Disable all include Computrace
 - Security - Secure Boot : Disabled
 - Startup > UEFI/Legacy Boot : UEFI Only
