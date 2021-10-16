# Arcobk

1. Back up of my dotfiles for xmonad arch linux

2. After installation of xmonad arcolinux pull this repo and copy all files to right directories.
3. Install all programs from pkglist.txt:
   sudo pacman -S $(comm -12 <(pacman -Slq | sort) <(sort pkglist.txt))
4. Install all packs to nvim
5. Check for missing AUR packs
6. Create pkglist.txt pacman -Qe | awk '{print $1}' > pkglist.txt
