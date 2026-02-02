# my-os
How to install and use my personalized Ubuntu flavor.

## Featured apps and packages
- i3wm
- kitty
- tmux
- emacs
- keepassxc
- dolphin
- arandr


## Install
Follow these indications to flash a drive with the ISO:

##### Download ISO
Follow this link to download the ISO file:
https://drive.google.com/drive/folders/1MEJyVE9BLkV4vCOlgVOH220EnbsBVdYk


##### Flash a USB:
```bash
sudo dd if=<iso_path> of=<drive_path> bs=4M status=progress conv=fsync
sudo eject <drive_path>
```

##### Installer for Ubuntu
Recommended `subiquity`:
```bash
sudo snap install subiquity
sudo snap run subiquity
```
