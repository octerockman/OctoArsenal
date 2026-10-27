# Octo Arsenal 0.5.27

Historical steel weapons, shields and individual weapon progression for Valheim.
By **OctoDad / Studio Bascinet**.

![Octo Arsenal — historical weapons and progression](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Cover-1920x1080.png)

## Equipment

Ten equipment lines: Steel Dane Axe, Steel Sword, Steel Winged Spear, Steel Bearded
Axe, Steel Berserker Axes, Norse Bow, Viking Round Shield, Kite Shield, Steel
Longsword and Armour Fang. Upgrade appearances and selectable shield styles are
included. The Steel Longsword has four appearances at qualities 1, 4, 7 and 10.

**Armour Fang** is a one-handed mace with a blunt hammer face and a piercing pick
face. Press **Y** while it is equipped to turn it around. Pick mode mines suitable
ore as its quality improves. Both faces share durability, quality and quest progress.

## Quench the steel in the blood of your foes

Craft the bow at **Workbench level 4** and the other equipment at **Forge level 4**.
Normal upgrades through level 10 require materials and a completed quenching
quest. Trophy requirements have been removed. Each physical weapon keeps its own
quest progress, so another newly crafted weapon starts separately.

An enemy must take damage from a weapon and then die to grant progress. The weapon
does not have to land the final hit. Shields count eligible enemies the player
helped damage while that physical shield is equipped when death credit arrives;
blocking is not required. Mining, misses, PvP and tamed allies grant no progress.

The next-quality quest follows this ladder:

| Target quality | Enemies required |
|---|---|
| 2 | 10 wolves and 2 cultists |
| 3 | 15 wolves and 2 cultists |
| 4 | 12 fulings and 1 fuling berserker |
| 5 | 18 fulings and 2 fuling shamans |
| 6 | 10 seekers and 1 seeker soldier |
| 7 | 14 seekers and 2 seeker soldiers |
| 8 | 12 charred foes and 2 asksvin |
| 9 | 18 charred foes and 1 morgen |
| 10 | 20 eligible Deep North foes |
| 11–30 | Eligible Ashlands / Deep North foes, rising from 20 at 11 to 50 at 30 |
| 31+ | 50 eligible Ashlands / Deep North foes per new quality |

Above level 10, completed quests and **battle idols** are both required. Each
successful level retains the existing 5% compounded growth in damage, block armor
and durability. A failed or unchanged idol attempt retains completed quest credit.
The manual download includes the full material costs and quenching notes.

## New weapon stats

Values below are the configured endpoints at qualities **1 → 10**, before player
skill and other effects. Armour Fang's two modes use the same item.

| Stat | Steel Longsword | Armour Fang: hammer | Armour Fang: pick |
|---|---|---|---|
| Damage | 145 → 338 slash | 95 → 260 blunt | 85 → 235 pierce |
| Normal attack stamina | 18 | 16 | 18 |
| Secondary attack stamina | 35 | 28 | 28 |
| Block armor | 50 → 78 | 40 → 60 | 40 → 60 |
| Parry bonus | 2× → 5× | 2× / 3× / 4× at quality 1 / 5 / 10 | Same as hammer |
| Knockback | 50 → 55 | 75 | 20 |
| Backstab | 3× | 3× | 3× |
| Durability | 250 → 1000 | 250 → 1000 | Shared with hammer |
| Weight | 3.5 | 2.5 | 2.5 |
| Movement penalty | −5% → −1% | −5% | −5% |

## Controls

| Key / action | Function |
|---|---|
| **N** | Show or hide the smaller quest tracker to the right of the hotbar |
| **Y** | Switch the equipped Armour Fang between hammer and pick |
| **Alt + 1 / 2 / 3** | Access quiver or spear-carrier slots when those accessories are active |

Hiding the tracker does not stop quest progress. Locked upgrades display
**Steel needs Quenching.** Hammer/pick switching is disabled during attacks,
blocking, dodging and input menus. N and Y can be rebound in the main configuration.

The approved model positions, rotations and sizes are built in. The temporary
fitting editor has been removed and F9 is no longer used.

## Requirements and optional accessories

- **Valheim with BepInEx 5**. This build targets the installed Valheim 1.0.20 APIs.
- Install the **same Octo Arsenal version on all clients and the dedicated server**.
- A compatible **OctoPack** is optional for the backpack quiver and three-spear
  carrier. OctoPack 1.6.47 is the API version checked by the compatibility tests.
  Without a compatible OctoPack, the weapons remain available.
- **Better Archery** is optional. Its enabled recovery, crouch and nocked-arrow
  features take precedence to prevent duplicate effects.
- Remove the separate **OctoPack_addon_Quiver** plugin before using this mod;
  its functionality overlaps the included quiver.

The quiver and carrier are crafted at a workbench. Put the accessory in a
compatible backpack and right-click to equip it. Their shortcut-panel headings
can be dragged, and panel offsets are saved in the main configuration.

## Install or update

Use your mod manager, or install manually:

1. Close Valheim.
2. Install BepInEx 5 if it is not already installed.
3. Copy the manual package's `plugins` folder into `Valheim/BepInEx`.
   The resulting file is `BepInEx/plugins/OctoArsenal/OctoArsenal.dll`.
4. Keep only one OctoArsenal DLL. When updating, replace the previous DLL and
   keep the main configuration. No character or world save reset is required.
5. Start Valheim with matching versions on every client and the server.

The mod retires obsolete editor settings and archives `OctoArsenal.Fitting.cfg`
as a `.bak` file. Approved fits are built in; no fitting file is needed. Existing
item quality, hammer/pick mode and quenching data keep their native save keys.

BepInEx, game assemblies and other mods are not bundled.

## Release and test scope

Version **0.5.27** adds public AI disclosure metadata and release packaging to
0.5.26. Gameplay, approved fits, stats, costs, quests and model assets are retained.

The release build and automated regression checks pass. The final release binary
and live multiplayer have not received an in-game test. All players and the server
must use the same version. Offline players cannot receive kill credit. More test
details are included in the manual download.

## Community and support

Join **OctoDad's Mods** on [Discord](https://discord.gg/RueyvSfX7R) for questions,
bug reports and future mods. Include your mod version and the relevant BepInEx
log when reporting a problem.

## Credits and AI disclosure

Created by **OctoDad / Studio Bascinet**.

Created and maintained with generative AI assistance from **OpenAI Codex** (OpenAI), including code, documentation, concept references and asset-production assistance. The promotional equipment images use renders of the actual mod models. The mods have been built and tested during development; see Release and test scope above.

## Gallery

![Octo Arsenal features](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Features-1920x1080.png)

![Steel Dane Axe](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Steel-Dane-Axe-1920x1080.png)

![Steel Sword](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Steel-Sword-1920x1080.png)

![Steel Winged Spear](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Steel-Winged-Spear-1920x1080.png)

![Steel Bearded Axe](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Steel-Bearded-Axe-1920x1080.png)

![Steel Berserker Axes](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Steel-Berserker-Axes-1920x1080.png)

![Norse Bow](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Norse-Bow-1920x1080.png)

![Viking Round Shield](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Viking-Round-Shield-1920x1080.png)

![Kite Shield](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Kite-Shield-1920x1080.png)

![Armour Fang hammer and pick](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Armour-Fang-1920x1080.png)

![Steel Longsword](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Steel-Longsword-1920x1080.png)

![Optional OctoPack arrow quiver](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Arrow-Quiver-1920x1080.png)

![Optional OctoPack three-spear carrier](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Javelin-Carrier-1920x1080.png)

![Current weapon progression guide](https://raw.githubusercontent.com/octerockman/OctoArsenal/main/images/OctoArsenal-Weapon-Progression-1920x1080.png)

