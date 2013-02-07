Clone Terminal Window
=====================

This is a little utility to clone a gnome terminal window, and attempt to
restore as much of the state as possible:

 * The working directory
 * The remote host (via ssh)
 * root access

It gleans all of this state from the root window.

Installation
------------

Install ruby and xdotool (both available in apt).  Create a hotkey in your
window manager that will run this script (I'm using CTRL-SHIFT-T.)
