# macOS Catalina on Lenovo ThinkPad L440
  with OpenCore 0.6.3
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
          > USB > USB 3.0 Mode : Enable
          > Serial ATA > Mode : AHCI
          > Intel (R) Smart Connect Technology : Disable
 - Security - Security Chip : Disabled
            - Virtualization : Enabled
            - IO Port Access > Fingerprint : disabled
            - Internal Device Access : Disabled
            - Anti theft : Disable all include Computrace
            - Secure Boot : Disabled
 - Startup > UEFI/Legacy Boot : UEFI Only
 
