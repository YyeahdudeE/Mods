Stardew Valley Reimagined

author: DaisyNiko
version: 1.4.1

https://www.nexusmods.com/stardewvalley/mods/4119


----------------------------------------


REQUIREMENTS


* SMAPI 2.11 (required)
https://www.nexusmods.com/stardewvalley/mods/2400

* Content Patcher 1.8 (required)
https://www.nexusmods.com/stardewvalley/mods/1915

* Winter Grass (recommended)
https://www.nexusmods.com/stardewvalley/mods/1601

* Entoarox Framework (recommended)
https://www.nexusmods.com/stardewvalley/mods/2269


----------------------------------------


INSTALLATION


1. Download and install SMAPI and Content Patcher.
2. Add the "[CP] Stardew Valley Reimagined" folder to Stardew Valley/Mods.
3. Run the game with SMAPI.


----------------------------------------


if you want to use the mod with an existing save...


1. Install this mod as normal.
2. Install the Entoarox Framework.
3. Run the game and load your save.
4. Click on the SMAPI console window and type the following commands, pressing Enter after each one:

world_clear backwoods trees
world_clear mountain trees
world_clear railroad trees
world_clear desert trees
world_clear town trees
world_clear beach trees
world_clear woods trees
world_clear forest trees
world_clear forest debris
world_bushreset

5. You will have to wait however many in-game days for the trees to grow back in their new places.


----------------------------------------


CONFIGURATION


Run the game once with SMAPI to generate a config.json file in this mod's folder. Right-click the file and open in Notepad to make changes.


"MapsToignore"

> This is where you can list all the maps you DON'T want.
> If you want them all, leave it blank.
> If you want to ignore multiple maps, separate them with a comma.


"IgnoreFestivals"

> either "true" or "false"
> Set to true if you just want to use the vanilla festival maps.


example:

"MapsToIgnore": "BusStop, Woods, Town",
"IgnoreFestivals": "true"


----------------------------------------


COMPATIBILITY NOTES


> Download the optional Compatibility Patches folder from the Stardew Valley Reimagined Nexus page for conflicting mods.

> For Extended Minecart users, make sure you're using the ALTERNATE desert minecart location (select it in the Extended Minecart mod's config file).

> Not compatible with Stardew Valley Expanded.


----------------------------------------


FIXES FOR COMMON ISSUES


> If you have bushes and trees in weird places, follow the steps listed above to use the mod with a new save.

> If you exit a map and are warped to the wrong place, you've likely got a conflicting mod. Look at your SMAPI console -- it will tell you which mods are conflicting. Then delete one of them. Also check for a patch in this mod's optional Compatibility Patches download.

> Known issue: NPCs doing the egg hunt with you during the Egg Festival will stop walking around as soon as they run into something. Everything works fine. It just looks weird. If it bothers you, set "IgnoreFestivals" to true in the config.json.


----------------------------------------


CHANGES IN LEGENDARY FISH LOCATIONS

> The Legend can be found by fishing from the small area down the ladder next to the waterfall at the mountain lake.

> The Angler can be found by fishing at the very top of the river in the town, right at the mouth of the cave where the river comes out.


----------------------------------------


CREDITS


* EemieStardew for the flowers
https://www.nexusmods.com/stardewvalley/users/34984615

* Maleha for the waterfalls
https://community.playstarbound.com/members/maleha.626319/

* FawnGlade for orange fall tilesheets for Eemie's recolour
https://www.nexusmods.com/stardewvalley/users/71631533

* Various different people for translations. Please see the "Permissions and credits" section on the Nexus page for their info.


----------------------------------------

That's it. Enjoy. xx


