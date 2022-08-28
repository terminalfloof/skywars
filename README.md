# skywars
oh hi this is an OUTDATED minecraft education edition map made by a group of idiots


download the map using the releases shown on the right side

if you want to get the most recent version (commits), you can download the entire repo as a ZIP,
extract all,
take the inner folder out of the extracted folder
send the folder you just took out to a compressed ZIP. you can do this by right clicking, finding "Send to...", hovering and clicking ZIP.
After you zip it, be sure to change the .zip to .mcworld

if you know your git stuff
you can clone the git repo into the worlds folder
you can create a new world, then just copy the name. you can delete the world afterwards.
after you do this, if you want to update the world, you can git pull. this will overwrite your world, however.


## essential commands

`/tp (user) -5 2 8` reset person's playing status and teleport them back to spawn)

`/setblock 4 2 4 concrete 0` change game status from "playing" to "not playing"

`/gamerule pvp true` allow people to sumo with bows B)

`/tp 0 100 0` go to spawn

`/tp 0 4 0` go to commands area (don't break pls)

`/setblock 7 1 7 redstone_block` refill chests ;D

`/setblock 10 1 9 redstone_block` get the glass cages up

`/setblock 10 2 9 redstone_block` remove the glass cages

`/setblock 5 1 15 redstone_block` start the game

`/setblock -10 1 -21 redstone_block` start a random event

`/scoreboard players set @p playing 2` turn off resistance (if not ingame)
change @p to the playername/selector

## settings

`OVERRIDE PROXY`
Start the game no matter what. Even if there's only one player opting in.
Use wisely.

`EVENT MESSAGES`
If you're not ingame, you can toggle the event messages if they get annoying.

`Who's opted in?`
This should be self-explanatory.

`FIX 1-P PROXY BUG`
Is your game:
- Stuck on "game in progress"?
- Nobody's ingame, but the game won't allow you to start?
- Only one player's still ingame?
- One person doesn't want to respawn?
You can press this button to prematurely end the game.
**NOTE: PRESSING THIS BUTTON AFTER A GAME HAS ALREADY ENDED WILL CAUSE THE LAST WINNER TO GET ANOTHER WIN.**

`sumo`
go to sumo platform lol
