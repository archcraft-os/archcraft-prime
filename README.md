<p align="center">
<a href="https://archcraft.io"><img src="https://raw.githubusercontent.com/archcraft-os/archcraft-packages/main/archcraft-artworks/files/logo/png/logo-circle/logo-circle-1.png" height="128" width="128" alt="Archcraft"></a>
</p>

<p align="center">
<b>Archcraft Prime : An Ultimate Exclusive Experience</b>
</p>

<p align="center">
  <a href="https://archcraft.io" target="_blank"><img alt="home" src="https://img.shields.io/badge/HOME-blue?style=flat-square"></a>
  <a href="https://wiki.archcraft.io" target="_blank"><img alt="wiki" src="https://img.shields.io/badge/WIKI-blue?style=flat-square"></a>
  <a href="https://archcraft.io/gallery" target="_blank"><img alt="screenshots" src="https://img.shields.io/badge/SCREENSHOTS-blue?style=flat-square"></a>
  <a href="https://www.reddit.com/r/archcraft" target="_blank"><img alt="reddit" src="https://img.shields.io/badge/REDDIT-blue?style=flat-square"></a>
  <a href="https://discord.gg/3PzeJ5S7Pu" target="_blank"><img alt="discord" src="https://img.shields.io/badge/DISCORD-blue?style=flat-square"></a>
  <a href="https://t.me/archcraftos" target="_blank"><img alt="telegram" src="https://img.shields.io/badge/TELEGRAM-blue?style=flat-square"></a>
  <a href="https://matrix.to/#/#archcraft:matrix.org" target="_blank"><img alt="matrix" src="https://img.shields.io/badge/MATRIX-blue?style=flat-square"></a>
</p>

[![gif](./prime.gif)](https://ko-fi.com/s/c925a2a8c1)

---

### From Archcraft Wiki

- [Things To Do After Installing Archcraft](https://wiki.archcraft.io/docs/install-archcraft/post-install)
- [Install Archcraft With Calamares](https://wiki.archcraft.io/docs/install-archcraft/install-with-calamares)
- [Install Archcraft With ABIF](https://wiki.archcraft.io/docs/install-archcraft/install-with-abif)
- [Create A Bootable USB With Archcraft](https://wiki.archcraft.io/docs/boot-iso/boot-with-usb)
- [Boot Archcraft ISO With GRUB2 Bootloader](https://wiki.archcraft.io/docs/boot-iso/boot-with-grub)

### Overview

The flavor of Archcraft is a result of many people's requests and polls ([discord](https://discord.com/channels/888837929789710387/890046536778678355/1091409213147844658), [telegram](https://t.me/archcraftos/48993)) I did on communities. Based on the majority of voting in favor of the creation of this flavor, I present you the **`Archcraft Prime`**.

**Archcraft Prime** offers every (`Not the one released after Prime`) exclusive stuff of Archcraft in ***One Single ISO***. It has [`Openbox`](https://ko-fi.com/s/9b2de4919f), [`Bspwm`](https://ko-fi.com/s/5c859ad898) and [`i3wm`](https://ko-fi.com/s/a529474abf) as well as all the exclusive wayland compositors ([`Sway`](https://github.com/archcraft-os/archcraft-sway), [`Wayfire`](https://github.com/archcraft-os/archcraft-wayfire), [`River`](https://github.com/archcraft-os/archcraft-river), [`Hyprland`](https://github.com/archcraft-os/archcraft-hyprland) and [`Newm`](https://github.com/archcraft-os/archcraft-newm)) pre-installed.

It's basically a **Bundle** that has everything Archcraft has to offer exclusively. The idea behind this is to provide everything for less and If users want everything, they don't need to get them separately, and have to install everything individually, Instead they can get the complete bundle and all they need to do is, Install the ISO (with the choice of their favorite WM or WC)

**1st ISO Generation :** `Apr 28, 2023` <br>
**2nd ISO Generation :** `May 06, 2023` <br>
**3rd ISO Generation :** `July 10, 2023` <br>
**4th ISO Generation :** `October 14, 2023` <br>
**Last Updated :** `October 14, 2023`

<details>
<summary><b>Changelogs</b></summary>

## October 2023
- Updated ISO profile
- Latest base with new packages
- Added `archcraft-randr` app to manager display and monitors (Only X11)
- Updated all window managers
  - Clean PKGBUILDs (`with only needed deps`) and updated code
  - Directory **openbox-themes** now merged into **openbox**, new config structure for openbox
  - Added **example layouts** for multi-monitors in `bspwmrc` (single, two-monitors, three-monitors layouts)
  - Added multi-monitor support in all available WMs (use `archcraft-randr`)
- Updated all wayland compositors
  - Added better example for multi-monitor support in...
    - Sway: `~/.config/sway/sway-output`
    - Wayfire: `~/.config/wayfire.ini`
    - River: `~/.config/river/init`
    - Hyprland: `~/.config/hypr/hyprland.conf`
    - Newm: `~/.config/newm/config.py`
- Added `wipe` ability in ABIF
- Fixed issue with `help and tips` app
- Removed `python2` as it's not needed anymore
- Small improvements and bugs fixed.

---

## July 2023
- Updated ISO profile with latest archiso
- Latest base with new packages
- Fixed `xfce-power-manager` issue (not locking the screen on lid close)
- Fixed sddm not saving the last used session issue
- Added a calculator app
- Added Welcome and Help-and-Tips App
- Fixed Scaling issue in QT apps in wayland
- **`Openbox WM`**
  - Added `tint2` as alternate panel (in all themes)
  - Ability to switch between panels
  - Added `bluetooth` module on both panels
  - Added a rofi `bluetooth` applet
  - Fixed window resizing issue via each side of window
  - etc
- **`BSPWM`**
  - Added `bluetooth` module on polybar (in all themes)
  - Added a rofi `bluetooth` applet
  - etc
- **`I3wm`**
  - Added `bluetooth` module on polybar (in all themes)
  - Added a rofi `bluetooth` applet
  - etc
- **`Sway, Wayfire, River, Hyprland`**
  - Added `bluetooth` module on Waybar
  - Added a rofi `bluetooth` applet
  - Added `alacritty` terminal
  - Added `pywal` support
  - Improved a lot of scripts
  - etc
- Many small bugs fixed.

---

## May 2023
- Nothing Much, Just Updated The ISO with Fixed NEWM

---

## April 2023
- Created the ISO base from scratch
- Grub2 bootloader with themes
- Customized Plymouth & SDDM
- Basic Applications Only, No Bloatware
- Calamares Installer (Graphical) with ability to choose WMs/WCs
- ABIF (CLI) Installer as secondary installer
- Full Network Manager Support, Various VPN plugins
- Built-in Bluetooth Support
- Pipewire For Sound/Audio (Systemwide, Bluetooth, Jack)
- Built-in Printer Support
- Almost All Audio, Video and Image Codecs
- Full File manager functionality (Mounting, Networking, Archiving, etc)
- Built-in AUR support
- Minimal User Interface
- All Premium Window Managers (Openbox, Bspwm and i3wm)
- All Exclusive Wayland Compositors (Sway, Wayfire, River, Hyprland, Newm)
- Archcraft Icons, Themes, Wallpapers, Fonts
- Etc

</details>

### Get The ISO

You can download the latest `ISO` from [ko-fi :coffee:](https://ko-fi.com/s/c925a2a8c1).

> Default `username` and `password` is **liveuser**.

For Graphical Installation Instructions, See [Install Archcraft With Calamares](https://wiki.archcraft.io/docs/install-archcraft/install-with-calamares)<br>
For CLI (abif) Installation Instructions, See [Install Archcraft With ABIF](https://wiki.archcraft.io/docs/install-archcraft/install-with-abif)

---

**`WARNING : VM -`** This ISO works with VMs (Virtualbox, VMware, Qemu, etc). But **only the Window Managers** (X11) will work on it. All **the Wayland Compositors will not work**. If worked, They will be very laggy due to poor 3D support.

#
<br>

**`WARNING : Nvidia -`** There is no official support for Nvidia. Unfortunately, their drivers are so messy, and their products so random, that it’s impossible to help if `the wayland compositors on this ISO` don’t work on your machine. Every card seems to be random, and might work perfectly, or not work at all. However...<br>
The ISO have everything configured **out-of-the-box**, Needed to run a _wayland compositor_ on **Nvidia**. It has all the needed modules enabled into `mkinitcpio.conf` and **initrd**, `Kernel parameters` are added, and the needed proprietary graphics drivers installed.<br>
Now, It's your choise to give it a try.

**Update:** As Reported, Users are able to boot and Install the Latest ISO (April) on their Nvidia Machines. Everything is working fine.

**More info :** [Sway Installation](https://wiki.archlinux.org/title/Sway#Installation), [Hyprland Nvidia](https://wiki.hyprland.org/Nvidia/), [wayland Requirements](https://wiki.archlinux.org/title/wayland#Requirements), [DRM_kernel_mode_setting](https://wiki.archlinux.org/title/NVIDIA#DRM_kernel_mode_setting), [NVIDIA#Installation](https://wiki.archlinux.org/title/NVIDIA#Installation)

#
<br>

**`WARNING : Iris XE -`** Some users reported that, The Wayland Compositors on this ISO does not work on systems with `Intel Iris XE` GPUs. Keep that in mind while going for it.

---

### Screenshots

<!-- Openbox -->

<details>
<summary><b>Openbox</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/openbox/openbox_1.png)|![img](https://archcraft.io/images/premium/openbox/openbox_2.png)|![img](https://archcraft.io/images/premium/openbox/openbox_3.png)|![img](https://archcraft.io/images/premium/openbox/openbox_4.png)|![img](https://archcraft.io/images/premium/openbox/openbox_5.png)|

| Screenshot 6 | Screenshot 7 | Screenshot 8 | Screenshot 9 | Screenshot 10 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/openbox/openbox_6.png)|![img](https://archcraft.io/images/premium/openbox/openbox_7.png)|![img](https://archcraft.io/images/premium/openbox/openbox_8.png)|![img](https://archcraft.io/images/premium/openbox/openbox_9.png)|![img](https://archcraft.io/images/premium/openbox/openbox_10.png)|

| Screenshot 11 | Screenshot 12 | Screenshot 13 | Screenshot 14 | Screenshot 15 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/openbox/openbox_11.png)|![img](https://archcraft.io/images/premium/openbox/openbox_12.png)|![img](https://archcraft.io/images/premium/openbox/openbox_13.png)|![img](https://archcraft.io/images/premium/openbox/openbox_14.png)|![img](https://archcraft.io/images/premium/openbox/openbox_15.png)|

| Screenshot 16 | Screenshot 17 | Screenshot 18 | Screenshot 19 | Screenshot 20 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/openbox/openbox_16.png)|![img](https://archcraft.io/images/premium/openbox/openbox_17.png)|![img](https://archcraft.io/images/premium/openbox/openbox_18.png)|![img](https://archcraft.io/images/premium/openbox/openbox_19.png)|![img](https://archcraft.io/images/premium/openbox/openbox_20.png)|

</details>

<!-- Bspwm -->

<details>
<summary><b>Bspwm</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/bspwm/bspwm_1.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_2.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_3.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_4.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_5.png)|

| Screenshot 6 | Screenshot 7 | Screenshot 8 | Screenshot 9 | Screenshot 10 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/bspwm/bspwm_6.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_7.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_8.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_9.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_10.png)|

| Screenshot 11 | Screenshot 12 | Screenshot 13 | Screenshot 14 | Screenshot 15 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/bspwm/bspwm_11.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_12.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_13.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_14.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_15.png)|

| Screenshot 16 | Screenshot 17 | Screenshot 18 | Screenshot 19 | Screenshot 20 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/bspwm/bspwm_16.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_17.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_18.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_19.png)|![img](https://archcraft.io/images/premium/bspwm/bspwm_20.png)|

</details>

<!-- i3wm -->

<details>
<summary><b>i3wm</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/i3wm/i3_1.png)|![img](https://archcraft.io/images/premium/i3wm/i3_2.png)|![img](https://archcraft.io/images/premium/i3wm/i3_3.png)|![img](https://archcraft.io/images/premium/i3wm/i3_4.png)|![img](https://archcraft.io/images/premium/i3wm/i3_5.png)|

| Screenshot 6 | Screenshot 7 | Screenshot 8 | Screenshot 9 | Screenshot 10 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/i3wm/i3_6.png)|![img](https://archcraft.io/images/premium/i3wm/i3_7.png)|![img](https://archcraft.io/images/premium/i3wm/i3_8.png)|![img](https://archcraft.io/images/premium/i3wm/i3_9.png)|![img](https://archcraft.io/images/premium/i3wm/i3_10.png)|

| Screenshot 11 | Screenshot 12 | Screenshot 13 | Screenshot 14 | Screenshot 15 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/i3wm/i3_11.png)|![img](https://archcraft.io/images/premium/i3wm/i3_12.png)|![img](https://archcraft.io/images/premium/i3wm/i3_13.png)|![img](https://archcraft.io/images/premium/i3wm/i3_14.png)|![img](https://archcraft.io/images/premium/i3wm/i3_15.png)|

| Screenshot 16 | Screenshot 17 | Screenshot 18 | Screenshot 19 | Screenshot 20 |
| --- | --- | --- | --- | --- |
|![img](https://archcraft.io/images/premium/i3wm/i3_16.png)|![img](https://archcraft.io/images/premium/i3wm/i3_17.png)|![img](https://archcraft.io/images/premium/i3wm/i3_18.png)|![img](https://archcraft.io/images/premium/i3wm/i3_19.png)|![img](https://archcraft.io/images/premium/i3wm/i3_20.png)|

</details>

<!-- Sway -->

<details>
<summary><b>Sway</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 |
| --- | --- | --- | --- |
|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_1.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_2.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_3.png)|![sway](https://raw.githubusercontent.com/archcraft-os/archcraft-sway/main/screenshots/sway_4.png)|

</details>

<!-- Wayfire -->

<details>
<summary><b>Wayfire</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_1.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_2.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_3.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_4.png)|![wayfire](https://raw.githubusercontent.com/archcraft-os/archcraft-wayfire/main/screenshots/wayfire_5.png)|

</details>

<!-- River -->

<details>
<summary><b>River</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 |
| --- | --- | --- | --- |
|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_1.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_2.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_3.png)|![river](https://raw.githubusercontent.com/archcraft-os/archcraft-river/main/screenshots/river_4.png)|

</details>

<!-- Hyprland -->

<details>
<summary><b>Hyprland</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 |
| --- | --- | --- | --- |
|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_1.png)|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_2.png)|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_3.png)|![hyprland](https://raw.githubusercontent.com/archcraft-os/archcraft-hyprland/main/screenshots/dark/hypr_4.png)|

</details>

<!-- NEWM -->

<details>
<summary><b>Newm</b></summary>

| Screenshot 1 | Screenshot 2 | Screenshot 3 | Screenshot 4 | Screenshot 5 |
| --- | --- | --- | --- | --- |
|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_1.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_2.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_3.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_4.png)|![newm](https://raw.githubusercontent.com/archcraft-os/archcraft-newm/main/screenshots/blur/newm_5.png)|

</details>

### Videos

| Openbox | Bspwm | i3wm | sway |
| --- | --- | --- | --- |
|[![vid](https://archcraft.io/images/premium/openbox_p.png)](https://youtu.be/ci_nMh0-7vA)|[![vid](https://archcraft.io/images/premium/bspwm_p.png)](https://youtu.be/GnF9CK_gwW4)|[![vid](https://archcraft.io/images/premium/i3wm_p.png)](https://youtu.be/NYCX8o-fmoo)|[![vid](https://archcraft.io/images/premium/sway_p.png)](https://youtu.be/ASlQcf8Jc0I)|

| Wayfire | River | Hyprland | Newm |
| --- | --- | --- | --- |
|[![vid](https://archcraft.io/images/premium/wayfire_p.png)](https://youtube.com/playlist?list=PLXH9dADRlWHYk_5Boqiu7L3HcLVC83TWU)|[![vid](https://archcraft.io/images/premium/river_p.png)](https://youtu.be/MwnK6arB2Rc)|[![vid](https://archcraft.io/images/premium/hyprland_p.png)](https://youtu.be/t6Zd2F7rtPw)|[![vid](https://archcraft.io/images/premium/newm_p.png)](https://youtube.com/playlist?list=PLXH9dADRlWHaXM3Q8G_gaunljITif3cUl)|

---

- For **Keybindings**, See `Help and Tips` app.
- I Hope you'll enjoy this flavor of Archcraft.
- Thank you for supporting Archcraft.
