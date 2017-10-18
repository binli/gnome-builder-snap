snap package for gnome-builder.

3.20.4
===
Enable the source in apt first, after that run "apt-get update", and "apt-get source gnome-builder" at the 3.20.4 directory.

The snapcraft could build it successfully.

![gnome-builder-3-20-4][Demo-3.20.4]

3.24
===
Get the source code from git://git.gnome.org/gnome-builder , but it failed cause of the version of library is too low.

Snap plugins for gnome-builder
===
git@github.com:jhenstridge/gnome-builder.git

Now it can't work for 3.20.4, I could build it when disable some APIs.

[Demo-3.20.4]:https://github.com/binli/gnome-builder-snap/raw/master/images/3-20-4-demo.png
