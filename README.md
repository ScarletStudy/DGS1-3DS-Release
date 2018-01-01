The Great Ace Attorney - English Translation Patch
============================

Please feel free to log typos and errors in the issues page.

**How to build the Game Update**

**>> IF YOU HAVE ALREADY MADE THE EPISODE 1 CIA, YOU CAN SKIP STEPS 1-5!**

**>> Just use** 000400000014AD00_v00.cia **and** dd_font.bin **from last time**

**>> You should still create a new folder, since the .EXE and .BAT files were updated**

Note: Make sure Luma3DS and FBI are updated to the latest version before starting.

1) Start GodMode9 (on Luma3DS/B9S - hold START while booting your 3DS and choose GodMode9)

2) Get a decrypted CIA of your game:
	* Physical Copy: [C:] GAMECART > select 000400000014AD00_v00.3ds > NCSD image options... > Build CIA from file
	* eShop Copy: [A:] SYSNAND SD > title > 00040000 > 0014AD00 > select the .tmd file > TMD file options... > Build CIA (standard)

3) Get the Dual Destinies font:	(you can skip this if you've previously dumped the font archive for our Demo or Episode 1 release)
	[A:] SYSNAND SD > title >
	
	* EUR Full: 00040000 > 000F1E00
	* EUR Demo: 00040002 > 000F1E01
	* USA Full: 00040000 > 000F1400
	* USA Demo: 00040002 > 000F1401
	
	\> content > 00000000.app > NCCH image options... > Mount image to drive > romfs > archive > UI_cmn_eng.arc > Copy to 0:/gm9/out

	Note: sd:/gm9/out/ may be sd:/gm9out/ for earlier versions of GodMode9

4) Extract the archive with the patcher and the IRIS file to a folder on your computer

5) Transfer the following files from your SD card to the folder you extracted the patcher and the IRIS file to:
	* sd:/gm9/out/000400000014AD00_v00.cia OR sd:/gm9/out/000400000014AD00.cia
	* sd:/gm9/out/UI_cmn_eng.arc


6) If applicable, rename the following:
    * Rename UI_cmn_eng.arc to dd_font.bin
    * Rename 000400000014AD00.cia to 000400000014AD00_v00.cia

7) Double-click PATCH_DGS.bat (it may be displayed as PATCH_DGS on your computer) to generate DGS_Episode2_Update.cia

8) Transfer DGS_Episode2_Update.cia to your SD card and install it with FBI

9) Run The Great Ace Attorney on your console - sorry, the Banner can not be translated via a Game Update, but the eManual is (partially) in English :)

New Years 2018, Scarlet Study
