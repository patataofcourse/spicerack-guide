**Disclaimer:** The Japanese version of Rhythm Heaven Megamix (Rhythm Tengoku: The Best +) is not currently supported. Sorry for the bother!

### These instructions are to set up SpiceRack in a 3DS console! Citra instructions [here](citra.md) 

You can skip Step 2 if you have a Luma version 13.0 or higher.

If your 3DS doesn't have CFW at all, check out the amazing guide by the folks at [3ds.hacks.guide](https://3ds.hacks.guide) to know how to mod your console!

1. Download Saltwater <!--[(here)]()--> and Barista <!--[(here)]()-->
1. Download the latest version of Luma3DS, which you can find [over here](https://github.com/LumaTeam/Luma3DS/releases/latest)
    - If you had any settings on in the Luma3DS menu, turn them on again! They'll most likely have reset after changing your Luma version.
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
1. Set up your mods inside the app and launch your preferred version of Megamix