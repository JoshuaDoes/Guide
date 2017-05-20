# RiiConnect24 Wii Guide
## Device: Wii
### Stage: Exploit - Twilight Hack

<i class="notice--danger">This guide is for the original Wii only. Do not use this on a Wii U!</i>

You will need:
- A Wii on 3.2-3.4, if you're on 4.0-4.2 use [Bannerbomb](Bannerbomb) instead, or if on 4.3, [Letterbomb](Letterbomb).
- An SD card of under 4GB (it cannot be an **SDHC**).
- [Twilight Princess' ZIP](404)
Steps:
Inside the zip file you will find versions of the hack for all three regions. You may copy all of them to your SD card, but you will need to choose the correct one to copy to your Wii based on your version of Zelda: Twilight Princess. USA users, additionally, need to determine the correct save slot to load once inside Twilight Princess. The easiest way to check your version is to compare the text string which is on the inner circle of the data surface with the ones below:

<table style="width: 700px; text-align:center; font-size:90%;">

<tbody><tr>
<th> Region </th>
<th> Inner circle text </th>
<th> File </th>
<th> Save slot
</th></tr>
<tr>
<td> Europe/Australia (EUR) </td>
<td> RVL-RZDP-0A-0 JPN </td>
<td> /private/wii/title/rzdp/data.bin </td>
<td> Twilight Hack
</td></tr>
<tr>
<td> Asia (JPN) </td>
<td> RVL-RZDJ-0A-0 JPN </td>
<td> /private/wii/title/rzdj/data.bin </td>
<td> Twilight Hack
</td></tr>
<tr>
<td> America (USA) </td>
<td> RVL-RZDE-0A-0 JPN </td>
<td> /private/wii/title/rzde/data.bin </td>
<td> TwilightHack0
</td></tr>
<tr>
<td> America (USA) </td>
<td> RVL-RZDE-0A-0 USA </td>
<td> /private/wii/title/rzde/data.bin </td>
<td> TwilightHack0
</td></tr>
<tr>
<td> America (USA) </td>
<td> RVL-RZDE-0A-2 USA </td>
<td> /private/wii/title/rzde/data.bin </td>
<td> TwilightHack2
</td></tr></tbody></table>

0. Ensure your SD card is formatted as FAT. By default SD cards are formatted as FAT, so if you're not sure you can skip this step.
- (Optional) If you have an existing Zelda save that you want to backup, do so before proceeding:
	1. Put your SD card in your Wii and turn it on.
	2. Go into Wii Options --> Data Management --> Save Data --> Wii
	3. Find your Zelda save, click on it, click "Copy", and click Yes
1. Put your SD card in your computer, and copy the "private" folder from the card to a safe place.
2. Copy the "private" directory from the Twilight Hack download to the root of your SD card.
3. Take your homebrew Wii executable (elf or dol file) and save it in the root directory of your SD card as "boot.elf" or "boot.dol" as appropriate.
4. Put your SD card in your Wii and turn it on.
5. Go into Wii Options --> Data Management --> Save Data --> Wii.
6. Find your Zelda save, click on it, click "Erase", and click Yes.
7. Open the SD card and select the "Twilight Hack" save that corresponds to your game region. Note: Some people are having problems with the Wii not "seeing" the save file on the SD card. If you are experiencing this, try setting the archive bit for the data.bin file - in Windows this can be either be done from the file's properties dialog (right click on it in Windows Explorer and check the box) or from the command line using "attrib +a <path to data.bin>". More info at #wiihelp on Efnet.
8. Click copy and then yes. Now exit out of the menu.
9. If you are using System Menu 3.4, you must immediately put the Twilight Hack to use. Turning off or running some other channel or game will have the System Menu delete the savegame again, and you'll have to start over.
10. Insert The Legend of Zelda: Twilight Princess game disc and run the game.
11. If you have the USA version of the game, load the "TwilightHack0" or "TwilightHack2" version of the game as appropriate (see above).
12. Otherwise, load the only "Twilight Hack" save game.
13. Once in the game, either walk backwards or talk to the man standing in front of you.
14. Follow the instructions listed on the screen.
15. Enjoy.

<div class="notice">Continue to <a href="HBC">Homebrew Channel Installation</a></div>