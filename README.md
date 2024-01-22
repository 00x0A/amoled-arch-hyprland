# amoled-arch-hyprland

install yay:
```
pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay-bin.git && cd yay-bin && makepkg -si
```

install all programs:
```
yay -Syuu acreom-bin adw-gtk3 apple-fonts breeze btop calibre dconf-editor dunst efibootmgr firefox fisher flatpak fuse2 github-cli gnome-tweaks-git gst-plugin-pipewire htop hyprland hyprpaper intel-media-driver intel-ucode iwd kitty libva-intel-driver libva-mesa-driver linux-firmware linux-zen man-db nano nautilus network-manager-applet nwg-look pavucontrol pfetch pipewire-alsa qbittorrent-enhanced smartmontools sof-firmware starship ttf-apple-emoji ttf-jetbrains-mono-nerd unzip visual-studio-code-bin vulkan-intel vulkan-radeon wget wireless_tools wofi xdg-desktop-portal-hyprland xf86-video-amdgpu xf86-video-ati xf86-video-nouveau xf86-video-vmware xfce4-settings xorg-server xorg-xinit
```
install firefox user.js
```
put in profile location: ~/.mozilla/firefox/xxxx.default-release/user.js
```
