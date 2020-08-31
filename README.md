# 3ds.hacks.guide Setup Script
A GodMode9 script for automating some of the setup on 3ds.hacks.guide.

## Instructions
Copy the file "3ds.hacks.guide_Setup_Script.gm9" to "\gm9\scripts" on the SD card. Then open GodMode9, press the HOME button, choose "Scripts...", and choose "3ds.hacks.guide_Setup_Script". The script will let you know what to do from there.

## Features
The script performs the following actions:
* Verify Files
	* Verfies that all of the files the script needs are present.
* Install CIAs
	* Installs all CIAs in the SD card's "cias" directory.
* Setup Luma3DS to CTRNAND
	* Sets up Luma3DS in the NAND so the 3DS can boot without an SD card.
* Clean Up Setup Files
	* Cleans up files from the exploit the user performed, along with some other setup files.
* Backup Essential Files
	* Backup essential files to "\gm9\out" on the SD card.

The script features the following:
* Noob-proof
	* Does a lot of the work for the user, so there's less room for mistakes.
* Future-proof
	* The script is set up so that it should run without issues in the future, in case it isn't updated for newer exploits, apps, etc. (which it will be anyway!).
* User-interface
	* The script will show its current progress on the top screen, so you'll know what the script is currently working on.
