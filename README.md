# Skript-Blood
[Skript] Blood XP v1.0

Requirements:
- Skript
- MC version 1.9+. Recommended 1.16+

Optional Requirements:
- Essentials
- Citizens NPC (NPC Quest Coming Soon!)

This skript was written to add a little spice to PvP in Minecraft!

Features:
- 10% chance of a player to "spill blood" in a specific world.
- Blood can be collected in empty glass bottle.
- Blood can be configured a time to expire, and a spill radius. Default 3x3 radius, ~ 3 seconds to expire.
- Leaderboard to show off who has the most blood.
- Redemption shop to trade Blood XP for rewards

Setup:

In the skript file there is a config section.
- Set "world" to your world's name
- Set "bloodduration" or leave it default for expiration time
- Set "bloodradius" or leave it default for spill blood area
- Set msgprefix to what you would like all messages sent by this plugin to show up as in chat
  - Example that its currently set to: "[JC] victim's blood just spilled!" "[JC]" being the prefix.

After setting up those, find a spot in the world and make it inaccessible to regular players, stand still and type /blood spawndragon, as a dragon is required for this plugin to work. The dragon would not move and would not make a sound. Dragon must be in the same world that the blood will be spilling in.

Redeemable rewards can be configured at like 105 to 130 if you know what you are doing.

Commands:

  Player Commands:
   - /blood : Displays a list of possible commands within /blood. Also displays current amount of Blood XP
   - /blood redeem : View list of redeemable items, and also redeem them (/blood redeem [redeemable option]
   - /blood leaderboard : View top 10 players with the most Blood XP
  
  Admin Commands:
   - /blood : Displays a list of possible admin and player commands.
   - /blood setdragon : Sets a non-movable and silent dragon. (Required for the "Blood")
   - /blood spawnblood : Simulates a blood spill for testing or other purposes.
   - /blood respawndragon : In the event the dragon despawns, this would respawn it to its last location. Must be in same world the dragon should be!
   - /blood setxp [player] : Sets amount of blood XP a player has.
   - /blood clearxp [player] : Sets amount of blood XP a player has to 0.
  

Coming in future updates:
- Usable in multiple worlds
- NPC quests redeemable with blood
- Other redeemable rewards, possibly pets (Using HPET plugin) and custom enchants

