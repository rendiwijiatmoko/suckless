# Rendi's build of dwm - dynamic window manager
dwm is an extremely fast, small, and dynamic window manager for X.

## Requirements
In order to build dwm you need the Xlib header files.

## Installation
Edit config.mk to match your local setup (dwm is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install dwm (if
necessary as root):
```shell
$ sudo make clean install
```

## Running dwm
Add the following line to your .xinitrc to start dwm using startx:
```bash
...

exec dwm
```

## Configuration
The configuration of dwm is done by creating a custom config.h
and (re)compiling the source code.
