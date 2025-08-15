![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond-Remastered/refs/heads/main/images/Vagabond%20Remastered%20Header%20PNG.png)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/156283">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/README.md">Installation</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/GAMEPLAY.md">Gameplay Guide</a> |
  Changelog |
  <a href="https://loadorderlibrary.com/lists/vagabond-remastered-2">Load Order</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/FAQ.md">FAQ</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/CONFIG.md">Configuration</a> |
  <a href="https://trello.com/b/cVEDt7At/vagabond-remastered">Trello</a> ]
</p>

---

# Table of Contents

 - [Beta Versions](#beta-versions)


## Beta Versions

- [0.3.8](#038) Release Date: August 15, 2025
- [0.3.7](#037) Release Date: August 13, 2025
- [0.3.6](#036) Release Date: August 12, 2025
- [0.3.5](#035) Release Date: August 11, 2025
- [0.3.4](#034) Release Date: August 10, 2025

### 0.3.8

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

- Many small bug fixes. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- Fixed an issue where percentage bonuses for lockpicking were doing almost nothing.
- Added [Dynamic Stat Scaler](https://www.nexusmods.com/skyrimspecialedition/mods/140409?tab=description)
  - Effectively replaces features of the [Enhance Enemy Attributes](https://www.nexusmods.com/skyrimspecialedition/mods/65861) mod that were removed in the previous update
  - **ONLY** buffs enemies that are lower than player's level. The exact buff is +2% melee damage, +1% ranged damage, +5 HP, +10 armor per level below player
  - Completely script-free
- Nerfed armor scaling of non-boss enemies by around 25%
- Reduced base stamina cost of attacks and dodges by 20%
- Weapons with unique Weapon Arts (crafted with Void Shards) are now easier to obtain, requiring lower tier weapons than previously
- Reduced intensity of [Know Your Enemy 2](https://www.nexusmods.com/skyrimspecialedition/mods/93258) and [armor module](https://www.nexusmods.com/skyrimspecialedition/mods/94067) resistances even more
  - These were already pretty mild, but now the settings are *lowest possible*. My intention is that these resistances only have very minor impact on the game for immersion / optimization purposes without feeling too restrictive.
- Overhauled some mage outfits with variants of [Traveling Mage - My version SE by Xtudo](https://www.nexusmods.com/skyrimspecialedition/mods/69577)
- Added [Tsor The Ultimate Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/70460) and [Faarok The Norse God](https://www.nexusmods.com/skyrimspecialedition/mods/66722) male character presets
- Removed [Drugs for Bandits](https://www.nexusmods.com/skyrimspecialedition/mods/112760) mod because the impact of bandits constantly using Skooma or Sleeping Tree Sap was actually annoying and caused some bandits to literally commit suicide

### 0.3.7

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

- Fixed an issue where player character was glowing red while attacking or blocking
- Bug fixes and balance tweaks to poise system
- Fixed first one-handed perk not providing intended damage on all stacks of mastery, also buffed the perk's damage bonus
- Both one-handed and two-handed first perks now increase poise damage dealt on each stack of mastery
- Made perfect dodge (sneak perk) more reliable to proc
- Added bigger character collisions to fix issues with getting too close to enemies during combat
- Gave non-boss NPCs proper katana and daikatana movesets
- Generated a navmerge in CK to hopefully reduce NPC pathing issues (seems to have fixed some College jank)
- Added [Maintained Magic](https://www.nexusmods.com/skyrimspecialedition/mods/114983)
  - Untested, feedback welcome
- Added [Death Idle Fix](https://www.nexusmods.com/skyrimspecialedition/mods/152344)
- Added [NAT.ENB III - sun glare lens chroma edge visibility Patch](https://www.nexusmods.com/skyrimspecialedition/mods/156781)

### 0.3.6

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

- Many small bug fixes. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- Made Weapon Arts more spammable, provided you have magicka. Also fixed any bugs where you lose magicka despite the attack not activating.
- Rebalanced bandits spawning in wilderness to be closer to player level
- Locked chests now have a chance to contain extra insight
- Added ultrawide optional addon (thanks Sasquatch)
- Added [Dismembering Framework](https://www.nexusmods.com/skyrimspecialedition/mods/126203)
  - by default gore is disabled, but can be enabled in optional mod
  - thanks to Biggie_boss for config
- Added [Dual Wield Parrying SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/85505?tab=files), but for Keyboard and Mouse users only
  - No extra button space for controller, plus spell hotbar can be used to cast spells leaving hand free for blocking
  - With MCO dual wield always blocks with right click / left bumper regardless
- Added [Relentless](https://www.nexusmods.com/skyrimspecialedition/mods/114022)
  - Can be purchased from Dawnguard Vendors Gunmar and Hestla
- Added [Lightened JK's Dragonsreach](https://www.nexusmods.com/skyrimspecialedition/mods/152031) to hopefully reduce odds of crashing there

### 0.3.5

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

- Fixed missing Timeless Elegance mesh, causing some NPCs like Carlotta Valentia to have invisible body
- Fixed missing textures on Wind Ruler armor, worn by Uthgerd the Unbroken
- Fixed clipping **ASS** on Penelope outfit worn by some female NPCs
- Fixed male character underwear and feet having messed up textures
- Reduced sprint stamina cost
- Removed jumping stamina cost
- Reduced stamina regen delay
- Added [No Stamina Consumption Outside Combat](https://www.nexusmods.com/skyrimspecialedition/mods/77026)
- Normal attacks can now be initiated while at zero stamina
- Made enemy arrows and bolts fly slower
- Made lockpicking less hardcore, the dice roll thresholds for all locks are lowered
- Fixed excessive damage on mace power attack and weapon art
- Nerfed NPC wards
- Fixed wrong precision trail visuals
- Add missing TrueHUD boss bars to some dungeon bosses
- Added [SSE FPS Stabilizer](https://www.nexusmods.com/skyrimspecialedition/mods/38438) optional file which was missing by mistake
- Removed Unslaad - Dragonslayer addon because it broke reward for killing a boss.
- Updated [Temples of the Ancients Complex Material](https://www.nexusmods.com/skyrimspecialedition/mods/127371) to fix weirdly dark looking textures
- Updated [New Creature Animation - Giant](https://www.nexusmods.com/skyrimspecialedition/mods/83317?tab=posts), hopefully the new version is less jank

### 0.3.4

Key Info

- Initial Release.
- Open Beta.
