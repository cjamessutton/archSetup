# Overview

I should start this by emphasizing my lack of experience. This is my first foray into setting up an entire graphical user interface from the ground up. As a result, I can't guarantee best or even correct practices. Feel free to offer suggestions or even submit PR's.

This is also explicitly a learning project for myself. I realize tools to do this exact thing are available a thousand times over in public repos. I want to figure out my OS, though, and this seems to be the best way to do so.

## Objective

This repo should provide an install script that will allow you to easily set up what I have on my box, with the prerequisite of installing Arch, git, and a few hardware specific packages. It will include options to install optimizations for a laptop, as well, which will probably need some tweaking for your individual machine. Everything else should work seamlessly with a new Arch install.

## Resources

[Luke Smith's i3-gaps configs](https://github.com/LukeSmithxyz/voidrice) - This build will not be married to terminal anywhere near as much his, but it will be a valuable resource for anybody looking to find extra examples of what I'm doing.

[/r/unixporn](https://www.reddit.com/r/unixporn/) - This is my go-to for inspiration and cool resources from the wider ricing community.

## Package Groups

### OS

**Display Server** - Xorg is the most common version of this. It provides the API for applications that use the GUI to communicate with the OS > Kernel > Hardware. Wayland is a more modern DS.

**Display Drivers** - These let your OS converse with video card. They are machine specific and will be a prerequisite for the tools provided here.

### GUI

**Desktop Environment** - This is a pre-packaged group of tools to provide a compete GUI experience. They typically include a login (display manager, dm), window manager (wm), terminal emulator (this is Linux, after all), file manager, text editor, theme and icons, panel/tray/bar, and default apps (music, video, office, browser). *The essential parts of that list are the display manager, window manager, and panel/tray/bar. You could make an argument for a terminal emulator.* This repo can be thought of as a desktop environment installer.

**Display Manager** - This is a login screen that will display after your system has booted. Many of them will also let you select which window manager you want to use. LightDM and GDM are some examples. They can be graphical or terminal.

**Window Manager** - Controls the placement and appearance of windows within a GUI. i3, bspwm, and OpenBox are some examples.

### Core Workflow

**Terminal emulator** - Once you log in to a GUI, access the actual terminal becomes difficult. A terminal emulator sovles that problem. Since it is a GUi app, it can provide interaction with the mouse, scrolling, and aesthetic tweaks, as well. 

**Text editor** - I'm a little avant garde with this definition. To me, a terminal editor would suffice as a text editor. However, something like sublime or atom may be more appropriate as examples, due to the ease of access they bring to the table.

**Browser** - No computer is truly complete without a way to browse internet. There are so many to choose from that doing so really does become a challenge. Chrome, imo, leads the pack with useful features and a vibrant extension ecossystem, but qutebrowser, vivaldi, and firefox all make powerful arguments for their existence. 

**Music and video** - Play music and video. Terminal music players exist and are awesome. Spotify will be my choice, though, and VLC will be my video player.

### Laptop Utilities

https://wiki.archlinux.org/index.php/laptop

# Instructions
