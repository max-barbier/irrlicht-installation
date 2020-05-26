# irrlicht-installation
A simple tutorial to install irrlicht

If you are on Linux, in particulary on Fedora 28/29/30 or later, just type the command "sudo dnf install irrlicht-devel".

For the users on Ubuntu for exemple, create a directory in your /usr/include path which you have to name "irrlicht" and copy the 
integrality of the directory "include" in it.

Then, copy all the .so in your /usr/lib path.

If you only use a makefile, the flags "-lIrrlicht -lXxf86vm -lXrandr -lGL -lGLU -lXi -lX11" will be necessary.

There is a test/ directory, when you have done all of that, go to this dir and do "make && ./irrlicht". If a window appears, press "s" and
you  will see an animated model.
