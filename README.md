# PhotoGIMP
A simple Patch for GIMP 2.10+ for Photoshop Users

* Tool organization to mimic the position of Adobe's Photoshop;
* Hundreds of new fonts by default;
* New Python filters installed by default, such as "heal selection";
* New Splash Screen
* New default settings to maximize space on the canvas;
* Shortcuts setted for the similars on Photoshop, following Adobe's Documentation;
* New icon and Name from custom .desktop file.

# How to Install

This build is all about flatpak, but also "just files" that you can use on any version of GIMP (.deb,.rpm, Snap, AppImage, Windows, macOS), just check the localization of the GIMP files on every system/package.

## Install on a Flatpak enviroment

* First of all, you need to have the latest GIMP installed on your system using Flatpak(https://flatpak.org/setup/)
* Install GIMP Flatpak through your AppCenter/Package Manager or terminal:
```flatpak install flathub org.gimp.GIMP```

## Installing this Patch

Inside of the .zip file from the [releases page](https://github.com/Diolinux/PhotoGIMP/releases) you'll find three hidden folders (on Linux, using the dot before its name). All of this folders has to be extracted on your /home/$USER folder, overriting everything if you already has a the same files from a old installation.

The file has this directories:

* .icons (wich have a new PhotoGIMP icon)
* .local (wich contaion the .desktop file personalized)
* .var (wich contation the flatpak patch customization for GIMP 2.10+)

If you just want the PhotoGIMP custom without change the original GIMP icon and its name, just extract only the .var folder to your home folder.

## Credits

This project would't be possible without the amazing GIMP Team.
The Photo from the new Splash is from [Isabella Mariana](https://www.pexels.com/pt-br/@isabella-mariana-1022505)
A BIG thanks to all Diolinux's supporters on Twitch and YouTube.
