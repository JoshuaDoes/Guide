# RiiConnect24 Wii Guide
## Device: Wii
### Stage: Exploit - Bannerbomb

<i class="notice--danger">This guide is for the original Wii only. Do not use this on a Wii U!</i>
 
You will need:
- A Wii on system versions 4.0-4.2
   If you're on 4.3, use [Letterbomb](Letterbomb) instead
- An SD card with at least 128 MB of free space
- [Bannerbomb](/assets/files/abd6a_v200.zip)
- [HackMii Installer](https://bootmii.org/download) - only the ELF is needed!

Steps:
- If your SD card has a private directory with saved channels, rename it temporarily (e.g. to "privateold")
   Having other saved channels on the same card will screw it up. (You can skip this step if you don't have any channels on the SD card. Saves will not interrupt this process.)
 
1.  Copy the `private` folder from `abd6a_v200.zip` to the root of your SD card.
2.  Extract the `boot.elf` file from the HackMii installer to the root of your SD card.
3.  Insert your SD card into your Wii and power it on.
4.  Go to the SD Card Menu on the main System Menu screen.
5.  A message should appear asking to "load boot.dol/.elf". If it freezes or does not appear, download the next .zip file from the Bannerbomb website and start over.
![PLACEHOLDER](http://placehold.it/350x150?text=BannerBomb+Load+Screen)
6.  The homebrew on your SD card will load. Enjoy!

<div class="notice">Continue to <a href="HBC">Homebrew Channel Installation</a></div>
