# amoled-arch-hyprland

install yay:
```
pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay-bin.git && cd yay-bin && makepkg -si
```

install all programs:
```
yay -Syuu adw-gtk3 apple-fonts btop dconf-editor dunst efibootmgr firefox flatpak github-cli gnome-tweaks-git gst-plugin-pipewire htop hyprland hyprpaper intel-media-driver intel-ucode iwd kitty libva-intel-driver libva-mesa-driver linux-firmware linux-zen man-db nano nautilus network-manager-applet nwg-look pavucontrol pfetch pipewire-alsa qbittorrent-enhanced smartmontools starship ttf-apple-emoji ttf-jetbrains-mono-nerd unzip visual-studio-code-bin wget wireless_tools wofi xdg-desktop-portal-hyprland xfce4-settings xorg-server xorg-xinit
```
install firefox user.js
```
put in profile location: ~/.mozilla/firefox/xxxx.default-release/user.js
```
laptop tweaks:

power
```
sudo pacman -S thermald ; yay -S envycontrol auto-cpufreq
```
```
sudo auto-cpufreq --install ; envycontrol -s integrated
```
lid
```
sudo mv ./setkeycodes.service /etc/systemd/system/setkeycodes.service ; sudo systemctl enable setkeycodes.service
```
