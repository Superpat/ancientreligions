2019-01-04 v0.43.0 "Sequana"
============================

> Sequana is a Celtic river goddess popular in Gaul. She was the patron of the river that bore her name, now known as the Seine. A shrine near the source of the river holds a Roman era statue of the goddess, revealing her popularity even after Caesar's conquest. Hundreds of votive offerings to Sequana have been found at the bottom of the river near the shrine.

General:

- Fixed many, many, *many* bugs.

Celtic:

- Living Legend bloodline event has been fixed. Those of you with many duplicate bloodlines can keep them as compensation for your troubles.
- Added new Torques as Celtic crown jewels. These will replace crowns (but take the neck slot), and Celts will get the swords Christians and Norse get.
- The Celtic Warrior Lodge, "The Band of Camulos", has been added. Camulos is a Briton war and storm god.
  - Special leader trait is "Raider".
    - +50% Imprison Enemy Commander
    - +20% in Hill Terrain
    - +20% Morale Offence
  
Britannic:

- Missing localisation was added for events involving a vassalized Arch-Dryad and having free investiture after the Arch-Dryad has been created.
- Fixes bug with events where the Arch-Dryad gives artifacts to favored rulers.
- Britannic characters will also use the new torques as crown jewels.
- The Britannic Warrior Lodge, "The Champions of Andraste", has been added. Andraste is the Sanctaidd ("Archangel") of Victory.
  - Special leader trait is "Lancer".
    - +20% Plains and Farmland Terrains.
    - +20% to Light and Heavy Cavalry.

Hellenic:

- Bug fixes and new events for the Artemis event chain from (formerly!) retired CK2 modder cybrxkhan. Thanks!
- Removed custom Roman cultural buildings in favor of the ones provided by vanilla.

Promethean:

- Skeptic and Epicurean monastic orders have been added.
  - They're mostly copies of the Stoics, with small tweaks here and there.
  - Most anyone who has access to the Stoics will also have access to these societies.
  - The relevant neoplatonist traits have been factored into all three societies.
- All three Neoplatonist societies favor Learning, but each also favors another attribute.
  - The 0.5 x Learning bonus has been replaced with a 0.3 x Learning + 0.2 x the other attribute
  - Stoics favor and grant Diplomacy.
  - Skeptics favor and grant Intrigue.
  - Epicureans favor and grant Stewardship.
- Removed Promethean from Lets. Get. PAGAN!, as it's now a heresy of a reformed religion, which makes things buggy.
- Restored The Coven as a satanist society for Prometheans.

Titan Cult:

- The Titan Warrior Lodge, "The Warriors of Perses", has been added. Perses is the Titan of Devastation.
  - Special leader trait is "Ravager".
    - +20% in Mountain Terrain.
    - +20% for Light and Heavy Infantry.
- Made The Coven the satanist society of the Titan Cult.

Egyptian:

- The Egyptian/Atenic Warrior Lodge, "The Champions of the Sun", has been added.
  - Special leader trait is "Sandstrider".
    - +20% in Desert and Plains Terrains.
    - +10% Speed
    - +10% Retreat
    - +20% Siege

Atenic:

- Removed Atenic from Lets. Get. PAGAN!, as it's now a heresy of a reformed religion, which makes things buggy.

2018-12-18 v0.42.4 "Tasgetius"
============================

> Tasgetius was a king of the Gaulish Carnutes tribe (carnutes meaning "the horned ones", possibly a connection to Cernunnos). Tasgetius was appointed to kingship by Julius Caeser himself. The puppet king was assassinated in three years.

Celtic:
  - Living Legend bloodline event will only fire once.
    - Also made it so you can still become a Living Legend even if you already have the bloodline. You'll only get the trait in that case.
  - Britannic's can get their crusader trait (Morrigan) again.

Egyptian:
  - Fixed bug where the "arriving in the GHW target lands" event repeats infinitely for Kemetics, reapplying the "Might Bull of Montu" trait each time.


2018-12-15 v0.42.3 "Carnutes"
-------------------------
> The Carnutes were a tribe of Celts in Gaul that contemporary scholars believed to represent the economic and religious heartland of the Celtic peoples. Julius Ceasar established the Carnutes as a protectorate and selected one of their number as king. Less than five years later this king was assassinated and all the Romans in Carnute territory were slaughtered. This rebellion is what sparked the full-scale revolt led by Vercingetorix. Their capitol eventually became the city of Chartres.

General:
  - Fixed gender law reverting to Agnatic on title holder change even with Enatic Clans.
  - "Random with Heresies" no longer spawns Aztec religion but will spawn Hellenic.
  - Gaulish and Neo-Coptic will only spawn in Random and Full Random worlds.

Celtic:
  - Creating Britannia while Celtic or Druidic and either Breton, Welsh, or Pictish will now grant the Blood of Arthur Pendragon bloodline, in addition to the Pendragon nickname.
  - Druidic and Britannic can use the Holy War CB again.
  - Celtic Holy Orders convert to Druidic on reformation.

Hellenic:
  - Fixed typo for Hellenic holy scripture.
  - Sacred Band and Hellenic Legion Holy Orders convert to reformed on reformation.
  - Becoming the Chosen of Artemis now grants a bloodline.

Egyptian:
  - Anubis and Horus Guard Holy Orders will convert to Kemetic on reformation.
  - Coptic has been renamed to Neo-Coptic, to distinguish it from the vanilla one.
  - Kemetic can use the Holy War CB again.
  - Fixed issue where Egyptian/Kemetic rulers could get artifacts irrelevant to them.
  
Atenic:
  - The Meryatenate no longer causes you to have the wrong government.
  - Atenic can use the Holy War CB again.
  - Fixed issue where Atenic rulers could get artifacts irrelevant to them.


2018-12-10 v0.42.2 "Herne"
-------------------------
> Herne the Hunter is a ghost story told by Shakespeare about a phantom that haunted the woods of Windsor. According to the legend, he has the antlers of a stag and rides through the forest rattling his chains to keep people away from his oak tree.

General:
  - Added new random world religion icons.
    - They're a Boar and a Bell; regular, reformed, and reformed heresy versions.
    - Had to in order to make the icons appear correctly in a random world.
  - Added a new shattered world option for religions, Random with Heresies.
    - Sits between Random and Full Random, allows heresies but bars reformed religions from spawning (including the heresies of reformed religions).
    - e.g. Fraticelli will spawn, but Britannic Pagan will not.

Celtic:
  - Organize Red Dragon Knights and Organize Sons of Gwydion now compatible with a Temporal Head.
  - AI only decisions assign_bard and assign_druid should no longer be visible.
  - When becoming a Living Legend, you are awarded a new bloodline instead of the trait.
    - The trait still exists in the files for compatibility.

Hellenic:
  - Fixed bad references to the Pontifex Maximus.
    - This fixes the Organize Sacred Band decision.
  - For fun, the Titan Cult is now a heresy of unreformed Hellenic (as opposed to reformed).
    - Titan Cult will become a heresy of the reformed faith on reformation though.

Egyptian:
  - Egyptian Pagan is now simply called "Egyptian" to match the other pagan religions.

Aten:
  - Atenism no longer requires Iqta government.
    - Both Feudal and Tribal Atenic rulers will have to deal with decadence.


2018-12-08 v0.42.1 "Manannan"
-------------------------
> Manannan "mac Lir" (son of the sea), is the god of the sea. One of the gods said to rule the otherworld, he is said to ferry souls to the afterlife. He is ascribed several powerful artifacts and magical abilities, including the gift of prophecy. He also plays small but important roles in several legends, often as the foster father of the hero, such as Lugh of the Long Spear.

General:
  - CK2 3.1 compatability
  - Fixes crash bug when doing anything involving the Commander minor title.
  - Fixes bug with Flamen Dialis minor title.
  - Fixes messed up flags.

Celtic:
  - Reformation will now modify god names if Dogmatic, Agnatic Clans, or Enatic Clans have been chosen.
  - Added Rhiannon and Sequana as goddesses and removed The Horned One and Angus.
    - The localisation keys are still there, so this won't break anything if you're The Sword of Angus or something.

Egyptian:
  - Accounted for Kemetic (reformed egyptian) in several places that were missed in the Cernunnos update.
  - Reformation will now modify god names if Dogmatic, Agnatic Clans, or Enatic Clans have been chosen.
  

2018-12-02 v0.42.0 "Cernunnos"
-------------------------
> Cernunnos is the Horned God, a deity of fertility, life, animals, and the underworld. Worshipped throughout Gaul and Celtiberia, Cernunnos was one of a small number of almost universally worshipped Celtic gods. His most famous appearances are on the Pillar of the Boatman, a carved column found in a Roman temple in Paris; and the Gundestrup Cauldron, a fantastic example of iron age silverwork found in a peat bog near Gundestrup, Denmark.

General:
  - CK2 3.0 compatability
  - Crusades and Jihads can now be called in a Paganified world if the player is a member of the religion.
    - For example, the Pope can call Crusades if there is a Catholic player.
  - Holy Orders are no longer vassalizable.
  - Most Holy Orders now have the standard mechanics from vanilla (making donations/loans, building castles, etc.)
    - Note: I've written a somewhat experimental new mechanism to implement these features, so they won't be exactly as vanilla. 
    - The decisions are now targeted, so right-click the grandmaster of the order to use them.
  - Added more possible immortal mystics, some of which will have ancient religions and/or cultures.
    - Nestor the Wise, Greek Hellenic Pagan, master of diplomacy
    - (random) the Spartan, Greek Hellenic Pagan, master of war.
    - (random) the Fearless, Gaulish Celtic Pagan, master of war.
    - Cleopatra the Alchemist, Coptic Kemetic Pagan, master spy.
    - Seneca the Younger, Roman Promethean Pagan, master scholar.
    - Lucan the Younger, Roman Hellenic Pagan, master scholar.

Celtic:
  - Fixes bug where the Unfit King Beta game rule was being ignored.
  - Gaulish Queens will henceforth be known as Riga, and Empresses as Vercingetoriga.
  - There are now Celtic artifacts to be found when searching for artifacts (Monks & Mystics feature):
    - Tier 5: Silver Hand of Nuada, Spear of Lugh
    - Tier 4: Skull of Brigid, Horn of Bran Galed, Crown of Myrdynn (temporal religious head)
    - Tier 3: Tusk of Torc Triath
    - Tier 2: Torque of Boudicca, Old Carnyx, Horned Helm, Battersea shield
    - Tier 1: Generic tier 1 religious artifacts
  - Also introducing a new heresy, Britannic Pagan!

Britannic Pagan:
  - A matriarchal and monotheistic religion based on the Romano-British goddess Britannia, a personification of the isles themselves.
  - Borrows heavily from Catholicism, using the College of Cardinals (Circle of Dryads), a system of Saints and Sanctaidd (Angels), and a new Thumoideachais mechanic (baptism) I've created.
  - The Arch-Dryad is the head of the Britannic Church, a position formable by decision for a King or Emperor ruling Middlesex with sufficient cash and piety. There must also be at least 16 Dryads in existence to form the Church of Britannia.
  - Dryad, Bad Dryad, and Child of a Dryad traits have all been added. Only priestesses get the Dryad trait.
  - The Thumoideachais mechanic allows a ruler to request a priest to officiate a Britannic baptism with a targetted decision.
    - The Thumoideachais must be held before the child turns 3.
    - If a child reaches the age of 3 without a Tumtha, they become Sych, "dry". This is a mark of shame for a Britannic and will worsen relations with other members of the faith and the Church in particular.
  - A fertility festival called Imbolg has been added for Britannics. It's based on the Welsh festival of the same name held in honor of St Brigid.
    - Brigid is a Saint to the Britannic as well and features heavily in the flavor text.
  - The Knights of Saint Boudicca are the Britannic holy order and will be formed shortly after the Arch-Dryad is created.
  - Britannic rulers are restricted to Enatic, Enatic-Cognatic, and Absolute Cognatic succession laws.
    - Council voting behavior has been updated to ensure that Britannic councilors will behave appropriately.
  - Britannic rulers are forbidden from lowering the status of women laws and will never choose to vote in favor of doing so.
  - There are now Britannic artifacts to be found when searching for artifacts (Monks & Mystics feature):
    - Tier 5: Y Tair Tonau "The Three Waves" (trident of britannia), Helm of Britannia, Shield of Britannia
    - Tier 4: Skull of Brigid, Horn of Bran Galed
    - Tier 3: Tusk of Torc Triath
    - Tier 2: Torque of Boudicca, Old Carnyx, Horned Helm, Battersea shield
    - Tier 1: Generic tier 1 religious artifacts

Hellenic:
  - As with vanilla, Hellenic Pagan is now unreformed and reformable.
    - Disabled the Myrmidon mercenary company in favor of the vanilla holy order of the same name.
      - I'll add a new merc company for hellenes eventually!
  - The Philosopher event chain is now more likely to fire and the max demense size requirement is relaxed to 230.
    - Various conditions will also increase the odds of the event firing, such as being in a defensive war and your religion having a low MA (<50%).
  - There are now Hellenic artifacts to be found when searching for artifacts (Monks & Mystics feature):
    - Tier 5: Nimean Lionskin, Kronium, Bloody Robes of Caesar, Aethon's Feather
    - Tier 4: Hector's Armor, Odysseus' Bow, Death Mask of Agamemnon, Crown of Theseus
    - Tier 3: Skull of Alexander, Alexander's Armor, Golden Amphora, Sphinx Claw, Golden Apple
    - Tier 2: Corinthian Helm, Petrified Tongue of an Oracle, Silver Amphora, Fragment of Achilles Shield
    - Tier 1: Generic tier 1 religious artifacts
  - Disabled my Roman cultural conversion events, as there is some evidence they are responsible for the CTD bugs some have experienced.
    - Those with Holy Fury can still do the Roman Renaissance event chain that comes with the DLC.
  - The decision icon for organizing the Sacred Band should work properly now.


Kemetic:
  - Kemetic Pagan is now unreformed and reformable.
    - The unreformed religion has no religious head, and will be referred to as Egyptian Pagan.
    - The reformed one now has the holy orders and "Rebuild Luxor" decision.
    - The Paragon Cult of Amun will now be created on reformation.
    - Crown of Upper and Lower Egypt (temporal religious head) has been added.
    - Nile River events have been modified to be less spammy.

Atenic:
  - Made it more clear that forming the Meryatenate requires that Akhetaten is restored.
    - The Sunburst Crown is given to the Meryaten when the title is formed.
  - Added an icon for the "Organize the Burning Blades" decision


2018-06-10 v0.41.3 "Cardea"
-------------------------
> Cardea was the ancient Roman goddess of the hinge, doors, and winds. She was closely associated with the fundemental Roman city planning concept of "cardo", which described the main north-south street of a settlement or army camp. This is where the English "cardinal" (as in directions) comes from.

General: 
 - Fixes bug allowing an incomplete and in development decision to be visible, despite it doing nothing.
  - Characters who took this decision will be refunded their money when you load the game with this update!

Celtic:
 - Druids of the Circle will not be referred to as Cardinals when they are elected anymore.


2018-05-16 v0.41.2 "Aura"
-------------------------
> Aura was a minor goddess of the breeze. Sometimes the plural Aurae was used, implying a race of nymphs. According to Nonnus, she was the daughter of the Titan Lelantos and the mother, by Dionysus, of Iacchus, a minor deity connected with the Eleusinian mysteries.

General:
 - Compatability with CK2 2.8.2

Celtic:
  - Organizing the Fianna is more accessible than previously, specifically to British Emperors.

Kemetic:
  - Fixes bug that prevented the "Lost in a Sandstorm" event from firing.
   - Also fixed the death sound for this event.


2017-12-17 v0.41.1 "Euronotus"
-------------------------
> Euronotus was a lesser god representing the South-East winds, his name indicates this. "Euro (East)" and "Notus (South)".

General:
 - Compatibility with CK2 2.8.1

Celtic:
 - Fixes bug preventing Court Druid title from being manually assigned.

Atenic:
 - Fixes bug where Tribal Aten rulers who use the Adopt Feudalism decision would get Feudal Government instead of Iqta.


2017-11-23 v0.41.0 "Apheliotes"
-------------------------

General:
 - Compatibility with CK2 2.8


2017-09-03 v0.40.4 "Asteria 2"
-------------------------

General:
 - Resolves bug where tribal characters would usurp county titles in their de jure kingdom, turn feudal, and all holdings would be destroyed.
 

2017-09-02 v0.40.3 "Asteria"
-------------------------
> Asteria "the starry one" was the titan of falling stars and nocturnal oracles and the daughter of Coeus and Pheobe, her sister was Leto. Unlike her husband, Asteria has several stories attributed to her. One such tale describes her flight from the advances of Zeus; she transformed into a quail and dived into the ocean, where she became an island bearing her name.

General:
 - Merged changes from the CK2 2.7.2 "Tiny Patch"

Celtic:
 - Removed two year cooldown for "Invite Druid to Court" decision.

Kemetic:
 - Pyramids are now an actual building that will appear in your holdings.
  - Thanks to IhateTrains for importing the code from WtWSMS.


2017-07-04 v0.40.2 "Eurybia"
-------------------------
> Eurybia, whose name means "she who has a heart of flint", was the titan mother of Perses. Like her husband Krios, very little is known of Eurybia other than her immediate family. The meaning of her name suggests a cruel and callous nature.

General:
 - Secret Cults now can only Prepare Ground in provinces owned by members of the Secret Cult.
 - When apostates are burned at the stake and members of the society are informed, there is now an option to leave the society. The character is then barred from being recruited to any secret religious societies or devil worshipper societies for 5 years.

Celtic:
 - The Old Wizard has slightly better traits now and will automatically become a Zealous Druid if you decide to go Celtic Pagan, assuming he's alive and in your court.
 - When conversion cascades down your realm tree, characters whose true religion is Celtic pagan will always accept conversion to Celtic pagan.

Promethean:
 - Based on some feedback from forum user PlotVitalNPC, I've changed how moving prosperity to devestated provinces works to add some player agency.
   - The devestation of the province is reduced from -3 Prosperity to -2 Prosperity.
   - You now select the donor province with a title decision (right click on the county shield) called "Prepare Settlers".
   - You then select the receiver province with another title decision called "Send Settlers".
   - Only one province at a time can be preparing settlers.
     - The selected province has an empty modifier called "Preparing Settlers" so you know which one it is.
     - The modifier expires after 30 days.
     - You can use a decision "Stop Preparing Settlers" to de-select that province.


2017-06-13 v0.40.1 "Krios"
-------------------------
> Krios was the titan father of Perses. Little is known of this Cthonic deity, other than that he and his wife Eurybia sided with the other titans in the Titanomachy and have been imprisoned in Tartarus for all time.

Celtic:
 - Fixed a bug with the Old wizard event chain for Celts.

Promethean:
 - Fixed a bad condition in the Expansion CB.
 

2017-06-11 v0.40.0 "Perses"
-------------------------
> Perses was the son of the Titans Krios and Eurybia. His name means Destroyer/Ravager, a fitting name for the Titan of devestation. He was married to the Titan Asteria, with whom he fathered Hecate, the goddess of magic.

General:
 - Modifiers to Prosperity for many events and decisions have been added for Reapers Due owners.
   - All festivals/celebrations added by the mod now add a small amount of prosperity.
   - Decisions to construct new holdings (Crotone, Luxor, etc.) add large amounts of prosperity.
   - Gaining a Sacred Symbol adds a small amount of prosperity, but losing one removes the same amount.
   - And many more!
 - Many fixes for small bugs.
   - A lot of bugs related to conversion events have been fixed. (Secret Religion related commands are not idiomatic).

Promethean:
 - The Depopulation mechanic of the Expansion CB has been re-written to modify Prosperity instead (for RD owners only, the old system still works if RD is off).
   - Now, sieged provinces will lose three levels of prosperity, and all their progress toward higher prosperity will be lost.
   - The CB cannot be used if there are any provinces in your realm that are depopulated at any level.
 - Added events to send immigrants from your prosperous demesne provinces to depopulated ones, losing Prosperity in one province to reduce depopulation in the other.
   - These events represent the Promethean policy of lebensraum and replace the old event that triggered on the Depopulated modifier for Reapers Due owners.
   - There is a chance that the province converts to your culture and religion. This chance increases dramatically for each level of Prosperity you transfer.
   - If you don't want to give up a level of prosperity in one of your demesne provinces, you can ask your direct liege for help.
     - Your direct liege can deny the request, send settlers (one prosperity), or forward your request to their liege.


2017-05-14 v0.39.2.2 "Pelagon"
-------------------------

Celtic:
 - Fixed a bug that broke the Old Wizard event chain for Celts.


2017-05-09 v0.39.2.1 "Thebes"
-------------------------

Hellenic:
 - Hellenic can now be a secret religion.
 - Secret Cults can be created for Hellenism.


2017-05-07 v0.39.2 "Cadmus"
-------------------------

General:
 - Compatibility with CK2 2.7.1
 - Most conversion events now set secret religion rather than open religion.
 - Fixed a lot of localization bugs related to societies and custom localizations.
 - Implemented the decisions to secretly convert to a religion if you own a holy site of that religion.
   - For logical consistancy, the entirely fictional heresies of Prometheanism and Titanism require at least one province in the world to have their religion before the decision can be taken.
 - Adjusted merc compositions again in an attempt to make them more like vanilla holy orders and merc companies.
   - They've also been adjusted in some places to be a little less terrible and random.
   - I'm very open to constructive feedback on merc compositions.

Hellenic:
 - Updated acceptable cultures for the Studied the Classics event chain.
   - Removed Norman, French, and Occitan cultures.
   - Added Serbian and Croatian, but it is much rarer (20% as likely, to be precise).


2017-04-02 v0.39.1 "Polemos"
-------------------------

General:
 - Added some missing text in localisations.

Celtic:
 - The Pendragon title is no longer applied to every Welsh/Breton/Pictish Emperor of Britania, only the first.
 - Some bits of French translation, provided by Amendile.

Promethean:
 - Fixes the Crotone Academy of Engineering's bonus being backwards (+5% local build time, rather than -5%).
 - Prometheans now have access to the Hermetic Society.
   - Neoplatonist traits give you Hermetic Society currency.

Titan:
 - Some bits of French translation, provided by lukaslunt.

Atenic:
 - Aten characters now use the Iqta government by default.
   - This was intended to go out in Ares but was forgotten.
   - This change is intended to be temporary; a custom government for Aten characters is probably in the cards.


2017-03-23 v0.39 "Ares"
-------------------------

General:
 - Added unit modifiers to Hellenic, Titan, Promethean, Kemetic, and Atenic.
 - Compatibility with CK2 2.7.
   - Your old saves will probably work, but back them up just in case!
 - Secret Religious Societies are available for all 7 religions.

Celtic:
 - Improved the conversion events slightly.
   - Unlanded children of the liege will not discount the possibility of converting just because they are Zealous.
   - The player's court will always convert (unless they are landed, like councilors, or prisoners).
   - The Insanity conversion event will now also cascade through the realm, allowing vassals and courtiers to convert with you.
   - This should give Celtic revivals a leg to stand on. It's still unlikely they'll be more than a blip, but there's always a chance.
 - Unfit King mechanic is enabled on an experimental basis.
   - It is controlled by a game rule, and is disabled by default.
   - In an effort to balance the ability to abdicate, the old ruler will have a strong claim on all titles and all Powerful Vassals will get a weak claim.
   - Please give feedback on this mechanic!
 - Added Devil Worshipper Society called The Unseelie Petitioners.

Hellenic:
 - Added new Mercenary company, The Myrmidons.
   - This company comes into existence when the entire duchy of Thessalonika is converted to Hellenism.
   - Has 4 pure heavy infantry regiments.
 - Updated the Philosopher event chain.
   - It is now possible to fire when the Empire has 130 or fewer realm holdings, up from the previous limit of 100.
   - More events have been added to the chain to make the Philosopher earn any support he may get from the Emperor, and to allow for a better story to unfold.
 - Added Devil Worshipper Society called The Coven.
   - Prometheans and Titans have access as well.

Kemetic:
 - Added Devil Worshipper Society called The Fangs of Apep.
   - Atenic have access as well.


2017-02-16 v0.38.3.1 "Hippolytus"
-------------------------

Hellenic:
- Fixed a critical bug in the Philosopher event chain that was caused by the Virbius update.


2017-02-16 v0.38.3 "Virbius"
-------------------------

Hellenic:
- Fixed a critical bug in the Philosopher event chain.


2016-11-04 v0.38.2 "Egeria"
-------------------------

General:
- Compatibility with CK2 2.6.2
- New Game Rule: AI Revival
  - On: Player and AI are both able to get Ancient Religion revival events.
  - Off: Only the player can get Ancient Religion revival events.
- Did my best to obey the Supernatural Events Game Rule. Please report events that should be obeying it but aren't.
  - Left the Sacred Symbols and Sidhe events alone intentionally, since they are an important mechanic for Celts.
- Increased the frequency of the event that clears the Angry Sidhe modifier after a decent/good sacrifice.

Hellenic:
- Fixed a bunch of broken flavor events
- Hellenic Reconquest is now usable once every 50 years, not once per lifetime.

Promethean:
- Neoplatonist traits (Stoic, Skeptic, Epicurean) are now considered good traits for doctors.

Celtic:
- Druid is considered a good trait for doctors.
- Added new "Battle Raven" Celtic Crusader trait.

Kemetic:
- Added new "Mighty Bull of Montu" Kemetic Crusader trait.

Atenic:
- Added new "Lightbringer" Atenic Crusader trait.


2016-8-27 v0.38.1 "Actaeon"
-------------------------

Kemetic:
- Fixed Kemetic revival events being called for any character at random.


2016-8-27 v0.38.0 "Diana"
-------------------------

General:
- Updated to CK2 2.6.1 compatibility.

Celtic:
- Fixed some backward mtth modifiers in Aonach Tailteann events.
- Gaulish culture now has special localizations for titles.
- Non-theocracy title localizations have been removed from Celtic and Druidic paganism.
-- It is my opinion that feudal, republican, and tribal titles should be derived from culture.
- Fixed bad localization for the Warden of the Wild minor title description.

Hellenic:
- Quite a few Hellenic flavor events courtesy of retired modder cybrxkhan.
-- Includes one really long event chain, but it's quite rare!

Promethean:
- Prometheans now get an event on adulthood to choose between the three Neoplatonist traits; Stoic, Skeptic, and Epicurean.
-- You can switch to a different trait by decision every 5 years for 200 piety.
-- Members of the same school have improved relations with one another.

Kemetic:
- Fixes an issue where men could become pregnant in a cat-related event.
- First (of three planned) Kemetic Revival event chain is out!
-- There is a small chance that those who are On Hajj or On Pilgrimage in the East (Jerusalem, Antioch, or Axum) will be become lost in a sandstorm and meet an old man in an ancient temple.


2016-3-5 v0.37.3 "Tullius"
-------------------------

General:
- Update to 2.5.2
- Factored in the existence of the Feeble, Dull, Shrewd, and Robust traits for events and decisions, where appropriate.
- Fixed bug in Pagan Subjugation that allowed vassals who subjugate another realm of equal or greater rank to their liege to become independent, which had been introduced in Cecrops.
- Used new infamy modifier for custom CBs.
 - Hellenic County Liberation = 75% Infamy
 - Hellenic Reconquest = 85% Infamy
 - Promethean Expansion gets no modification.


2016-2-16 v0.37.2 "Aetna"
-------------------------

General:
- Merge tactics from 2.5.1
- Fix bug relating to Hellenic EREmperors being unable to reform the empire.
- Fix localization overrides not being used.


2016-2-10 v0.37.1 "Cecrops"
-------------------------

General:
- Compatability with CK2 2.5.1
- Adjusted opinion modifiers and honorary titles to match new vanilla balance.
- Laws adjusted to take into account ancient religions.
-- Celtic Pagan, Druidic, and Promethean will make female-friendly laws easier to get.
-- Titan Cultists, on the other hand, are decidely less enlightened on the subject of women.
- Minor Titles and councilor positions have been adjusted to account for ancient religions.
-- Like Laws, appropriate religions will make it easier or harder to hire/appoint women.

Promethean:
- Bug fixes relating to the Unbinding Festival and Rebuilding Crotone.
- Stoic trait now grants a +5 General Opinion bonus, as intended.
- Skeptic and Epicurean traits now have icons.
- All three philosophy traits have been given potential blocks to keep random children in Scotland from getting them.



2016-1-26 v0.37.0 "Vulcan"
-------------------------
General:
- Nearly every kingdom in the game now has a Crusade weight for all of the added religions, including the heresies.
-- This means your religious heads will intelligently call Great Holy Wars.
- Moved some data around to different files to reduce compatability headaches.
- Added Chronicle entries for many events.
- Modified Lets. Get. PAGAN! to include heresies.
-- Georgians and Armenians become Promethian.
-- Alanians become Titan.
-- East Africans become Atenic.
-- Duke of Galilee gets his stones back if the world goes pagan. Surely a blessing from Dionysus...
- New Minor Titles: Champion (copy of vanilla title that only my religions can use), Master of Arms (pagan group).
- Holy Orders rebalanced (yes, again) to bring them more in line with Vanilla HOs.

Celtic:
- Tweaked St Kilda event chain to be more likely.
- Court Wizard conversion chain now cascades through the entire realm, increasing likelihood that vassals will convert with you.
- Fixed issue in the event where a son or brother asks to join the red dragons where the buttons would be labeled backwards.
- Galloway is no longer a holy site. Dijon takes its place. This is to represent the Fountains of Sequana, a major place of worship for the Continental Celts. Also to make reformation a little harder. It was way too easy to start as Gwynned and take Dublin and Galloway and do some raiding to get up MA.
- Fixed an issue caused by a Druidic training event calling a Sons of Gwydion event.
- The Wolf Tails will still form if you somehow manage to Reform Celtic before converting even a single province.
-- In this case, they will be Druidic to start.
- In the mercenary spirit of their ancient forebears, The Wolf Tails can be hired by anyone who has the coin.
- Fixed broken Headhunter events. It should be possible to become a Living Legend again.
- New Minor Titles: Chariot Master, Headsmen, Warden of the Wilds.
- New decision to invite a bard to your court.
- A random event may have a Bard and their troupe arrive at your estate seeking lodging. Allow them to stay, and you will have the opportunity to invite the bard to join your court.
- Improved Religion UI, from CK2Plus.

Hellenic:
- New Hellenic revival event chain inspired by Michael Psellos and Plethon.
-- Byzantine or Roman Empire must be at 100 or fewer realm holdings, be held by a non-pagan, cannot already have the philosopher in their court, and the current ruler must not have had the event happen to them already.
-- A Philosopher from the University of Constantinople will seek to join your court and provide you with his advice.
-- Over the course of several years, the Philosophos will cause controversy and will require your support. This will come with a price.
- Three traits; Stoic, Skeptic, and Epicurean have been added. The Philosopher will come with the Stoic trait, but it is otherwise only available with Ruler Designer (for now). Skeptic and Epicurean do not yet have icons.
- Added a Hellenic revival event chain if the Mani Peninsula (Monemvasia) is in the realm, as an homage to the 30 pages thread about that on the forum.
- Tweaked Studied the classics event chain:
-- Made it more likely to be taken by an AI courtier of the player.
-- Added low possibility for Hellenic heresies.
-- Added opportunity for host to convert, if specific traits.
-- Increased valid cultures to the entire Latin and Byzantine culture groups.
- Sacred Band Holy Order from CK2Plus has been included (thanks guys!).
- Added the "Hellenic Legion" holy order, created by Mbites.
-- It appears when Rome or Constantinople is held by a Hellenic Pagan, *or* when the Roman Emperor or Basilius is Hellenic Pagan, and it is Roman cultured.
- New Minor Titles: Fylakasminos (Keeper of the Flock), Chiliarch, Proxenos, Hellanodikos.

Promethean:
- Promethean holy sites have been moved around to better reflect the lore and to differentiate them from Hellenism and the Titans.
-- Alexandria; A center of advanced learning for over 1000 years.
-- Consenza; Former site of a Pythagorean Academy, and must be rebuilt (via decision, like the Restore Luxor chain, but different).
-- Kartli; Kartli covers the southern slopes of Mt Kazbek, the legendary peak where Prometheus was chained on the orders of Zeus.
-- Thessalonike; Common holy site for Hellenic and Promethean, to create conflict.
-- Athens; Site of the First Academy and point of conflict between Titan Cultists and Hellenes.
- Prometheans may now Restore the First Academy via decision, making the Philosophos of Piraeus the Scholarch of the First Academy.
- Prometheans can Rebuild the Academy of Crotone, the site of an ancient Pythagorean academy.
-- +20% MA for Prometheanism for 30 years.
- Prometheans can Organize the Men of Steel, a Holy Order of the faith. The culture of the holy order matches the organizer.
- There is now an Unbinding Festival decision and event chain that Prometheans can do once a year. It is a celebration of the Unbinding of Prometheus from his prison on Mt Kazbek.
-- The event chain includes lots of small random events inspired by vanilla and VIET.
-- If you're lucky you may get a skilled courtier. If you are unlucky, you may be injured, or even die!
- Prometheans now have access to an invasion CB called Expansion. It is inspired partially by Plato's Republic.
-- Conquered provinces suffer from a "Depopulated" modifier for 30 years after the invasion, making it difficult to hold but more likely to convert culture and religion to the top liege.
-- It targets Kingdoms and is based on the tribal invasion cb.
-- It can only be used if you are independent and do not have Depopulated provinces in your realm.
- New Minor Titles: Proxenos, Hellanodikos, Archopapyri (Master of Scrolls), Archothisavrous (Master of Treasures), Fylakasflogas (Keeper of the Flame).

Titan Cult:
- Titan holy sites have been moved around to differentiate them from Hellenism and Prometheanism and better reflect locations that would actually be holy to them.
-- Rome; because of the large temple to Saturn/Kronos.
-- Antioch; because of a mosaic of/dedicated to Tethys. Also it spreads the sites out.
-- Athens; Location of the Kronia festival and point of conflict with Prometheans and Hellenes.
-- Thessalia; location of Mt Othrys, the Titan capitol during the Titanomachy (basically the Titan Olympus).
-- Rhodes; Once held the Colossus, a massive statue to the titan Helios.
- The Sickles are a holy order that can be created by Titan Cultists. The culture of the holy order matches the organizer.
- New Minor Titles: Fylakasminos (Keeper of the Flock), Hellanodikos, Konistrachos (Master of the Arena).

Kemetic:
- Added Nile Flooding events, courtesy of retired modder cybrxkhan.
-- Every year the Nile river will flood, sometimes good, sometimes bad.
- Numerous flavor events for Egyptian and Aten pagans, also courtesy of cybrxkhan.
-- Events involving cat worship, palm trees, and keeping the principle of Ma'at in your heart.
- Sed Festival back to requiring a 30 year reign to use.
-- This is more historical and matches the fairly significant boons rewarded. The previous reduction to 10 years was to counteract the lack of flavorful events and decisions available to Kemetic and Atenic characters.
- Coptic culture is available through ruler designer and the console.
-- Coptics have access to a Khopesh wielding heavy infantry/horse archer retinue called the Anhuri.
-- Coptics also can build a Temple of Anhur building to enhance your heavy infantry troops.
- New Minor Titles: Gods Wife, Divine Adoratrice, Master of Palms, Fanbearer on the Right Hand of the King, Iry-pat, Haty-a, Khetemty.

Atenic:
- Faithful followers of Aten can now restore Akhetaten, the ancient city we call Amarna today.
-- This decision is almost a carbon copy of the Restore Luxor decision. It may receive more love in the future.
- Atenism now has a religious head, the Meryaten, which is a King tier Fylkir style title held by the reformer.
-- The Meryaten is created by decision, and requires that Akhetaten is restored.
- The Burning Blades are a new holy order for Atenism that can be created via decision and are immediately vassalized by the organizer.
- Atenic now uses Decadence. If the representitive of the divine on Earth behaves in a manner unworthy of the divine, the people will rise up to overthrow the unworthy in the name of Aten.
- New Minor Titles: Gods Wife, Divine Adoratrice, Master of Palms, Fanbearer on the Right Hand of the King, Iry-pat, Haty-a, Khetemty.


2015-8-12 v0.36.4 "Beroe"
-------------------------
- Compatibility with vanilla 2.4.3
- Fixed issue where Tribal Marshals couldn't use the Train Warriors action
- Hellenism, Prometheanism, The Titan Cult, and Atenism are all available in the Ruler Designer.
- Pagans no longer use random Coats of Arms for Count and higher titles.
- "Studied the Classics" is more likely to occur in later start dates than previously (but still less likely than early start dates).
- The third witch is now a Kemetic pagan.
- Updated religion descriptions using the new _FEATURES localization.
- "Lets. Get. PAGAN!" prevents Christian and Muslim religious heads from calling Crusades/Jihads.
- Added missing councilor localization for alternate governments.
- The Pontifica Maxima will no longer be referred to as a Legata Augusti.
- Roman Viceroys now have unique localization.
- Sed Festival can now be taken after 10 years instead of 30, so you actually have a chance of using it.
- Court Wizard is no longer grantable.


2015-7-19 v0.36.3 "Eryx"
-------------------------
- Compatibility with vanilla 2.4.1
- Optimization of some MTTH events, by using pre-triggers to exclude courtiers.
- Fixed Gaulish Cavalry Retinue being Heavy Infantry. Should be Heavy Cavalry now, as intended.
- Messalians can hire women to all councilor positions again.


2015-3-10 v0.36.2 "Anchises"
-------------------------
Celtic Paganism:
- Wolf, Learning Druidic Arts, and Fennid traits have had their fertility moddifiers reduced by a factor of 100.
- Court Druid and Bard minor titles no longer restricted by government type. Any ruler (that matches other requirements) can hire them.
- Court Bards can no longer be landed. If they are busy administering their own land, how can they have time being your bard all day?
- Restless Sidhe is about 40% less likely to occur, and if you've had a good sacrifice to the Sidhe recently it won't happen.
-- Also descreased the mtth for the "sidhe are calmed" event, which requires you have at least a neutral response to your sacrifice. Should be far less annoying for those of you with a demesne larger than 4 now ;)
- Fixed localization problems in the Sidhe events that mistakenly referenced the religion of the province, instead of the ruler. This meant that a Celtic Pagan may occassinonaly say "May the Blessed Virgin protect us!".
- Adjusted the Potential on Invite Court Druid and Organize Fianna so it stops cluttering up your menu when its irrelevant. You now must either be a Irish cultured or personally hold land in Ireland to see it (in addition to being Celtic Pagan or Druidic).
- Fixed bug that made nearly every child of a Celtic Pagan player reincarnated.
- More small localization fixes.


2015-02-27 v0.36.1 "Adonis"
-------------------------
General:
- New cover image for Steam Workshop.
- Tags added for Steam Workshop.
- Pagan County Conquest can now target counties up to one sea zone away. Celts in Britain should have an easier time hoping the Irish Sea or the Channel.
- Added missing OR in the paganify event that meant that those cultures who should have gone Tengri, didn't.
- Added localization for the new CoA types, so they don't show as coa_plain_celtic, etc., in the Ruler Designer.
- Updated the Gone Pagan decision(s) to the latest version available from CK2+.
-- Characters that convert via the Gone Pagan decisions will gain the Zealous trait, which should make it less likely for them to instantly convert when faced with a Holy War.

Celtic Paganism:
- Children who are already Druids, or are training to become Druids, will not ask their parent to send them for Druid training.
- The Sacred Dogs modifier should now work as intended, giving a garrison growth bonus.
- The Sacred Lake tax bonus has been reduced from the insane 80% to the, likely intended, 8%.
- Your daughter will no longer be referred to as a "madman" if she comes back from her Druid training insane.
- Druidic (reformed celtic) can no longer be selected in Ruler Designer.
- Added missing gfx for wolf trait.
- Fixed localization for the Sons of Gwydion formation event ("restless sons of Emperor." -> "restless sons of the Empire.")
- Fixed bug in "Child returns from druidic training with a strange child" event that made the ruler the parent of the strange child, instead of the returning druid.
- Fixed some localization that was gender specific. These will continue to crop up as we find them.
- The temple of Mellifont (Dublin holy site) should exist in all starts now.

Hellenic:
- Epic Blood traits no longer selectable in Ruler Designer. Its not finished yet, stop asking!

Promethean Paganism:
- Prometheans can now hire women to any councilor position, just like the other <feminist = yes> religions, as intended.


2015-02-21 v0.36.0 "Venus"
-------------------------
General:
- Pagan religions now use random flags for all title tiers
- Added a paganify decision available on startup, before unpausing the game
- Fixed adopt feudalism and republicanism decisions
- Removed FRENCH, SPANISH and GERMAN used as localization for non-translated keys: the game now properly defaults to English when a key is not translated in another language and playing in that language. This allows to play with partially translated mod(s), yet being able to see something useful for the keys missing translations.
- Merged localization files to simplify maintenance and translations
- Listed all event ranges in event_id.txt and fixed some event ID collisions
- Fixed encoding of some files
- Fixed ALL validation errors from non-vanilla files
- Fixed convert_to_attacker_religion and convert_to_reformed decisions having no effect
- Simplified convert_to_reformed effect using abandon_heresy = yes
- Updated README and add DEV installation steps
- Added dignity to all new heads of religion

Celtic Paganism:
- Added unique title frame and CoA patterns
- Added College of cardinals for Druidic religion (falls back to open-elective w/o SoA) !
-- Added druidic suitability icon
-- Tweaked the "Open Cardinals screen" button to be non-Christian
-- Tweaked the selection of Arch-druid to ensure he holds a holy site, and favor reformer culture / culture group
-- Workaround vanilla bug of cardinal seat nominations not firing, thanks to the above usurpation
- Changed druidic to celtic_pagan and druidic_reformed to celtic_pagan_reformed for better mod compatibility
- Cleaned up councilor allow clauses and made celtic_pagan properly feminist
- Improved invite druid decision feedback with follow-up event where the druid actually presents himself and event options to nominate as Chancellor/Seer/Court druid, if applicable
- Added basic gaulish culture (no flavor), with a cultural building and retinue
- Tweaked merc and holy orders composition/growth (sons of gwydion growth increased to 25%,  wolf tails composition tweaked, fianna levy size reduced)
- Changed hold divination and give offerings to sidhe to be high priority
- Changed vassalizing fianna to cost 500 prestige
- Fixed auto-suggest court druid notification that kept firing
- Druidic education events now work for both genders
- Made it clear in events and in trait description that Druids cannot inherit.

Hellenic Paganism:
- Added unique title frame and CoA patterns
- Hellenic pagans can not raid unless they are tribal.
- Making Hellenism the state religion will now give you the nickname 'the Apostate'
- Created decision to recreate the pontificate and pontifex_restored religion modifier
- Created titan_pagan and promethean_pagan heresies
-- Added titan 'Hold Thysia' decision 
-- Titan Cultists are barbaric, it is an unreformed faith that cannot reform, and has many simalarities to other such religions
-- Promethean pagans can no longer use, or are subject to, subjugation
-- Promethean pagans can no longer use county conquest
-- Prometheans are pre-reformed and have a creatable head of religion, the Scholarch of the First Academy
- Rebalanced the Roman Legion retinue to match vanilla sizes (250)
- Fixed hellenic_county_liberation CB discrepancy (using CB on other rulers under same liege causes the CB to end inconclusively): CB cannot be used on same realm characters.
- Fixed restore_roman_empire decision having no effect
- Allowed "Studied the Classics" revival event chain to fire after year 1066 (with increased MTTH) and added religious sympathy trait.
- Fixed mayor not becoming Roman when city restores Roman customs
- Allowed Court Bard and Royal Champion for tribal rulers
- Made it clear in events and in trait description that Vestals cannot inherit
- Fixed a typo that allowed you to emulate multiple heroes
- Opened up the conversion event a little more to make it more likely
-- No maximum age requirement.
-- No longer requires Christian group, and pagans more likely to convert if moral authority low.
-- Based chance of courtier converting changed to 15%.
-- Christians and Muslims far more likely to convert than jews or indians.

Egyptian Paganism:
- Added unique title frame and CoA patterns
- Added Sed festival decision and event chain, for Pharaoh's having ruled for 30 years:
-- Can be retaken every 3 years for increased bonuses each time
-- Chances of bad outcomes, based on traits
- Fixed typos in some Egyptian event flags
- Atenism is pre-reformed.


2015-01-31 v0.35.4 "Minor Fixes"
--------------------------------
- Celtic Pagans can now hire Celtic pagan women to any councilor position, assuming they otherwise qualify. Note: Celtic Pagans and Druidic's require their Chancellor and Chaplain to have the either the Druid, Bad Druid, or Poet trait. The Invite Druid to Court decision fires an event 3 days after you make the decision. So long as you don't have a Court Druid (minor title) you can make the decision. Also, all Celtic Pagan/Druidic Theocracies are automatically given the Druid trait.
- Fixed religion description localization for Celtic Pagan, Druidic, and Hellenic.


2015-01-21 v0.35.3 "Error Free!"
--------------------------------
According to the Validator anyway!
- Fixed CTD when conquering certain counties as a Celtic Pagan.
- Added localization for several dozen titles, modifiers, and events.
- Added new god names for Kemetic pagans.
- You should now be able to (successfully) look up to your favorite hero of the Trojan War as a hellenic pagan. Unless your favorite hero isn't Achilles, Odysseus, Nestor, Hector, Aeneas, or Paris. Minor thematically appropriate benefits incurred.
- Removed defunct compatabilty files to reduce confusion and clutter. They'll make a triumphant return, I promise!
- The Arch Druid can now call Great Holy Wars.
- Notification event that the Wolf Tails have founded is no longer being handed to a province


2015-01-15 v0.35.2 "Maintenance Release"
----------------------------------------
- Fixes an event id collision between the Wolf Tails events and three of the Celtic Sacred Symbols events.
 
 
2015-01-13 v0.35.1 "Religious Icons and Other Fixes"
----------------------------------------------------
- Religious Icons should be working again.
- The Sons of Gwydion now have a flag (a copy of the Red Dragons flag, for now). You'll have to delete your flag cache. There are tutorials online for this.
- Fixed syntax errors in a handful of events, traits, and modifiers have been fixed.


2015-01-12 v0.35 "Second Life"
------------------------------
This release marks a second life for Ancient Religions. With superskierpat having moved on to higher education, others take up the charge of maintaining and expanding the work of their predecessor.
Now, enough with the dramatics, time for details!

- Dozens of minor fixes from bad event triggers to localization. So many I can't even count them!
- A major reorganization of the files to make com-patches much easier in the future!
- Druidic pagans now have 2 holy orders and 2 mercenary companies!
- The Fianna have had several of their events fixed, expect a visit from the boisterous warriors if you are a Druid and a Gael (Irish or Scottish)! As before, they are created by the King (or Queen!) of Ireland, and can also be vassalized by said monarch, but it is costly. Young men in your realm may wish to join the Fianna, seeking fame and glory.
- The Sons of Gwydion. A mercenary company much like the Varangians, they are organized by, and serve, the Reformed Druidic Emperor of Prydain. They will have a slew of flavor events (most of which are cribbed from the Varangian events). Like the Fianna, your sons may wish to join the Sons of Gwydion.
- The Red Dragon Knights may be formed by any Reformed Druidic King level ruler. They operate like any other Holy Order. They can take donations, give out loans, and will occasionally ask druidic rulers in the de jure empires of Britain, Francia, Hispania, or Germania for permission to build a barony in their lands.
- Finally, The Wolf Tails are a mercenary company that will form spontaneously shortly after the first province converts to Druidic pagan (un-reformed). (The Wolf Tails and the Fianna will both convert when Celtic Paganism reforms.)
- Kemetic (Egyptian Pagan) has been ported over from CK2+ (thanks guys!) and is available if you have Ruler Designer. Currently there are no revival events implemented, but they are planned for v0.40!
- Refactored mod to use ACR_ prefix on txt/csv files and ACR sub-folders for assets, to ease-up mod integration


2013-2014 Alpha "Merged Celtic Pagansim"
--------------------------------------
- Added hellenic heroes legend events (WIP)
- Improved mod compatibility by reducing overriden vanilla files
- Simplified the pagan holy cb requirements
- Fixed title_censor_desc and missing title_aedile_desc localization
- Used is_unique to simplify minor_titles
- Added "Bad Druid" trait
- Added Celtic reincarnation events (requires RoI)
- Added Court druid auto-suggest
- Used religious sympathy traits on ancient religion revival event chains
- Fixed reformed pagan ai not proselytising
- Added new Fianna and Red Dragon events
- Added CK2+ gone pagan decision
- Added AnaxXiphos religious and trait icons, and flags
- Druids and Poets now necessary in order to have chancellors and spritual advisors when celtic
- Added sacred celtic symbols mechanic
- Added druidic training, changeling, St-Kilda event chain
- Merged gaelic and brythonic religions


2013 0.31 "v1.111 compatibility"
-----------------------
General:
- Updated to CK2 v1.111
- The 0.3 flavor events will now fire much less often
- Fixed druidic decisions not appearing in decisions tab
- Various localisation fixes
- Added a music module, contains music that will fire only when playing certain religions, flavorful and free of copyright

Compatibility Patches:
- All compatibility patches updated to latest builds (Viet 1.4, PB 3.2.28, SWMH 2.81)
- Fixed Imperial Reconquest being unavailable for Hellenic Pagans in compatibility patches
- Fixed gaelic religion tab causing CTD in SWMH
- Druidic rebirth event now takes into account new SWMH celtic cultures


2013 0.3 "Compatibility patches"
-----------------------
- Updated to Crusader Kings 2 version 1.11
- Six new mythological and cultural flavor events
- Released compatibility patches or instructions for Project Balance, Viet, PB + Viet, SWMH and Arko Armories.


2013 0.21 "Tweaks & bugfixes"
-----------------------------
General:
- Updated to CK2 v1.10.3
- Fixed a few typos
- Added the Egyptian icon, you can now check it out and tell me what you think

Extended Legacy of Rome:
- Reworked the Lost Roman Provinces event chain: The list of duchies are now more historically accurate; and updated for the 1.10 map.
- Reworked the Roman Borders Restored event: The list of duchies now matches the updated Lost Roman Provincesevent chain.
- Reworked the Imperial Reconquest CB:
	- It is now based on the same duchy list as the updated Roman Borders Restored event, rather than a list of kingdoms whose de jure duchies might change during the course of a game.
	- Added the same distance condition as for holy war.
	- It is now disabled if, and only if, you could holy war the target instead, rather than being disabled against all Muslims.

Hellenic Polytheism:
- Now behaves mostly like an already reformed pagan religion, but without a religious head at the start of the game:
- Hellenic pagans form and join factions just like reformed pagans, not like unreformed pagans.
- Hellenic pagans convert and are converted like reformed pagans, not like unreformed pagans.
- Hellenic pagans can now use any Crown Authority level
- AI characters that would have agreed to "Demand Religious Conversion", had it been available, will instead spontaneously convert in on average one year.
- Hellenic pagans can no longer use the Pagan Subjugation CB
- Hellenic pagans got a Hellenic Liberation CB against any Roman, Italian or Greek county not ruled by a pagan.
- Any Hellenic pagan King or Emperor can now use the Imperial Reconquest CB once every five years against non-pagans (a Hellenic pagan Roman Emperor has of course unlimited use of it).
- When an unlanded character converts to Hellenic Polytheism after having "Studied the Classics", his host is now informed via an event.
- You now use the standard pagan interface to become Pontifex Maximus instead of a special decision.
- Only the Pontifex Maximus is now able to appoint flamines.
- Added the Vestales (a.k.a. Vestal Virgins) as minor titles appointed by the Pontifex Maximus, and a decision + events for other Hellenic rulers to nominate children for the position.
- Hellenic characters now use zoroastrian coat of arms (Temporary)

Gaelic Druidism:
- The Gaelic Reformed religion is now named Tuatha
- The Religious head is now an Ard Ri, rules over Tara and is a caliph like title
- Aonach Tailteann event chain, can be used once per rule by independent dukes, kings and emperors
- Gaelic barons and counts are now called Chiefs and High Chiefs and rule over a Tuath and a Tuatha
- The duchy of Meath no longer uses the pagan coat of arms when held by a pagan
- Fixed the court wizard event firing repeatedly for irish and scottish lords
- Gaelic holy sites are now located in Mellifont (Dublin), Iona (Scotland), Reykjavik (Iceland), Tydewwi (Wales) and A Coruna (Galicia)
- Gaels now have a Divination that can be used every 5 years instead of the Celtic celebrations
- Added an event to allow Lunatic or Possessed characters of irish or scottish culture to become gaelic pagans
- Gaelic characters now use pagan coat of arms
- When Iceland is held by an Irish or Scottish character it is named �oslainn

Brythonic Druidism:
- Fixed the court wizard event firing repeatedly for welsh and breton lords
- Brythonic holy sites are now located in Waltham (England), Whithorn (Scotland), Locmine (Brittany), Chartres (France) and Bangor Fawr (Wales)
- Brythons now have a Divination that can be used every 5 years instead of the Celtic celebrations
- Added an event to allow Lunatic or Possessed characters of welsh or breton culture to become brythonic pagans
- Brythonic characters now use pagan coat of arms


2013-06-14 v0.2 "Hellenic polytheism"
-------------------------------------
- Official first release of hellenic polytheism
- Added all hellenic emperors as pontifex maximus in history files
- Fixed there being no holy wars for reformed brythonic and gaelic pagans
- Some characters in your realm will now actually convert when you change your religion to druidism
- Differentiated gaelic and brythonic religious icons and title flags
- Brythonic and Gaelic holy orders will now reform
- The sacrifice chain for britons and gaels will now have unique text when sacrificing Norse Pagans
- Headhunter events now only triggered if you get the heroic battle events (to make sure the actual character gets the trait and not his liege)
- The schism can be mended by the catholics
- The Holy Roman Empire can reform the Roman Empire
- Added two modules: One containing only druidism and the other containing only hellenism


2013-06-13 v0.11 "Gaelic Paganism"
----------------------------------
- Removed useless name limitations, they go in the group entry
- Added Gaelic Pagan and Gaelic Pagan Reformed entries. (Gael localised Brythonic religion)
- Removed the at peace penalty and the no raised vassal opinion loss to the reformed versions
- Changed the reformed religion scriptures (Ballads to Sacred Stones) for the druidic religions and gave them the ability to call crusades once reformed
- Fixed a few character flag problems in the holy order events
- Gave the druidic religions the ability to switch to the true cognatic succession law (Based on the matriarchal aspects of the celtic cults)


2013-06-12 v0.1 "Brythonic druidism"
------------------------------------
- First release, featuring the Brythonic branch of Druidism
