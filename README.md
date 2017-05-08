docker-xc16
=============

[MPLABX](https://www.microchip.com/mplab/compilers): MPLAB XC16 Cross Compiler, Docker Container

Info
----

This Docker Container is intended to capture a general method that developers can work with a similar
tool chain on demand.

docker build -t xc16  docker build github.com/kamacurus/docker-xc16

example run cmd
docker run -i -t --privileged -v ~/Projects/proj:/home/user/proj:Z -w /home/user/proj xc16 /bin/bash

ToDo
----
Uses Legacy Peripheral Library - Howto use new periperal lib from cmd line?
Fix PicKit3 USB permissions 
