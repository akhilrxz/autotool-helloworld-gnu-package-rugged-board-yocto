# autotool-helloworld-gnu-package-rugged-board-yocto

*********Write a GNU helloworld autotool recipe to add GNU helloword package in phy-image and then build & test**********

i created a new layer for this project 
     by command :
              bitbake-layers create-layer ../sources/layername
              bitbake-layers add-layer ../sources/layername

2) created a folde named auto-hello and add sub folder inside called files
3) then i created a auto-hello recipie
4) then i inside files i added a auto-hello.tar files which gnu files ,makefile,am,makefile.in,configure.ac and user program.c file
5) then i runn comands bitbake auto-hello created a image
