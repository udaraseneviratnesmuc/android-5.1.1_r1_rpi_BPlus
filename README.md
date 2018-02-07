# android-5.1.1_r1_rpi_BPlus
Compiled android-5.1.1_r1 for Raspberry Pi B+

This repository includes the compiled sources of android-5.1.1(Lollipop) under ARM processor architecture which supports the Raspberry PI model B+

Ref : https://raspberrypi.stackexchange.com/questions/44005/how-do-i-install-the-android-debug-bridge-adb-on-a-raspberry-pi

Anyone may edit the adb-compile-env-setup.sh file and change the branch of google android repository and compile their interested android version.
before running the adb-compile-env-setup.sh create adb-dev directory and place Makefile inside it.

If following errors occured you may try the below solutions:
	1) Makefile: : *** missing separator. Stop. :- Check for the leading spaces of the command lines in the Makefile and replace them with TABS
	2) make: *** No rule to make target 'adb.o', needed by 'adb'. Stop :- make sure that Makefile is inside the system/core/adb/ (This directory structure should be created after running the adb-compile-env-setup.sh)


################## Special Thanks ###################
Eugen(https://raspberrypi.stackexchange.com/users/70770/eugen) who answered for https://raspberrypi.stackexchange.com/questions/44005/how-do-i-install-the-android-debug-bridge-adb-on-a-raspberry-pi 
