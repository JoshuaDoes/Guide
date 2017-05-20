# RiiConnect24 Wii Guide
## Device: Wii
### Stage: Exploit - Bannerbomb

<i class="notice--danger">This guide is for the original Wii only. Do not use this on a Wii U!</i>
 
You will need:
- A Wii on 4.0-4.2; if you're on 4.3, use [Letterbomb](Letterbomb) instead.
- An SD card of any size.
- [Bannerbomb Files](/assets/files/abd6a_v200.zip)
- [HackMii Installer](https://bootmii.org/download) - only the ELF is needed!

Steps:
- If your SD card has a private directory with saved channels, rename it temporarily, e.g. to "privateold". Having other saved channels on the same card will screw it up. (You can skip this step if you don't have any channels on the SD card. Saves are fine.)
 
1. Copy the Bannerbomb "private" folder to the root of your SD card.
2.  Extract the boot.elf from HackMii installer to the root of your SD card.
3.  Put your SD card in your Wii and turn it on.
4.  Go to the SD Card Menu on the main System Menu screen
5. A message should appear asking to "load boot.dol/.elf". If it freezes or does not appear, download the next .zip file from the Bannerbomb website and start over.
6.  The homebrew on your SD card will load. Enjoy!

Continue to [Homebrew Channel Installation](HBC)
