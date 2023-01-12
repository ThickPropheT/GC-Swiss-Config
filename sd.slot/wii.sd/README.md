Wii SD / SD Gecko
=================

Executable Source:
-----------------

	swiss_rVVVV/DOL/swiss_rVVVV.dol => ./autoexec.dol


Requirements:
------------

- 1x Wii SD (a.k.a. SD Gecko) inserted into memory card slot B.

- 1x 4GB or less SD card formatted to FAT **for booting via Action Replay**.
	- **NOTE** that some Wii SD/SD Gecko adapters may only support
		SD and not SDHC or SDXC.

**OR**

- 1x SD card up to 2TB formatted to FAT or FAT32 **for general storage or Swiss Configuration**.

	- **NOTE** that some Wii SD/SD Gecko adapters may only support
		SD and not SDHC or SDXC.


Boot via Datel Action Replay:
----------------------------

1. Copy `./autoexec.dol` to the root of the SD card.
	1. **NOTE** that `autoexec.dol` can be hidden from view
		within the Swiss menu (see the root `README.md`).

1. Follow steps in Configure Swiss section below.

1. Insert the SD card into the Wii SD adapter in memory card slot B.

1. Insert the Action Replay disc and turn on the console.


Configure Swiss:
---------------

1. Navigate to the `./config` directory.

1. Navigate to the directory corresponding to the video output you will be using.

1. Copy the `./config/<video_output>/swiss/` directory to the root
	of the SD card.
	1. **NOTE** that if the SD card is being updated, you can preserve
		the list of recently opened applications. This list is saved in the
		`<SD_card>:/swiss/settings/recent.ini` file. To preserve the list, ensure
		that this file is not replaced/deleted when copying the `swiss` configuration
		directory in this step.
