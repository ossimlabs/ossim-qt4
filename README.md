# ossim-qt4
Qt4-based GUIs for OSSIM. 

This repository provides two applications: imagelinker and iview. These have been somewhat superceded by the Qt5-based ossim-geocell (in [ossim-gui](https://github.com/ossimlabs/ossim-gui) repo) but some liked the old GUIs better.

h1. Building

The build is handled by the core OSSIM cmake system. There is an environment variable, BUILD_OSSIM_QT4, defaulted to "OFF" in the ossim-cmake-build scripts. To build the Qt4 applications, set BUILD_OSSIM_QT4=ON in your shell before running the [ossim build script](https://github.com/ossimlabs/ossim/scripts/build.sh).

h1. `imagelinker`

This is a highly-capable image viewer that provide resampling to various projections (i.e., orthorectification), as well as a large collection of image processing filters and analysis tools. If you want to do things like mosaicking, tonal balancing, reprojections, and swipe, use this app.

h1. `iview`

This is a quick and dirty viewer that displays the raw pixel data with no reprojections or resampling. It is good for checking the functionality of a particular image format handler.

