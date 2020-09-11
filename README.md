st - simple terminal
============================
Personal fork of suckless.org's st - a simple terminal emulator for X which sucks less.


Patches
------------
* alpha-focus-highlight
* bold-is-not-bright
* boxdraw
* externalpipe
* externalpipe-eternal
* externalpipe-signal
* newterm
* scrollback
* scrollback-mouse
* xresources


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Configuration
-------------
The configuration of st is done by editing config.h and
(re)compiling the source code.
