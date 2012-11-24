sgh-t889-kernel
===============

SGH-T889 Kernel

This is the Stock Kernel for SGH-T889, otherwise known as the T-Mobile Galaxy Note 2.

The Goal of this project is to get an AOSP-based kernel for the T889 so that AOSP-based ROMs can run on this phone. 
This Kernel should preserve all of the S-Pen functionality.

===========================================
TO BUILD
Open Makefile with some editor.
Change the CROSS_COMPILE flag to a proper build toolchain for Android.

make clean
make arch=arm t0tmo_04_defconfig 
make (make -j<processor count> for faster build time)