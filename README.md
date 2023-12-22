# fortran

## f03gl Makefiles 

f03gl is Fortran 2003 interface to OpenGL. https://www-stone.ch.cam.ac.uk/pub/f03gl/index.xhtml. 

f03gl folder contains Makefiles for major platforms.
- Makefile.mac
  - Download and install XQuartz - X11 packages for Mac. https://www.xquartz.org/    
  - Download f03gl zip or tarball file. Uncompress it. 
  - Copy Makefile.mac to the root folder of f03gl.
  - Run "make -f Makefile.mac".
  - Tested on MacOS 13.5.2 M1. 
- Makefile.linux
  - Download f03gl zip or tarball file. Uncompress it.
  - Copy Makefile.linux to the root folder of f03gl.
  - Run "make -f Makefile.linux".
  - Tested on Ubutun 22.04.3 ARM chip. 
- Makefile.win
  - In progress.

