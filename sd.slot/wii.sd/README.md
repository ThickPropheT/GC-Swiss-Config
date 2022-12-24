Wii SD / SD Gecko
=================

Executable Source:
-----------------

	`swiss_rVVVV/DOL/swiss_rVVVV.dol` => `./autoexec.dol`


Requirements:
------------

- 1x Wii SD (a.k.a. SD Gecko) inserted into memory card slot B.

- 1x 4GB SD card formatted to FAT.
	- *NOTE* that some Wii SD/SD Gecko adapters may only support
		SD and not SDHC or SDXC.


Boot via Datel Action Replay:
----------------------------

1. Copy `./autoexec.dol` to the root of the SD card.

2. Follow steps in Configure Swiss section below.

3. Insert the SD card into the Wii SD adapter in memory card slot B.

4. Insert the Action Replay disc and turn on the console.


Configure Swiss:
---------------

1. Navigate to the `./config` directory.

2. Navigate to the directory corresponding to the video output you will be using.

3. Copy the `./config/<video_output>/swiss/` directory to the root
	of the SD card.
	a. **NOTE** that if the SD card is being updated, you can preserve
		the list of recently opened applications. This list is saved in the
		`<SD_card>:/swiss/settings/recent.ini` file. To preserve the list, ensure
		that this file is not replaced/deleted when copying the `swiss` configuration
		directory in this step.