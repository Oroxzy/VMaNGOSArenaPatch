# VMaNGOS Arena Patch
VMaNGOS Arena Patch Client Side (WoW Client 1.12.1 mpq file).

Features:
  - Arena Watcher NPC in the arena: speak to him to start the arena immediately (if everyone does it).
  - Solo & Group queue for 1v1, 2v2, 3v3 and 5v5
  - Cross Faction support (Horde can team up with Alliance and vice versa).
  - Spectator support.
  - Disabled Item switching during the battle (even out of combat) except Weapons of course (Adjustable in cfg).
  - Max patch for allowed gear can be set in cfg.
  - Max item level allowed can be set in cfg.
  - Disabled custom items.
  - Horde and Alliance can chat with each other if they're in the same arena team.
  - Disabled most Consumables and Buffs, adjustable in the "arena_disabled_spells" table.
  - Damage & healing done on Scoreboard added, this feature is new and not available in Classic for BGs. Also it does count Pet damage too and not count over damage (So if you kill a Player with 4k hp with a 6k Shadowbolt it adds only 4k damage)
  - Pet commands are disabled until door opens to avoid attacking your enemies before the battle starts.
  - Player Stash (UterusOne feature). If enabled in cfg, the chest spawns until the door opens to change gear and talents.
   
 Todo:
  - Fix Scoreboard for same Faction games (maybe edit */Interface/FrameXML/WorldStateFrame.lua*). (edit: not possible i think)
  
 Try it:
  - Goto (http://uterusone.net) and create your Account.

All 3 TBC Arenas & Dalaran Arena from WotLK available to play as 1v1, 2v2, 3v3, 5v5:
![TBC Arena](https://i.imgur.com/p5IVD1l.jpg)

Damage & healing done:
![Damage & healing done](https://i.imgur.com/eL6kHXH.png)

Remaining players:
![Alive players left](https://i.imgur.com/5zCC4aA.png)
