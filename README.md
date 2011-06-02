Description
---
rendermap is a tool used to render PNG images of Minecraft ingame
map data at various scales (TODO!)

Dependencies:
---
   - [libcppnbt](http://github.com/FliPPeh/cppNBT)
   - [libz](http://zlib.org)
   - [libpng](http://www.libpng.org/)

Building
---
Assuming libcppnbt is in the current working directory (either as static or
shared library or symlinked), libz and libpng either installed globally or
similar to libcppnbt, running 'make' will do the job. Otherwise minor
modification to the Makefile will have to be done to include the correct
search paths.

Running 'make' will create an executable file called "rendermap".

Usage Example
---
    $ rendermap Map_0.dat
    # This will create the image "Map_0.dat.png" in the current directory

Output example
---
![Example](http://i.imgur.com/W061Y.png)
