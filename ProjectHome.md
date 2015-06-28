# Area #

Area is a CAM-related software for pocketing operation.

This project provides library and associated python-module to compute pocket operations.

Written by _Dan Heeks_ <danheeks@gmail.com>, derived from the [kbool](http://boolean.klaasholwerda.nl/bool.html) library written by _Klaas Holwerda_

Here is some tool-path created with [Pocket](Pocket.md) ( Displayed using [HeeksCNC](https://code.google.com/p/heekscnc) ).
![http://libarea.googlecode.com/svn/wiki/pocket2.png](http://libarea.googlecode.com/svn/wiki/pocket2.png)

## Installation ##

### Dependencies ###
To build libarea, you need:
  * CMake
  * Python (with developers files)
  * Python Boost (with developers files)

### Fetch sources ###
```
svn checkout http://libarea.googlecode.com/svn/trunk/ libarea
```

### Build ###
#### Under Windows ####
There are files for _Visual Studio 2008_:
  * libarea/area.sln to make Python module;
  * libarea/pocket/pocket.sln is for making pocket.exe, see [wiki page](Pocket.md).

#### Under MacOSX, GNU/Linux, `*`BSD and probably a lot of POSIX systems ####
```
cd libarea
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## Others repositories ##
Please note that libarea have been pushed to GitHub but is not synced with this repository:

https://github.com/Heeks/libarea

GitHub repository provides a 2012-based version with additional users contributions, while this repository (at GoogleCode) is maintained by Dan Heeks with chosen patches.

## Contribute ##
You can contribute to libarea many ways:
  * Catch bugs and report them to issue tracker
  * Write patches and report them on associated issue or by email
  * Improve it: optimizations, build enhancements, documentation, etc. are welcome
  * Package it software for your preferred distributions