# Rofi-on-Mac
How to install, config and run rofi on MacOS.

## why rofi on mac
Rofi is an Application Launcher for linux.
for any reason if you want to run rofi(or any other x11 application) on MacOS,
here is how you can do it.

NOTE: running x11 app with following method might no be fully compatible, try it yourself and use on your own risk.

## Requirement
[Homebrew](https://brew.sh/)

[XQuartz](https://www.xquartz.org/)

[Quart-wm](https://gitlab.freedesktop.org/xorg/app/quartz-wm)

[Rofi](https://davatorium.github.io/rofi/)

[Hammerspoon](https://www.hammerspoon.org/) - Optional

## Installation
1.Package Manager

First you need Homebrew(package manager) in order to install and required programs,
or install these program manually(not recommended).

2.Install requirement

This command install x11 application support and rofi on your MacOS,
If you already have homebrew installed, copy these to your terminal:
```bash
$ brew install xquartz quartz-wm rofi
```

3.runing rofi

Now your machine shoult be able to run rofi, by copying this to terminal:
```bash
$ rofi
```
NOTE: Since you are runing rofi though XQuartz on mac, rofi might have some wired behavior.

### about these package
If you want to know more about the package, you can run the following command:
```bash
$ brew info xquartz quartz-wm rofi
```
