<p align="center">
  <a href="https://getcryst.al">
    <img src="https://getcryst.al/site/assets/other/icon-iso.png" alt="Logo" width="150" height="150">
  </a>
</p>
<p align="center"> 
<h2 align="center"> Crystal ISO </h2>
</p>
<p align="center">
    <a href="https://github.com/crystal-linux/iso"><img src="https://github.com/crystal-linux/iso/actions/workflows/build.yml/badge.svg"></a>
    <a href="https://github.com/crystal-linux/.github/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" alt="License">
    <a href="https://github/crystal-linux/iso"><img alt="GitHub isses" src="https://img.shields.io/github/issues-raw/crystal-linux/iso"></a>
    <a href="https://github/crystal-linux/iso"><img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr-raw/crystal-linux/iso"></a><br>
    <a href="https://twitter.com/intent/user?screen_name=crystal_linux"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/crystal_linux?style=flat?color=blue">
    <a href="https://discord.gg/hYJgu8K5aA"><img alt="Discord" src="https://img.shields.io/discord/825473796227858482?color=blue&label=Discord&logo=Discord&logoColor=white"> </a>
    <a href="https://github.com/axtloss"><img src="https://img.shields.io/badge/Maintainer-@axtloss-brightgreen" alt=The maintainer of this repository" href="https://github.com/axtloss"></a>
</p>

<p align="center"> Build or download the Arch-based Crystal Linux iso. </p>

## Dependencies:
* `pacman-contrib`
* `archiso`
* `squashfs-tools`

## How to Build:
You will have to use Arch or Arch-Based distros to build this ISO File.
* Install Dependencies
* Go to the project folder
* Run `./build_iso.sh`
    * If you get an error about `/tmp/<something>` running out of space, reboot (to clear tmpfs), then re-run with a dir to use as temp (e.g. `./build_iso.sh FOOBAR`)
    * If you also add a second arg as in `./build_iso.sh /some/folder testing`, you'll pull from our testing repo
