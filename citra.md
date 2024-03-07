**Disclaimer:** The Japanese version of Rhythm Heaven Megamix (Rhythm Tengoku: The Best +) is not currently supported. Sorry for the bother!

### These instructions are to set up SpiceRack in Citra! Hardware instructions [here](index.md) 

1. Make sure you're using a somewhat recent version of Citra (nightly 1819 onwards)
    - Note: Since the official Citra repository has been taken down, you can use [PabloMK7's fork](https://github.com/PabloMK7/citra/releases/latest) for the time being.
1. Download Saltwater [(here)](https://github.com/patataofcourse/Saltwater/releases/latest) and Barista [(here)](https://github.com/patataofcourse/Barista/releases/latest)
1. Install Megamix into Citra **as a CIA**
    - This part is very important - otherwise, Barista won't be able to boot Megamix
1. Install the Barista .cia into Citra or place the Barista .3dsx in your ROMs folder
1. Open your Citra folder (File > Open Citra folder)
1. Place the Saltwater.3gx file inside your Citra folder, in `sdmc/spicerack/bin`
1. Create, if it doesn't exist, a `sdmc/luma/plugins` folder in your Citra folder. Don't place anything inside
1. Place any .btk (Tickflow) files for mods you want to play in `sdmc/spicerack/mods`
1. Place your mods' RomFS (model, cellanim, layout, effect, etc.) folders in `load/mods/[YOUR ID GOES HERE]/romfs`, where the ID is:
    - 000400000018a400 - Rhythm Heaven Megamix (US)
    - 000400000018a500 - Rhythm Paradise Megamix (EU)
    - 000400000018a600 - Rhythm Sesang: The Best + (KR)
    - To run mods in non-US versions, you'll probably need to rename folders from "UScellanim", "USlayout", etc, to "EUENlayout", "KRlayout", etc.
        - Keep in mind that this will likely set the language of some aspects of your game to English! For proper non-English support, you'll need to use mods that are properly localized.
        - The full list of languages and region codes is: `US`, `JP`, `KR`, `EU`, `EUEN`, `EUSP`, `EUIT`, `EUFR`, `EUGE`
1. Launch Barista
1. Set up your mods inside the app and launch your preferred version of Megamix