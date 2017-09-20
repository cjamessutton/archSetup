# Overview

I should start this by emphasizing my lack of experience. This is my first foray into setting up an entire graphical user interface from the ground up. As a result, I can't guarantee best or even correct practices. Feel free to offer suggestions or even submit PR's.

## Objective

This repo should provide an install script that will allow you to easily set up what I have on my box, with the prerequisite of installing git. It will include options to install optimizations for a laptop, as well, which will probably need some tweaking for your individual box. Everything else should work seamlessly with a new Arch install.

## Resources

[Luke Smith's i3-gaps configs](https://github.com/LukeSmithxyz/voidrice) - This build will not be married to terminal anywhere near as much, but it will be a valuable resource for anybody looking to find extra examples of what I'm doing.

[/r/unixporn](https://www.reddit.com/r/unixporn/) - This is my go-to for inspiration and cool resources from the wider ricing community.

## Package Groups

### OS

**Display Server** - Xorg is the most common version of this. It provides the API for applications that use the GUI to communicate with the OS > Kernel > Hardware. Wayland is a more modern DS.

**Display Drivers** - These let your OS converse with video card. They are machine specific and will be a prerequisite for the tools provided here.

### GUI

**Desktop Environment** - This is a pre-packaged group of tools to provide a compete GUI experience. They typically include a login (display manager, dm), window manager (wm), terminal emulator (this is Linux, after all), file manager, text editor, theme and icons, panel/tray/bar, and default apps (music, video, offic, browser). *The essential parts of that list are the display manager, window manager, and panel/tray/bar. You could make an argument for a terminal emulator.* This repo can be thought of as a desktop environment.

**Display Manager** - This is a login screen that will display after your system has booted. Many of them will also let you select which window manager you want to use. LightDM and GDM are some examples. They can be graphical or terminal.

**Window Manager** - Controls the placement and appearance of windows within a GUI. i3, bspwm, and OpenBox are some examples.

### Core Workflow

### Laptop Utilities

https://wiki.archlinux.org/index.php/laptop

### Apps

Music and video

# Instructions
