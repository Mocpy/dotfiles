Post Installation Setup
=======================

Arch Linux packages
---------------
Instaling packages:
```bash
sudo pacman -S <package name>
```
packages list:
- `alacritty`
- `ark`
- `aspell`
- `aspell-cs`
- `aspell-en`
- `autojump`
- `base`
- `base-devel`
- `canon-pixma-ts5055-complete`
- `code`
- `cups`
- `dolphin`
- `dpkg`
- `element-desktop`
- `firefox`
- `git`
- `git-lfs`
- `gparted`
- `grub`
- `gwenview`
- `htop`
- `intel-ucode`
- `kate`
- `kdeconnect`
- `kio-gdrive`
- `konsole`
- `libreoffice-fresh`
- `libreoffice-fresh-cs`
- `linux`
- `linux-firmware`
- `nano`
- `neofetch`
- `networkmanager`
- `noto-fonts-emoji`
- `opera`
- `pacman`
- `plasma-meta`
- `python-pip`
- `python-poetry`
- `rust`
- `sddm`
- `snapd`
- `spectacle`
- `spotifyd`
- `thunderbird`
- `tk`
- `tmux`
- `ttf-jetbrains-mono`
- `ttf-ms-fonts`
- `unzip`
- `usbimager`
- `vlc`
- `wine`
- `xclip`
- `xf86-input-synaptics`
- `xss-lock`
- `yay-git`
- `zola`
- `zram-generator`
- `zsh`
- `zsh-autosuggestions`
- `zsh-syntax-highlighting`

Install all packages from list:
1. download 'ArchLinux_packages.txt'
2. go to the directory there file is instaled
```bash
cd <name of that directory>
```
3. Run the following command to install the packages listed in your .txt file using sudo pacman -S

```bash
sudo pacman -S --needed - < ArchLinux_packages.txt
```


AUR packages
---------------
Instaling AUR packages:
```bash
yay -S <package name>
```
package list :
- `autojump`
- `canon-pixma-ts5055-complete`
- `snapd`
- `ttf-ms-fonts`
- `usbimager`
- `yay-git`

Install all packages from list:
1. download 'AUR_packages.txt'
2. go to the directory that file is instaled
```bash
cd <name of that directory>
```
3. Run the following command to install the packages listed in your .txt file using yay -S

```bash
yay -S --needed - < AUR_packages.txt
```
