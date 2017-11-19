Lioshi Icon Theme
================

Lioshi is a modern freedesktop icon theme whose design is based around the use of bold colours and simple geometric shapes to compose icons. Each icon has been meticulously designed for pixel-perfect viewing.

While it does take some inspiration from the icons in Google's Material Design, some aspects have been adjusted to better suit a desktop environment.

## Copying or Reusing

Lioshi is licenced under the terms of the [Creative Commons Attribution-ShareAlike](https://creativecommons.org/licenses/by-sa/4.0/). When reusing this work be sure to include a proper attribution:

> "[Lioshi Icons](http://snwh.org/lioshi/icons)" by [Sam Hewitt](http://samuelhewitt.com/) is licensed under [CC-SA-4.0](http://creativecommons.org/licenses/by-sa/4.0/)

Software that is included is free software; you can redistribute it and/or modify it under the terms of the [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.txt)

## Downloading Lioshi

Download instructions are available on the [official site](https://snwh.org/lioshi/download).

### Build &amp; Install

You can build and install the Lioshi icon themes from source, provide you have ```gnome-common``` installed on your system.

    ./autogen.sh
    make
    sudo make install


Fedora: 

    sudo dnf install xorg-x11-apps

Generate icons ancd cursor after changes (clean bitmaps directory before) and in src directory launch:

    sh render-cursors.sh 

And then

    ./autogen.sh
    make
    sudo make install

