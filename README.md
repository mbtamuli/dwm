# Personal fork of [dwm](https://dwm.suckless.org/)

## Patches added

* [Change Mod1 key to the Windows key](https://dwm.suckless.org/customisation/windows_key/)

## Steps to build

* Get the tools required to build packages.
  ```
  sudo pacman -S base-devel
  ```
* Clone this repo.
  ```
  git clone git@github.com:mbtamuli/dwm.git
  ```
* Get dependencies, build and then remove the installed dependencies after a successful build.
  ```
  cd dwm
  makepkg -sri
  ```
### Note
1. I'm just providing steps for the distribution I'm currently using - Arch Linux.
2. Run the commands as normal user(non-root).

For more details, visit [the wiki](https://wiki.archlinux.org/index.php/Arch_User_Repository#Installing_packages)
