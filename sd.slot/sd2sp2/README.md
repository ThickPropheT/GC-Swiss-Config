SD2SP2
======

Executable Source:
-----------------

	It is not currently possible to boot Swiss from SD2SP2.


Requirements:
------------

- 1x SD2SP2 adapter inserted into Serial Port 2 on the bottom of the console.

- 1x SD card formatted to FAT32.


Configure Swiss:
---------------

1. Navigate to the `./config` directory.

1. Navigate to the directory corresponding to the video output you will be using.

1. Copy the `./config/<video_output>/swiss/` directory to the root
	of the SD card.
	a. **NOTE** that if the SD card is being updated, you can preserve
		the list of recently opened applications. This list is saved in the
		`<SD_card>:/swiss/settings/recent.ini` file. To preserve the list, ensure
		that this file is not replaced/deleted when copying the `swiss` configuration
		directory in this step.
