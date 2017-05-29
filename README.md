# Ancient Religions

> An ancient religions mod for CK2

This mod aims at recreating dead religions in vanilla Crusader Kings 2.
If you want to include it in any publicly released mod, you need permission from the authors.
You also need to ask the authors noted in the Disclaimers section about their code.

## Features

For more info, check the [Ancient Religions page on ckiiwiki](http://www.ckiiwiki.com/Ancient_Religions).

Current Religions:
 - Hellenism
   - Titan Cult
   - Prometheanism
 - Celtic Paganism
 - Kemetism (Egyptian pagan)
   - Atenism
 
 There are currently no plans to add more religions, and we are not taking suggestions.

## Players

Installation steps:

1. __Important__: Delete your Ancient Religions folder, if you have one.
2. Extract the AncientReligions folder and the AncientReligions.mod file to your mod-folder (~\Documents\Paradox Interactive\Crusader Kings II\mod)
3. Enable the mod when launching the game
4. Have fun !

If you encounter any issues or are wondering about anything you can ask in the [Ancient Religions thread on the Paradox Forums](https://forum.paradoxplaza.com/forum/index.php?threads/ancient-religions-reborn.829413/).
Do note that you have to register your copy of Crusader Kings II in order to view the thread.

## Developers & Testers

To run the mod from a Git local repository:
- Clone the repository to Git default location (for instance C:\Users\username\git\)
- Run [create_symbolic_links.bat](create_symbolic_links.bat) to create symbolic links from CK2 mod folder to the actual folders in your Git working directory
- Copy over the [AncientReligions.mod](AncientReligions.mod) file from Git folder to CKII mod folder (you will need to re-copy them occasionally when they change in Git)

For improved maintainability and compatibility with other mods, the following conventions are used:
- Mod files are prefixed with ACR_ (except for modified vanilla files).
- Mod gfx assets are stored under an ACR sub-folder (except for modified vanilla gfx).
- Changes are listed in a [Changelog](ACR_Changelog.txt).
- The [Validator](http://forum.paradoxplaza.com/forum/showthread.php?597480-The-Validator-Find-errors-quickly-and-with-minimal-pain!) is used to detect bugs, and is configured via [ValidatorSettings.txt](AncientReligions/ValidatorSettings.txt).

## Credits

### Modders
- Superskierpat: Original author of the mod and contributor of tens of thousands of lines of code.
- Jonseverinsson: Early contributor and responsible for most of the Romano-centric content.
- Rylock, Schwarherz, et. al.: The CK2+ team provided the foundation of our Kemetic implementation with Pyramids, Luxor, and the Anubis and Horus Guards.
- AnaxXiphos: Contributed a large number of icons and CoAs.
- cybrxkhan: Advice, moral support, and some kickass event chains.
- jbelig: Beautiful CoAs for our religions and about half the flags for our custom titles.
- Romulien: Tons of coding help, including our implementation of the Cardinal elections for the Archdruid.
- theStormWeaver/xirsoi: Current mod maintainer and developer.

### Images
- "The Favorite Poet"; Sir Lawrence Alma-Tadema

## Disclaimers

### Code from Third Parties

The following code and assets were included in Ancient Religions Reborn from other mods, or were included with explicit permission from the creator. To use these you must seek the permission of the authors.

- Most of our trait, decision, and religion icons; by AnaxXiphos of the Historical Immersion Project.
- Nile River Floods event chain and modifiers; by cybrxkhan.
- Horus Guard, Anubis Guard, and Paragon Xroj Flags; CK2+ Team.
- Celtic, Hellenic, and Kemetic CoAs and Frames; jbelig.
- Flags for Burning Blades, Meryatenate, Sicles, Men of Steel, and First Academy; jbelig.