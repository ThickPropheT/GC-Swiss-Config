`swiss_rVVVV\DOL\swiss_rVVVV.dol` => `.\autoexec.dol`


Boot from Wii SD using Datel Action Replay

1. Ensure that the target SD card is 4GB or less and is in the FAT format.
	a. *NOTE* that some Wii SD adapters may only support SD and not SDHC or SDXC.
	
2. Copy `.\autoexec.dol` to the root of the target SD card.

3. Navigate to the `.\config` directory.

4. Navigate to the directory corresponding to the video output you'll be using.

5. Copy the `.\config\<video_output>\swiss\` directory to the root
	of the target SD card.
	a. **NOTE** that if the target SD card is being updated, you can preserve
		the list of recently opened applications. This list is saved in the
		`<SD_card>:\swiss\settings\recent.ini` file. To preserve the list, ensure
		that this file is not replaced/deleted when copying the `swiss` configuration
		directory in step 5.