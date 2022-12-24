GC Loader
=========

Executable Source:
-----------------

	`swiss_rVVVV/GCLoader/boot.iso` => `./boot.iso`


Requirements:
------------

- 1x GC Loader ODE installed in console.

- 1x SD card formatted to FAT32.

- 1x Secondary SD card used for configuring Swiss (see Configure Swiss section below).


Boot from GC Loader:
-------------------

1. Copy `./boot.iso` to the root of the GC Loader SD card.

2. Follow steps in Configure Swiss section below.

3. Insert the GC Loader SD card into the GC Loader and
	the Secondary SD card into its respective card slot.

4. Turn on the console.


Configure Swiss:
---------------

At present, Swiss is not capable of loading its configuration from
the GC Loader SD card. In order to configure Swiss, a secondary SD
card is required.

1. Navigate to the `/sd.slot/` directory.

2. Navigate to the directory corresponding to the secondary SD card
	slot you will be using.

3. Open the chosen directory's `README.txt` file and follow the steps
	in the Configure Swiss section.