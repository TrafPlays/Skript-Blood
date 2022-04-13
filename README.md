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
- 10% chance of a player to "spill blood" in a specific world, or all worlds.
- Blood can be collected in empty glass bottle.
- Blood can be configured a time to expire, and a spill radius. Default 3x3 radius, ~ 3 seconds to expire.
- Leaderboard to show off who has the most blood.
- Redemption shop to trade Blood XP for rewards
- Blood collection cooldown
- Mobs can also spill blood

Setup:

In the skript file there is a config section.
- Set "world" to your world's name
- Set "bloodduration" or leave it default for expiration time
- Set "bloodradius" or leave it default for spill blood area
- Set "msgprefix" to what you would like all messages sent by this plugin to show up as in chat
  - Example that its currently set to: "[JC] victim's blood just spilled!" "[JC]" being the prefix.
- Set "cooldown" to determine how long a player can collect blood at a time.
- Set "animals" to true of false if you would want mobs to also spill blood.


Redeemable rewards can be configured at line 171 to 226 if you know what you are doing.

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


v1.2 Changelog:
+ Patched mobs spilling blood, and made it an option to enable in configs
+ Added option to allow blood to spill in ALL worlds or the defined world
+ Added more reward examples. Requires LuckPerms, HPET, and Essentials

V1.1 Changelog:
- Removed need for enderdragon
- Removed physical dragon breath, it goes directly into the blood XP
+ Added a cooldown option so players don't spam right click bottles

Coming in future updates:
- Usable in multiple worlds
- NPC quests redeemable with blood
- Other redeemable rewards and custom enchants

