# Skript-Blood
[Skript] Blood XP v1.1

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
- Blood collection cooldown

Setup:

In the skript file there is a config section.
- Set "world" to your world's name
- Set "bloodduration" or leave it default for expiration time
- Set "bloodradius" or leave it default for spill blood area
- Set "msgprefix" to what you would like all messages sent by this plugin to show up as in chat
  - Example that its currently set to: "[JC] victim's blood just spilled!" "[JC]" being the prefix.
- Set "cooldown" or leave it default


Redeemable rewards can be configured at like 105 to 130 if you know what you are doing.

Commands:

  Player Commands:
   - /blood : Displays a list of possible commands within /blood. Also displays current amount of Blood XP
   - /blood redeem : View list of redeemable items, and also redeem them (/blood redeem [redeemable option]
   - /blood leaderboard : View top 10 players with the most Blood XP
  
  Admin Commands:
   - /blood : Displays a list of possible admin and player commands.
   - /blood spawnblood : Simulates a blood spill for testing or other purposes.
   - /blood setxp [player] [amount] : Sets amount of blood XP a player has.
   - /blood clearxp [player] : Sets amount of blood XP a player has to 0.
  
V1.1 Changelog:
- Removed need for enderdragon
- Removed physical dragon breath, it goes directly into the blood XP
+ Added a cooldown option so players don't spam right click bottles

Coming in future updates:
- Usable in multiple worlds
- NPC quests redeemable with blood
- Other redeemable rewards, possibly pets (Using HPET plugin) and custom enchants

