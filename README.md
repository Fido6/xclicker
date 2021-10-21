<p align="center">
	<img src="https://raw.githubusercontent.com/robiot/XClicker/main/img/banner.png" alt="XClicker" />
</p>
<p align="center">
	<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/robiot/XClicker/total?label=GitHub%20Downloads" />
  	<a href="https://aur.archlinux.org/packages/xclicker"><img alt="AUR version" src="https://img.shields.io/aur/version/xclicker" /></a>
  	<img alt="GitHub Issues" src="https://img.shields.io/github/issues/robiot/XClicker.svg" />
  	<img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/robiot/XClicker" /></a>
</p>

## What is XClicker?
XClicker is a open-source, easy to use, feature-rich, **blazing fast** Autoclicker for linux desktops using x11.

![Example image](https://raw.githubusercontent.com/robiot/XClicker/main/img/newexample.png)

## Main features
 * Simple layout;
 * Safe mode, to protect from unwanted behaviour;
 * Autoclick with a specified amount of time between each click;
 * Choose mouse button [Left/Right/Middle];
 * Repeat until stopped or repeat a given amount of times;
 * Click on a specified location only;

### How much cps?
The highest I have got with it was around **750cps**, but that was still with 1 millisecond interval.\
With 0 millisecond interval, the focused application may freeze.

## Building

After cloning the repository, you only have to run this one command. The executable will be placed in **./build/release/src/xclicker**.
```
$ make release
```

## Installing
Check out the [Installation Guide](https://github.com/robiot/XClicker/wiki/Installation)

## License
XClicker is licensed under GPL-3.0 LICENSE.

Dependencies are licensed by their own.
