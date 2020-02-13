Buoidda's crafts 1.6.2
mod for UnRealWorld version 3.32 and 3.40b
Developed with Windows 8.1, no testing on other ops
Release date 2017-01-30

[i]So, one day your character thought: "I'm pretty good at making this. I could make a living out of it."[/i]

[SIZE=6]Buoidda's crafts 1.6.2[/SIZE]


[SIZE=4][u]DESCRIPTION[/u][/SIZE]

This mod is for all those characters pursuing a career as a travelling craftsman. It suits really well for hermits as well.

It adds possibility to:[LIST]
[*]collect ore from lakes and mires, under certain conditions
[*]build bloomery furnace for smelting ore
[*]build simple stone forge and use fireplaces as forges
[*]forge all the basic iron tools, axes, pots etc.
[*]forge some iron weapons, including short spears (iron javelins)
[*]make punt, fishing rod and net
[*]make several bows, including three historical two-wood bows out of pine compression wood
[*]make the staff-bow and ski while shooting!
[*]fletch with various arrowheads of various materials. Forked fowling arrows!
[*]harvest birch root and split spruce twigs for tying equipment
[*]harvest bone, antler and sinew from your deer kills
[*]collect bear teeth to make a necklace
[*]make cordage and rope of various fibers, including willow bark! 
[*]make birch-bark items and containers
[*]build kotas with covers of fur, leather and wool
[*]wrap yourself in fur covers when sleeping
[*]make finished fur covers into leather
[*]collect guts and blood for sausages and cakes!
[*]shear sheep and knit yourself woollen clothes!
[*]Rain's Clothing Mod v3 included!
[*]Rain's clothing addition: weave wool cloth.
[/LIST]
[SIZE=4][u]INSTALLATION[/u][/SIZE]


[SIZE=3][u]QUICK INSTALLATION[/u][/SIZE]
[LIST]
[*]rename your original "biy_glossary.txt" to "ORIGINAL biy_glossary.txt"
[*]rename your original "diy_glossary.txt" to "ORIGINAL diy_glossary.txt"
[*]Place all the .txt files in the UnrealWorld game folder
[*]Place all .png image files in the "UnrealWorld\truetile" subfolder. In most cases, simply unzipping this package to URW game folder does it for you.
[*][i]If you have multiple mods you may have to check the hotkeys in menudef_*.txt -files. Each menu entry should have its own hotkey, including those in-game.[/i]
[/LIST]
[SIZE=3][u]INSTALLATION DETAILS[/u][/SIZE]

This mod is in multiple files. They do not overwrite vanilla unreal world installation. But to achieve clean menus, you probably want to comment out some vanilla recipes from diy_glossary.txt and biy_glossary.txt (latter only in case of hideworking mod).

I'm providing files to make those recommended edits, called "biy_Buoidda's glossary.txt" and "diy_Buoidda's glossary.txt".
You'll want to rename your original "biy_glossary.txt" and "diy_glossary.txt" to "ORIGINAL *iy_glossary.txt". This way they will not be read in-game.

It is not necessary to use all files, but there are some dependencies between them:

[font=Courier]
Hideworking....independent, [i]recommended vanilla "biy_glossary.txt" edits[/i]
Knitting.......independent, [i]uses couple of Rain's clothing image files[/i]
Crafts.........independent, [i]recommended vanilla "diy_glossary.txt" edits[/i]
Fletching......requires crafts, [i]recommended to remove vanilla .arrow. and .blunt arrow. recipes[/i]
Boneworking....requires crafts, complements fletching and includes cookery mod!
Bowying........requires crafts, [i]recommended to remove vanilla .primitive bow. and .shortbow. recipes[/i]
Ironworking....requires crafts and boneworking, complements fletching
[/font]

If you want to remove only parts of this mod, note that boneworking has two files and hideworking three! See file list below.

Also this mod doesn't require, but fits very nicely together with [URL=http://z3.invisionfree.com/UrW_forum/index.php?showtopic=1839]Rain's excellent clothing mod[/URL].
[i]Note that there's is some leftover code in Rain's mod that blocks .Woodsman's axe. -recipes.[/i]

I'm distributing modified Rain's clothing mod v3 bundled with this collection. I've made the following modifications to it:[LIST]
[*]commented out the testing submenu
[*]commented out .String. and .hemp rope. recipes. Functionally they are similar to .Twisted cord. and .Twisted and braided rope. recipes in my crafts mod. I did this because I wanted to be able to use {*cord} to refer to all string-like tying equipment. Rain's plant strings thus become hemp cord, nettle cord or whatever fibres origin is.
[*]many {Tying equipment} changed to {*Yarn} or {*Cord}
[*]added recipe to .Weave wool cloth.
[*]recipe .Spin Yarn. is asking for 'Fibre' instead of 'Plant Fibre'
[*]some PRICE-tags are corrected to uppercase as well (Thanks caouterizer!)
[/LIST]Rain's clothing mod is awesome! 

[SIZE=3][u]FILE LIST[/u][/SIZE]

biy_Buoidda's glossary.txt This contains suggested edits for hideworking.
biy_Buoidda's hideworking.txt 
cookery_Buoidda's boneworking.txt
cookery_Buoidda's hideworking.txt
diy_Buoidda's glossary.txt This contains suggested edits.
diy_o_Buoidda's fletching.txt
diy_p_Buoidda's boneworking.txt
diy_p_Buoidda's hideworking.txt
diy_p_Buoidda's knitting.txt
diy_q_Buoidda's crafts.txts
diy_r_Buoidda's bowying.txt
diy_Rainscloth modified for Buoidda's crafts.txt
diy_s_Buoidda's ironworking.txt
diy_z_Buoidda's TESTING.txt
menudef_Buoidda's crafts.txt
menudef_Raincloth.txt
*this readme file*
Readme RC3.txt (Readme for Rain's clothing mod v3)
truetile\bc-*.png   (52 image files)
truetile\rc-*.png   (6 image files, Rain's clothing mod v3)


[SIZE=4][u]CREDITS[/u][/SIZE]

While developing this mod, I learned a lot from Rain's professional and thorough way of doing things. I would've been much slower and harder to do this without his prior work in ironworking and clothing mods. In ironworking, there's not much original code apart from naming, but I think at least the recipe for charcoal is straight from Rain's ironworking. The knitting mod contains a lot of Rain's Clothing code, either modified or just copied.

Huge thanks for Kaaven for posting nice art for ironworking (and Rain for asking to do it) [URL=http://z3.invisionfree.com/UrW_forum/index.php?showtopic=7331&st=0]here[/URL]. I used the anvil, hammer, iron lump images. Also I shrunk and edited the anvil pic for whetstone image and shrunk coal image for charcoal tile (nice to have a small image since charcoal is made in stacks of 50). 

Likewise huge thanks for Atwood for providing tiles for bellows and the fowling arrow [URL=http://z3.invisionfree.com/UrW_forum/index.php?showtopic=8032]here[/URL].

This mod contains also modifications based on UnReal World game tiles and may be used with UnReal World game only. Using these tiles in any way for any other game/project is forbidden.

The bloomery is my screenshot of a pile of 11 stones on a pit. Edited a little hole, it looks quite nice when you light a fire on it. Just don't do it inside, you'll burn your house!

As of this release date, this package contains 52 image files. Some of those are just placeholders should I get better graphics done.
Kaaven's art is very nice, but I'd very much welcome some of my tiles redrawn by some more skilled of an artist.


[SIZE=4][u]ROLE-PLAY[/u][/SIZE]

[font=Times][SIZE=2]A smith, (in Finnish: "Seppä" or in Saami Language: "Ceahppi (one who is very skilled)") was a highly regarded person in the past. Some of them would travel between villages and farms to make iron and tools out of it. Since production of iron was very time consuming and steel precious, their services were also very well paid for.[/SIZE][/font]

There are number of things in this mod I couldn't or wouldn't bother to force players to do.[LIST]
[*]One is using birch for the various recipes asking for birch wood. I can't force this so it is up to the player to play along.
[*]Birch root should really be available in summer only, when soil isn't frozen. I can't force this.
[*]Same goes with being near deep water when collecting ore. Realistically the right depth is about 2-5 meters.
[*]Also it would be bad to use animal fiber to make a fishing net, since that would rot faster and be perhaps eaten.
[*]Boneworking recipes are supposed to do once per kill.
[*]Shearing sheep cannot really be modded. Follow the instructions.
[*](Reindeer antler suitable for (commented out) hunting bows should only be available from big male reindeer. I cannot force this because if you butcher "big reindeer carcass" it becomes "small reindeer carcass (largely cut)" when you cancel somewhere near finish. So this also requires some role-playing since now the code allows getting reindeer antler from all reindeer.)
[/LIST]About cultural items, if you feel your character shouldn't know how to make them, don't make them. I welcome players suggesting more cultural item recipes they feel connected to.


[SIZE=4][u]DETAILED DESCRIPTIONS / COMMENTS per recipe[/u][/SIZE]

Note that harvesting bog ore is done on zoomed-out map!


[SIZE=3][u]CRAFTS[/u][/SIZE]

.Split spruce twig.
I noticed the in-game info telling about fences that they were tied with split spruce branches. A sensible and easily available tying equipment available all year-around. For modders: For any mod recipe that previously had {Tying equipment} requirement I recommend assessing if {*cord} 'Cord' would be better: Like bows, arrows, bags, nets, fishing rods etc.
To prevent twigs being used in such recipes.

.Birch root.
Should only be able to harvest when soil isn't frozen, but I can't force it. This is a readily available general tying equipment for drying, traps etc. For modders: For any mod recipe that previously had {Tying equipment} requirement I recommend assessing if {*cord} 'Cord' would be better: Like bows, arrows, bags, nets, fishing rods etc.
To prevent roots being used in such recipes.

.Split trunk.
Combined bowstave and emergency board doable with stone-axe.

.Charcoal.  (50)
This code is adapted from Rain's iron v.0.91. 

.Pitch glue.
Birch pitch glue is actually more complicated to do. The sticky substance should really still be reduced by boiling it for hours. I wanted to reduce menu entries so this will have to do.

.Twisted cord.
Everything that begins "Fibre from" can be made into a cord.

.Twisted and braided rope.
Everything that begins "Fibre from" can be made into a strong rope as well.

.Sauna scoop.

.Wooden tub.
Wooden tub uses split twigs for "hoops". Iron hoops was/would really be used only when iron/steel is cheap.

.Net.
Net is a lot of work. Therefore I added more cord than would weight-wise reasonable. New weight of 10 lbs.

.Punt.

.Willow-bark.
.Alder-bark.
.Fibre from bark. (7) [b]Added missing [patchwise]-tag. [/b]
Two new bark materials for cordage and tanning use. These are much better materials than birch-bark. The oldest known fishing net, the "net of Antrea" from Karelia, was made from willow bark.

.Birch-bark lace.
.Fibre from birch-bark. (5) [b]Added missing [patchwise]-tag. [/b]
Fibre from (outer) birch-bark is now significantly harder to make into good fibre.

.Birch-bark box.

.Birch-bark backpack.
Now you'll have your own lunch-pack! Fill it with dried meat and eat from it. Never again will you have to eat multiple fistfuls to fill your stomach. All containers work this way, but a backback has nice feel to it when travelling. Also widely used historical item in Finland.

.Birch-bark basket.
.Birch-bark cap.
.Birch-bark shoes.
.Birch-bark necklace.

.Dig clay.
To dig clay, dig a pit on a lake or river terrain and stand in it.

.Dig clay from sea-shore.
Clay is now available also in winter, provided you brave the ice-cold water for a few minutes. Do not continue if freezing to death. Don't.

.Clay pot.
Smaller that iron pot.


[SIZE=3][u]FLETCHING[/u][/SIZE]

Fletching is where it all started. I was unhappy to shoot every curly twisted branch I found, so I added more challenge on making arrows.

.Tipped arrow.
.Wooden blunt arrow.
These are the regular vanilla arrows with names that don't conflict the vanilla diy_glossary.txt. Requirements include arrowheads and arrow shafts.

.Fur-fletched arrow.
If lacking for feathers, fletching can be substituted by thin lace of fur, spiralling around the end of the arrow.

.Repair arrow.
One can reuse feathers and cord from broken and existing arrows by attaching them to a shaft with a new arrowhead. Be careful not to accidentally use your best arrows!

.Wooden blunt arrow.
A heavy blunt arrow without fletching. Quality capped at decent.

.Birch Sapling arrow shaft.
.Sapling arrow shaft.
.Split arrow shaft.
Various ways to get good straight shaft material. From birch shoots it's most difficult, easiest from good boards.

.Stone arrowhead.
Quartz or quartzite flakes will have to do since knappable rock is nowhere to be found in Unreal world.


[SIZE=3][u]BONEWORKING[/u][/SIZE]

.Dried sinew fibre.
[i]Image from Rain's Clothing v3, by Kaaven at URW forums[/i]
Harvested backstraps are dried to make sinew fibre. Usable for bowstrings and cordage.

.Bone fishhook.
It takes skill, but will have to do until you make iron ones.

.Reindeer bone. (4) Will spoil!
.Reindeer gut. (3) Will spoil quickly!
.Reindeer backstrap.
.Reindeer antler. (2)
.Elk bone. (4) Will spoil!
.Elk gut. (6) Will spoil quickly!
.Elk backstrap.
.Stag bone. Will spoil!
.Stag gut. (6) Will spoil quickly!
.Stag backstrap.
.Stag antler. (2)
.Bear tooth. (4)
This group on entries is all about harvesting stuff out of carcasses. Because of modding constraints, you need to pick up the carcass you are harvesting from. Often that is impossible with a fresh kill. The trick is to skin and butcher the animal for about 3/4s of the required time. Then it should appear as "* carcass (largely cut)" then it should be light enough to be able to pick up. If you cut too close to finish, the carcass will disappear!

.Bear tooth necklace.
Wear the mark of a skilled hunter!

.Bone spear.
Javelin with upgraded blunt damage. A leg bone is ground diagonally sharp and fitted to a staff.

.Bone arrowhead.

.Antler-tipped blunt arrow.
A blunt arrow that is lighter and bit more powerful than an all wooden one.
[i]Based on reconstruction of iron age arrows from Finland.[/i]

.Fowling arrow.
[i]Image by Atwood at URW forums[/i]
A fowling arrow is designed especially against birds. With a forked bone or iron arrowhead, it doesn't penetrate the whole bird as easily. It severs wings and gets stuck, disturbing flight. Missed arrows are also easy to recover. In-game the only real difference compared to regular arrows is that point damage is significantly lower than with normal arrows.
[i]Based on reconstruction of iron age arrows from Finland.[/i]

.Bone arrowhead.
.Forked bone arrowhead.
Bone for arrowheads is available only from elks and reindeer (to save menu space).

.Fishing rod.
Fishhooks required. Those are made from either antler or iron.


[SIZE=2][u]COOKERY with BONEWORKING[/u][/SIZE]		

.Roasted marrowbone.
.Boiled meat and marrowbone.
.Dry meat soup.

.Blood sausage. (3)
.Blood cake. (4)
These are usually boiled, but I wanted them to exist outside the pot. Thus roasting is used.

.Washed gut.
Surely guts have to be thoroughly washed inside out before eating. Peculiarly enough they can be eaten raw!

.Reindeer blood.
.Elk blood.
.Stag blood.
Harvested in same fashion as bones and guts. Blood can only be collected into pots and it requires also a fire because of modding constraints.


[SIZE=3][u]HIDEWORKING[/u][/SIZE]

Kotas now need kota covers! They come in three different materials: fur, leather and wool. Kota covers can also made into clothes of their respective material. And fur covers can be wrapped in when sleeping! It isn't possible to have two different recipes for kotas, so kotas can now only be made from kota covers. Unfortunately I had to sacrifice the vanilla way of doing them.

.Kota cover from single pelt.
Only fast way of obtaining kota covers.

.Kota cover from hide pieces.
.Kota cover of leather.
.Kota cover of wool.
Many spare clothes and furs can be used for making kota covers as well. It's a lot of sewing so these take several hours.

.Birch inner bark.
Usable for bark-water solution, especially when lacking bushes for obtaining willow bark.

.De-hair fur cover.
If in need of leather, fur covers can be de-haired with this recipe.

.Mild tanning of skin cover.
Soaking in tanning solution needs to be started carefully. Else the surface of the skin tans completely and prevents tanning agents from entering the skin.

.Final tanning of skin cover.
Final tanning by soaking in tanning solution. Fat is an option (that doesn't really do anything).

.Rinse tanned skin cover.
.Soften leather cover.
The final steps needed to make the skin into leather.

.Bark-water.
Tanning solution made by boiling bark. Only alder, willow and birch inner bark are usable. English language is actually a bit confusing here. Birch-bark shouldn't be "bark" at all, and in Finnish it has a different word: "tuohi", whereas the inner bark is called: "(koivun=birch)parkki". This recipe is found in cookery_Buoidda's hideworking.txt


[SIZE=3][u]BOWYING[/u][/SIZE]

.Braided bowstring.
All those fibers can be used to make a bowstring.

.Rawhide bowstring.
Cured hide produces slightly better quality bowstrings with less time. There's a curing time for a finished string.

.Spruce bow.
Spruce branches have compression wood in their undersides and kind of work like natural northern bows, where pine compression wood is used. Perfect for a makeshift bow in a survival situation. This bow is craftable with only a knife.

.Birch shortbow.
Game doesn't allow (yet) for wood species requirements, but I have left some descriptions with the word 'birch' in them to bug the players' conscience if they don't use birch.

.Northern staff-bow.
A long straight two-wood bow that doubles as a ski stick. The bulky tips impair its shooting qualities, but nonetheless is useful to be able to shoot while skiing. Based on a number of historical accounts and the only surviving Saami bow at Örbyhus Castle in Sweden.

[i].Sinew-backed antler bow. "Hunting bow"
This recipe is commented out in "diy_r_Buoidda's bowying.txt". It also requires boneworking mod.
This bow is craftable with a knife (and stone-axe to harvest antler) without the need for a proper axe. Anachronism: This type of bow probably hasn't been used in Finland during iron age. But it's [u]Unreal[/u] World![/i]

.Two-wood longbow.
A Longbow with similar construction than the Northern bow, but missing recurve ears and longbow shape instead.
There are a number of archeological findings about this type of bow in Norway. Game-stat-wise identical to longbow, though harder to make.

.Hardwood Longbow.
Longbow can currently be only from the occasional "hard staff" one finds from NPCs or in villages.

.Recurved northern bow.
Recurved two-wood bow. Based on the widely used bow-type in Northern Eurasia (incl. Finland and Skandinavia). The two-wood bow was praised for its power in Norse sagas. This is now the most powerful bow in URW. Accuracy is also imporved to shortbow level, so it is a worthy competitor for the famous longbow. Weight is 3.2 pounds, to have the inventory display it as "4 lbs" and thus be able to distinguish previous/vanilla bows from these upgraded ones.

.Compression pine belly.
Compression wood grows on underside of curved coniferous trees. There are no such trees in URW, so any trunk lying on pine mire terrain will fullfill the requirement. Personally I started looking for already fallen trees, since they are harder to find than standing trees. This way you get a feel of looking for a suitable tree.

.Birch backing.
.Recurve ear.
.Dried perch-skin.

[i].Antler strip.
This recipe is commented out in "diy_r_Buoidda's bowying.txt". It also requires boneworking mod.
Made from big male reindeer antlers.[/i]

.Retiller Northern bow.
Use this recipe to update any vanilla/previous northern bows to .Recurved northern bow. stats. It uses *common* skill with %100% bonus, so it should always produce same quality as the raw material bow which will be removed. If you want to upgrade a masterwork bow, you need to manually assign a skill that is at least 70, to make achieving masterwork crafts possible. (Common skill is always 50 in calculations.) 

.Big spruce branch.
Used to make a spruce bow.


[SIZE=3][u]IRONWORKING: TOOLMAKING, IRONWORKING AND FORGING[/u][/SIZE]

Ironworking is laborious and demanding work. Expect to start early in the morning, well fed and in good condition. Working times wary, but are often quite long. Sometimes multiple retries are needed to begin work. You might want to shorten them if encountered and it annoys you. For realism, it's still too quick and many steps and tools are left out. Recipes can have only 8 requirements.

[i]Timbercraft is used in ironworking menu recipes and for smithing axeheads and swordblades. It reflects the strengh and endurance needed. Carpentry skill is used for finer smithing and attaching handles.

If you want to make all the masterwork items yourself, you need to have hideworking, timbercraft and carpentry skills at least 70, preferably more. You don't necessarily need to have masterwork tools to make masterwork items, but it certainly improves the odds. Also note that the raw material quality limits the outcome, so always use perfect material when trying to make masterwork items. This is described in "news.txt" under "impact of raw material and tool quality/usefulness" in the URW game folder.[/i]


.Axe haft.
Tools require premanufactured hafts.

[SIZE=2]TOOLMAKING[/SIZE]

.Small knife.
.Broad knife.
.Handaxe.
.Carving axe.
.Woodsman's axe.
.Broad axe.
.Splitting axe.
.Sickle.
.Shovel.
These require smithing for the blades and iron heads.

.Stone hammer.
[i]Image by Kaaven at URW forums[/i]
Stone hammer is the first thing a smith should make.

.Iron hammer.
[i]Image by Kaaven at URW forums[/i]
Iron hammer is now only required for the hardest of hammerings.

.Bellows.
[i]Image by Atwood at URW forums[/i]
Smith's bellows are big and worked with feet.

.Grind an anvil stone.
[i]Image by Kaaven at URW forums[/i]
Currently these are only available from barren terrain where stones would be easily visible, such as Cliffs, Mountains and Lichenous forests.
Should anyone have a better idea, please let me know.

.Grind a whetstone.
[i]Original image by Kaaven at URW forums, modified[/i]
Currently these are only available from barren terrain where stones would be easily visible, such as Cliffs, Mountains and Lichenous forests.

.Dip net.
This is a tool that ore used to be scooped from the bottom of lakes, either onto raft or ice.

[SIZE=2]IRONWORKING[/SIZE]

.Scoop lake ore.
[i]Original image by Kaaven at URW forums, modified[/i]
Lake ore is found abundantly in lakes in depths of 2-5 meters. One needs specialized tools for lifting it on a raft or on ice.

.Harvest bog ore.
[i]Original image by Kaaven at URW forums, modified[/i]			
Ore can be found on mires that are next to mountain tiles. This action needs to be performed on zoomed-out map.

.Roast ore. (8)
Ore needs to be dried (not featured) and roasted to remove any organic residue which would maybe have negative effect on smelted iron. The recipe checks if you have piled the ore and firewood. You need to light the stack on fire yourself [i]afterwards[/i] for added ambience. Possible exploit: if you forget to light it, you can still collect roasted ore and reuse the firewood. Don't cheat or your iron will turn to ash!

.Smelt ore into iron.
[i]Original image by Kaaven at URW forums[/i]
Fresh ore cannot be used. The bloomery smelting is a highly inefficient process and it produces iron with variety of carbon contents. Think of the crude and inferior blooms as having very low carbon content. Decent and fine quality blooms have progressively higher carbon content.

.Wrought iron billet.
Slag and impurities are driven out of the iron bloom by hammering. Result is soft and malleable iron. It is also possible to recycle iron items with this, with loss of some material. Again, think of the decent billets as having some carbon content and fine quality enough to be mild steel.

It is also possible to improve a batch of billets, given enough skill and at least one billet is of better quality: 1 decent and 3 inferior billets has given 3 decent billets. I have never managed to improve a batch of only inferior billets.

.Steel billet.
Here the magic happens. Even the crudest piece of iron can be improved into something that can hold an edge. The piece is sealed with high-carbon mixture and heated for a long time, to make it absorb carbon and become steel. Only one piece can be handled at a time. This is because really this should be done for days, even weeks. If a sword needs much steel, heating single billets per day translates to many billets being heated for many days.

.Salvage iron from an axe.
.Salvage steel from a sword.
.Salvage steel from a scimitar.
I wanted to be able to recycle valuable metal from not so successful crafting attempts. (And to get to forge in winter without access to easy clay.)
In these the temper of the weapon is broken by heating and metal made malleable again. Then pieces can be forged off. For realism, I recommend leaving a part of the weapon unsalvaged and then discarding it. Not all of that weight is metal.

.Build a simple stone forge.
It is not really needed to have clay (hard to find in winter) for a usable forge.

.Make a bloomery furnace.
Made of stone and clay. With the added insulation of clay, sand and dung, a furnace can reach higher temperatures and refine ore into iron.  "Iron cabin" (Finnish "Rautahytti") is built outside. If you put in inside your house, don't light a fire on it!

.Assign a fireplace as a forge.
By standing next to a fireplace, you can now create an invisible "forge token", which is then 'p'ushed to the fireplace. Now smithing recipes accept the fireplace as a forge as well!

[SIZE=2]FORGING[/SIZE]

.Iron pot.
Needs malleable iron, not steel. Plate-like things are easier to hammer when iron is soft, and could be case-hardened later, if necessary.

.Iron arrowhead.  (10)
.Iron broadhead.  (5)
.Forked iron arrowhead. (5)
.Iron fishhook.  (5)
.Iron shovel blade.
.Iron small knife blade.
.Iron large knife blade.
.Iron small axehead.
.Iron large axehead.
.Iron sickle blade.
.Iron spearhead.
.Iron pommel.
All of these have iron in their name to be able to recycle them into wrought iron billets. Some accept iron billets, some demand steel. Large knive blades, axeheads and spearhead demand additional billets quality of which is not taken into account. A good way to spend those inferior billets.

.Shortsword blade.
Swordsmithing is made time-consuming, but they also have high value in-game. A shortsword blade takes 5 pieces of steel, which weighs more than the finished sword. My reasoning is that a lot of steel is lost to oxidization when the steel is laminated over and over again. (Flakes of oxidized iron fall off when hammering.) Though I've understood that lake and mire ore (limonite) is self-fluxing which should reduce oxidization and make forge-welding considerably easier than with modern steels.

.Iron battleaxe-head.
Battleaxe-head needs more steel than tool axes.

[SIZE=2]WEAPONS[/SIZE]

.Northern knife. Added more requirements because they are so valuable.
.Northern spear.
.Spear.
.Shortsword.
.Battleaxe.
.Broadhead arrow.

.Short spear.
Shorter spear is easier to throw than a regular one. Also works well with a shield.

.Knife handle pieces.
Needed for northern knife.