# Overlook

A Minecraft modpack that plays like a top-down action RPG. You look down on your hero, click to move,
and fight with class skills on Q W E R, in a world full of dungeons, towers and bosses to take them into.

For **Minecraft Java 1.21.1** with **NeoForge 21.1.258**.

## Install

You need [Prism Launcher](https://prismlauncher.org/) and a Minecraft Java account.

1. Download **[Overlook-Prism.zip](https://github.com/Mikestove/overlook-pack/releases/latest/download/Overlook-Prism.zip)**.
   (Not the green "Code" button. That zip is only the file list below, and Prism can't use it.)
2. In Prism: **Add Instance**, then **Import**, then **Browse**, pick the file, and click **OK**.
   You can also paste the download link into the Import box.
3. Press **Play**. The first start downloads every mod, which takes a few minutes. After that,
   the pack updates itself each time you press Play, fetching only what changed.

The instance asks for up to 6 GB of memory; change it in the instance's settings if needed.

**If Play stops with "Pre-Launch command failed"** and the log line above it begins with `-jar`, Prism has
no Java to run the pack's updater with. In Prism open **Settings**, then **Java**, and tick
**Auto-detect Java version** and **Auto-download Mojang Java** (or install Java 21 yourself and press
**Auto-detect** there). Then press Play again.

## How it plays

You begin in **Haven**, a walled village on an island, with a quest already in your journal. The people
of the village have gold marks over their heads: **!** means they have work for you, **?** means they are
waiting to hear how it went. Right click them to talk. The Elder, the Trainer and the Smith walk you through
your first steps. Down the south avenue are the traders: the Armourer and the Weaponsmith at the first two
market stalls (new stock every morning), the Alchemist for healing draughts, the Provisioner for potions and
food, and the Smith, who upgrades and mends gear and breaks up what you do not want. All of them buy gear.

The **Waygate** north of the square leads to the zones. Each is its own island with a level range and a
scout waiting by the gate with that island's quests: thin the enemy, find the treasure caches (a pillar of
gold light marks each one), kill the two named elites in their lairs, and then the boss in its arena at the
far end. Tell the Captain in Haven, and the next island opens:

| Zone | Levels | Boss |
|---|---|---|
| Greenhollow | 1 to 4 | Old Tusk |
| Whisperwood | 5 to 9 | The Broodmother |
| Sunscar Ruins | 10 to 15 | The Sand King |
| Frostfang Pass | 16 to 22 | The Frost Warden |
| Emberdeep | 23 to 30 | The Ashlord |

The realm has its own creatures, three kinds to a zone and a boss at the end of each road: Rotwalkers,
Tusklings and Strawmen in Greenhollow under **Old Tusk**; Webspinners, Boneguards and Wisp Hags in the
Whisperwood under **the Broodmother**; Sandwalkers, Scarabs and Dune Raiders in Sunscar under **the Sand
King**; Frostbound, Rime Wolves and Ice Wraiths in Frostfang under **the Frost Warden**; Ashen, Cinder
Hounds and Flame Callers in Emberdeep under **the Ashlord**. Some come at you, some leap, some hang back
and throw things: step out of the way.

The islands grow as you go: each zone is larger than the last, with more bands of enemies along its
road. Every zone also has a **dungeon**. Look for a dark stone with a burning doorway on it, standing
between four lit pillars a little way off the road; right click it to go down. Inside are rooms of the
zone's toughest enemies, treasure rooms at the dead ends, and the dungeon's master in the last hall, who
drops far more than anything on the island above. A stone in the first room and one in the master's hall
lead back out.

Bosses mark the ground before they strike, each in its own pattern: get out of the circles. If you fall
you wake in Haven with everything you were carrying, and **H** recalls you there from anywhere, once a
minute. The gate also leads to **The Wilds**, the ordinary open Minecraft world with all its dungeons, for
when you want no walls.

The host of the world sets the **difficulty** for each player from the pause menu (Esc, then Difficulty):
*Little Hero* for small children (enemies barely hurt and fall fast, and wounds heal by themselves), *Hero*,
or *Veteran*. Players on different settings share the same world. On a server, operators are the hosts, and
`/overlook difficulty <player> <little|normal|veteran>` does the same from the console.

Playing together: at a gate, whoever chooses the place takes every hero standing by the gate along (untick
the box on the gate's map to go alone), and every player shows on everyone's minimap and world map wherever
they are. On a server of your own, set `everyone_tracks_everyone = true` in `config/xaero/lib/common.cfg`
for the map part. Each other hero's name, level and health show down the left of the screen, under the
minimap, with the place they are in if it is not yours. Also: everyone near a kill gets the experience and silver and their own drops for their own
class, heroes cannot hurt each other, camps hold more enemies for each extra hero nearby, and elites and bosses
met by a party are sturdier.

When you join a world you choose a class and are handed its weapon:

- **Vanguard**: a greatsword. Tough, and hits everything around.
- **Arcanist**: a staff. Fragile, with fire, ice and the biggest hits.
- **Ranger**: a longbow. Quick, and fights from far away.

| | |
|---|---|
| Right click, or hold | walk to the cursor; on a person, a gate or a cache: walk up and use it |
| Left click | basic attack |
| Q, W, E | skills |
| R | ultimate |
| Space | dodge toward the cursor |
| F | drink a Healing Draught |
| H | recall to Haven |
| K | skills: spend points, pick upgrades, switch class |
| J | quest journal |
| I or P | your hero: what you wear, your numbers, your bag |
| Mouse wheel | zoom |
| [ and ], or drag with the middle button | turn the view |
| F6 | ordinary first-person Minecraft, and back |

A gold pointer at your hero's feet shows the way to your current quest, and the quest list sits at the
right of the screen.

**Gear** drops from enemies (elites and bosses always drop some), sits in caches and comes from quests.
Every piece has an item level and a rarity (common, uncommon, rare, epic, legendary), shown by the colour
of its name and of the light over it on the ground, and rolls its own bonuses: damage, health, critical
chance, faster cooldowns, energy. There are seven slots: weapon, head, chest, legs, feet, ring and amulet.
Press I or P for your hero's own inventory and right click a piece to wear it.

Armour is made for one class, and each class has its own look in five tiers, one for each zone: the
Vanguard's plate, the Arcanist's hooded robes, the Ranger's leathers. Weapons change with their tier too.
Enemies also drop **shards** (one kind per zone). Take them to Dorran the Smith and choose "Upgrade my
gear": each upgrade, up to +5, adds 10% to a piece's numbers for a few shards and some silver.

Armour and weapons are shaped as well as coloured: pauldrons, crests and horns on the Vanguard's plate, a
hood, mantle and skirts on the Arcanist, a cowl, quiver and cloak on the Ranger, more with every tier.

Roofs lift away when you walk indoors. Out of doors nothing is hidden: a hero or an enemy behind a tree or
a wall shows through it in outline, gold for you and red for them.

Weapons and armour wear with use, and more when you fall; the bar under a piece shows its condition. A
broken piece adds nothing until the Smith mends it ("Mend all my gear"). He also breaks old gear up for
shards: finer pieces give more. Every piece sits on the colour of its rarity: grey, green, blue, purple,
gold.

Kills and quests give experience, up to level 30. Every level gives two skill points. Each of the four
skills on Q W E R can be raised to level 10, and at skill level 4, 7 and 10 you choose one of several
upgrades that change how the skill works: wider, faster, burning, stunning, more arrows, a second
explosion. Points can be taken back and spent again at any time. Each class keeps its own level and skills,
so you can switch.

Outside the islands (in The Wilds), put the weapon away and it is ordinary Minecraft seen from above:
W A S D walk, and the mouse mines, builds and opens whatever the cursor is on. Roofs, cave ceilings and
treetops are cut away whenever they would hide your hero.

## What's inside

**The game itself:** Overlook (the top-down view, classes, skills, gear, quests, the village and the zones)

**Places to fight through:** When Dungeons Arise, YUNG's Better Dungeons, Mineshafts, Strongholds, Desert
Temples, Jungle Temples, Nether Fortresses, Ocean Monuments and Witch Huts, Towns and Towers

**Things to fight:** L_Ender's Cataclysm (bosses), Mowzie's Mobs

**Things to find:** Artifacts, Immersive Armors, Lootr (every player gets their own loot from a chest)

**The world:** Biomes O' Plenty, Nullscape, Traveler's Titles, AmbientSounds

**Getting around:** Waystones, Xaero's Minimap and World Map, Explorer's Compass, Nature's Compass,
Sophisticated Backpacks

**Help and comfort:** JEI (recipes), AppleSkin, Mouse Tweaks, Farmer's Delight, FallingTree

**Looks:** Iris with Complementary Reimagined shaders on by default (BSL is included too; press O to choose)

**Smoother play:** Sodium, Lithium, FerriteCore, ModernFix

## Good to know

- Mods that take over the camera are left out on purpose: they fight with the top-down view.
- The shader mod's "reload" and "toggle" keys start unbound, because R and K are used by the game here.
- The pack is young. The classes have been tested on their own; playing through the dungeons and bosses
  with them has not been balanced yet.
