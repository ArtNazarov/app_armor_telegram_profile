# app_armor_telegram_profile
Working profile for telegram-desktop package in archlinux

# installation

1. just bin.telegram-desktop to /etc/apparmor.d/ folder
2. edit download directory
3. Start complain mode
```
aa-compain /etc/apparmor.d/bin.telegram-desktop
```
3. Set profile to enforce mode
```
aa-enforce /etc/apparmor.d/bin.telegram-desktop
```
