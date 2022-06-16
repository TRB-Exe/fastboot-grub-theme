# Fastboot theme for GRUB2
Fun Grub2 theme with fastboot logo from xiaomi phones.
# Installation
1. Clone this repository
2. Copy `fastboot-theme` **folder** 
3. Paste folder to `/boot/grub/themes/`
4. Edit `/etc/default/grub` file and edit `GRUB_THEME=`
5. Code: ```GRUB_THEME="/boot/grub/themes/fastboot-theme/theme.txt"```
6. Save file
7. Run command `grub-mkconfig -o /boot/grub/grub.cfg` to update grub config
8. Restart your PC and you can see this theme
