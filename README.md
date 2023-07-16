# Nice GRUB Theme
 A good looking GRUB2 theme with MacOS wallpapers. 

# Customisations
 You can change the default logo by replacing `logo.png`. It also includes support for icons in the boot menu for all major OSes. If you find that your specific distro/OS is not supported (or maybe you just want to change how the icons look), you can also change them in the icons folder. Additionally, there are several different background styles in both light and dark themes.

# Installation and Setup
1. Clone the repo or download and unzip the main branch into `/boot/grub/themes`
2. Next, change `GRUB_THEME` in `/etc/default/grub` to `/boot/grub/themes/nice-grub-theme/theme.txt`
3. Rebuild grub by running `sudo grub-mkconfig -o /boot/grub/grub.cfg`
