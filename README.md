#Ancient Religions

> An ancient religions mod for CK2

This mod aims at recreating dead or pseudo-dead religions in vanilla Crusader Kings 2.
If you want to include it in any publicly released mod, you need permission from the authors.

###Features

For more info, check the [Ancient Religions page on ckiiwiki](http://www.ckiiwiki.com/Ancient_Religions).

Current Religions:
 - Hellenic paganism
 - Celtic Druidism
 - Egyptian paganism
 
Other plans include Basque, Guanche and Mesopotamian paganism, and further plans include the Cult of Cthulhu.

###Players

Installation steps:

1. __Important__: Delete your Ancient Religions folder, if you have one.
2. Extract the AncientReligions folder and the AncientReligions.mod file to your mod-folder (~\Documents\Paradox Interactive\Crusader Kings II\mod)
3. Enable the mod when launching the game
4. Have fun !

If you encounter any issues or are wondering about anything you can ask in the [Ancient Religions thread on the Paradox Forums](http://forum.paradoxplaza.com/forum/showthread.php?829413-Ancient-Religions-Reborn!).
Do note that you have to register your copy of Crusader Kings II in order to view the thread.

###Developers & Testers

To run the mod from a Git local repository:
- Clone the repository to Git default location (for instance C:\Users\username\git\)
- Run [create_symbolic_links.bat](create_symbolic_links.bat) to create symbolic links from CK2 mod folder to the actual folders in your Git working directory
- Copy over the [AncientReligions.mod](AncientReligions.mod) file from Git folder to CKII mod folder (you will need to re-copy them occasionally when they change in Git)

For improved maintainability and compatibility with other mods, the following conventions are used:
- Mod files are prefixed with ACR_ (except for modified vanilla files).
- Mod gfx assets are stored under an ACR sub-folder (except for modified vanilla gfx).
- Changes are listed in a [Changelog](ACR_Changelog.txt).
- The [Validator](http://forum.paradoxplaza.com/forum/showthread.php?597480-The-Validator-Find-errors-quickly-and-with-minimal-pain!) is used to detect bugs, and is configured via [ValidatorSettings.txt](AncientReligions/ValidatorSettings.txt).
