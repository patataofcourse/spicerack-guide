**Disclaimer:** The Japanese version of Rhythm Heaven Megamix (Rhythm Tengoku: The Best +) is not currently supported. Sorry for the bother!

You can skip Step 2 if you've recently played CTGP-7, since its launcher installs the required fork of Luma3DS.

1. Download Saltwater <!--[(here)]()--> and Barista <!--[(here)]()-->
1. Download the latest version of the Luma3DS plugin loader fork, which you can find [over here](https://github.com/PabloMK7/Luma3DS_3GX/releases/latest)
    - If you had any settings on in the Luma3DS menu, turn them on again! They'll have reset after changing your Luma
1. Install your Barista .cia or place the .3dsx in your `/3ds` folder
1. Place the Saltwater.3gx file in a folder in your SD named `/spicerack/bin`
1. Create, if it doesn't exist, a `/luma/plugins` folder in your SD. Don't place anything inside
1. Place any .btk (Tickflow) files for mods you want to play in `/spicerack/mods`
1. Place your mods' RomFS (model, cellanim, layout, effect, etc.) folders in `/luma/titles/[YOUR ID GOES HERE]/romfs`, where the ID is:
    - 000400000018a400 - Rhythm Heaven Megamix (US)
    - 000400000018a500 - Rhythm Paradise Megamix (EU)
    - 000400000018a600 - Rhythm Sesang: The Best + (KR)
    - **Keep in mind that to load RomFS assets you'll need to enable game patching enabled in Luma3DS** - hold Select while booting to enter the Luma config menu
    - To run mods in non-US versions, you'll probably need to rename folders from "UScellanim", "USlayout", etc, to "EUENlayout", "KRlayout", etc.
        - Keep in mind that this will likely set the language of some aspects of your game to English! For proper non-English support, you'll need to use mods that are properly localized.
        - The full list of languages and region codes is: `US`, `JP`, `KR`, `EU`, `EUEN`, `EUSP`, `EUIT`, `EUFR`, `EUGE`
1. Boot Barista through the Homebrew Launcher or your Home Menu, depending on method of installation
1. Follow the instructions inside the app