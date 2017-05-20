# RiiConnect24 Wii Guide
## Device: Wii U
### Stage: Exploit - WUPHax
### This guide is intended for use for stock to vWii hacks, *without any permanent Wii U exploits.* If you have these, you just need to load the WUPHax ELF via HBL.

<i class="notice--danger">This guide is for the Wii U only. Do not use this on a Wii!</i>

## Requirements
- A Wii U, on v5.5.1 with an active Internet connection.
- A Wiimote.
- An SD card that's at least 2GB in FAT32, and is not named "WIIU" or "WII U". If your SD is over 32GB, Windows may want to format it as exFAT; don't let it, use [GUIFormat](http://homebrew.ovh/guiformat.exe) to fix this.
- [WUPHax](https://github.com/FIX94/wuphax/releases)
- [HackMii Installer](https://bootmii.org/download/) - you will only need the boot.elf in the ZIP.
## NOTICE
It is suggested to use a DNS to prevent Wii U updates past 5.5.1, but since Nintendo EoL'd Wii U it's unlikely you'll need it. Nevertheless, I should still give it you:
Primary : 104.236.072.203 (TubeHax DNS)

Secondary : 107.211.140.065 (Chncdcksn hax)

## Guide
0. Insert the SD into your PC, and put the boot.elf from the HackMii installer into your SD Root. Then, put your SD back into your Wii U.
1. Go to loadiine.ovh in your Wii U (Bookmark this page!), and click on the scrolling bar; select "Homebrew AppStore Installer". You will be redirected to Wiiubru's launching pad for HASI. Just click on "Let's go" and let the magic do its trick :3
If it freezes, reboot; the MP4 exploit is not the most stable&tm;
2. Once you're in the HB AppStore, install HBL v1.2, and press the HOME button to exit to HOME menu.
3. Put your SD into your PC, and download the latest WUPHax ELF. Place this in SD:/wiiu/apps/wuphax (you will need to make the wuphax folder) and do not rename it!
4. Put your SD back into the 'U and then go back to loadiine.ovh - this time, load the Homebrew Launcher.
5. Click on wuphax, and load it. Then, press A to install - it will look like it has frozen, but it has not. Do not worry.
6. Once done, go to your vWii, and launch the Mii Channel.

Continue to [Homebrew Channel Installation](HBC)
