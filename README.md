# iot

Ubuntu 20.04 Desktop (minimal installation)

Installing Arduino IDE v1.8.13

Errors encountered during launch (post-install)

Failed to load module "canberra-gtk-module"

From developer:

GTK+ is a toolkit for creating GUIs, most of the default Ubuntu desktop, and the GNOME desktop environment, is developed using it.          libcanberra is a library for playing sounds. libcanberra-gtk-module, then, is the module that takes GUI events from GTK+ (like pressing  a button, or minimizing a window) and plays some configured sound.

Fix:

sudo apt-get install libcanberra-gtk-module
