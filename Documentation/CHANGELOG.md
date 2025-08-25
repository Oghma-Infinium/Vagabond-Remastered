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

- [0.3.12](#0312) Release Date: August 25, 2025
- [0.3.11](#0311) Release Date: August 22, 2025
- [0.3.10](#0310) Release Date: August 19, 2025
- [0.3.9](#039) Release Date: August 17, 2025
- [0.3.8](#038) Release Date: August 15, 2025
- [0.3.7](#037) Release Date: August 13, 2025
- [0.3.6](#036) Release Date: August 12, 2025
- [0.3.5](#035) Release Date: August 11, 2025
- [0.3.4](#034) Release Date: August 10, 2025

### 0.3.12

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

If using [**Maintained Magic**](https://www.nexusmods.com/skyrimspecialedition/mods/114983), unapply maintained spells before updating and re-apply the maintained spells after updating.

After updating and loading your existing character, create a new save file, then [clean your save](https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/CONFIG.md#cleaning-saves). This step is highly recommended.

- Lots of bug fixes, too many to list. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- Fixed an issue where entering skills menu immediately after obtaining insight may result in gaining up to triple the intended amount of insight points
- Greater Insight is now required after skill level 51 instead of 50 for consistency with training costs
- Enable regular to greater insight conversion with 5:1 ratio
- Nerfed excessively spongy dragon HP
- Nerfed Bleak Falls Barrow boss
- Fixed an issue where equipping some unique weapons would increase regular weapon art cost
- Made quest level gates actually work, should now be consistent with the [Gameplay Guide](https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/GAMEPLAY.md#quests-changes)
- Fixed Paladin Martih getting aggressive too easily from friendly hits (thanks Fate)
- Fixed a common crash in Dragonsreach
- Removed [Immersive Patrols Lite](https://www.nexusmods.com/skyrimspecialedition/mods/718) since I suspect random fights between civil war NPCs were prone to causing crashes

### 0.3.11

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

If using [**Maintained Magic**](https://www.nexusmods.com/skyrimspecialedition/mods/114983), unapply maintained spells before updating and re-apply the maintained spells after updating.

- Lots of bug fixes, too many to list. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- First Heavy Armor perk now gives 0.5% poise resistance per level of Heavy Armor skill when wearing heavy chestpiece
- First Light Armor perk now gives 0.35% poise resistance per level of Light Armor skill when wearing light chestpiece
- Fixed Battlemage magicka battery not working against enemies with 0 or less magicka
- Fixed issues with Void Shards sometimes not dropping when they should
- Removed dodges, sprinting and sprint attacks from Awoken Draugr (this was not intended in the first place)
- Buffed resistances of some unique dungeon bosses because I felt like they died a bit too fast
- Made the damage bonus from sprint attack perks in 1H and 2H trees actually work
- Slightly reduced drop rates of Diluted Insight from enemies and containers (around 15%, just regular; greater is unaffected)
  - Personally felt leveling was bit too fast in my current playthrough
- Rebalanced weapon and armor weights
- Rebalanced Silver Weapons, they now deal 50% extra damage against undead and werewolves, but degrade in durability 3 times faster than other materials
  - Before they dealt flat +20 + 25% extra damage against undead & WW with no penalty on degration speed
- Removed most Mihail mod summon spell tomes from being obtainable (I actually missed some)
- Made attacking immediately after blocking an attack feel more responsive
- Increased base poise health of both player and enemies, meaning everyone gets staggered slightly less frequently
- Disabled features of Skyrim Save Safe Overhaul by default because I suspect it might be causing crashes/freezes
- Made Lady Stone the default starting Standing Stone if another one is not picked in Skyrim Unbound MCM
- Added [DD - Jewelry Replacer by Vergi](https://www.nexusmods.com/skyrimspecialedition/mods/157252)

### 0.3.10

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

If using [**Maintained Magic**](https://www.nexusmods.com/skyrimspecialedition/mods/114983), unapply maintained spells before updating and re-apply the maintained spells after updating.

- Many small bug fixes. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- Added [Skyparkour](https://www.nexusmods.com/skyrimspecialedition/mods/132292?tab=posts)
- Added [Sprint Swim Redux SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/156417)
- Added [Skyrim's Paraglider](https://www.nexusmods.com/skyrimspecialedition/mods/53256)
- Added [Zen's presets](https://next.nexusmods.com/profile/RelentlessZen/mods)
- Removed two shrine blessing related perks from Restoration tree because they don't work properly with the [religion mod](https://github.com/Oghma-Infinium/Apostasy/blob/main/GAMEPLAY.md#archon---faiths-of-tamriel)
  - (untested) You can refund perk points by taking 5 Daedra Hearts to a cooking pot and crafting a Scroll of Legends.
- Fixed a balance oversight causing power attacks to deal more damage against blocking targets than intended. Affects both normal and timed block.
  - In practice a major buff to block builds
- Fixed issues with some enemies dropping more insight than intended (especially those with particularly high stamina or magicka)
  - Slightly increased insight drops from some other sources to compensate
- Reduced level multiplier of Hard enemy spawns from 1.25 to 1.15 and Very Hard spawns from 1.5 to 1.3 to reduce frequency of sudden difficulty spikes.
- Made battlemage magicka battery not restore magicka on Weapon Art attacks
  - Before this change some Weapon Arts like the Sword Dance could refund more magicka than they cost
- Removed wards from almost all mage enemies (and nerfed them for those who still do)
  - Player wards still remain as effective as before
- Made valuable weapons on Jorrvaskr walls to be only decorative
- Made Starfrost Hunger and Sleeping bonuses actually do something
- Significantly slowed food spoilage. All food now lasts at least 7 days, with most lasting 14+ days.
  - This does not automatically update on existing saves, but you can use the console commands below.
  - <details> <summary>**Updating food spoilage times with console commands**</summary>
    
    set SFSS_SpoilDaysCat0 to 42

    set SFSS_SpoilDaysCat1 to 14

    set SFSS_SpoilDaysCat2 to 14

    set SFSS_SpoilDaysCat3 to 14

    set SFSS_SpoilDaysCat4 to 7

    set SFSS_SpoilDaysCat5 to 7

    set SFSS_SpoilDaysCat6 to 7

    set SFSS_SpoilDaysCat7 to 7

    set SFSS_SpoilDaysCat8 to 21

    set SFSS_SpoilDaysCat9 to 28
  
</details>

### 0.3.9

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

- Many small bug fixes. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- Difficulty settings overhaul. See [guide](https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/GAMEPLAY.md#difficulty-overhaul) for details
  - Default difficulty Adept is now easier than before, especially on resource management, with Expert, Master and Legendary intended as "challenge" difficulties
- Reduced poise damage taken by player by 33% (This is **separate** change from the difficulty overhaul)
- Reduced baseline physical damage enemies deal by 20% (this is remedied by difficulty overhaul for those who still want it tough)
- Fixed tempering, it was barely doing anything before
- Reduced intensity of dynamic scaling for low level enemies
- Made most player one-handed animations 10% faster, because it felt like those weren't quite fast enough compared to two-handed
- Reduced reach of NPC melee attacks
- Removed bunch of terrible SPID outfit distributions (Khajit with a summer dress, Torvar with gladiator outfit)
- Fixed an issue where Skyrim Outfit System item search crashed the game because of Chinese characters
- Added [Bows Can Break](https://www.nexusmods.com/skyrimspecialedition/mods/104758) for NPCs only
- Added [Grendel - Troll Audio](https://www.nexusmods.com/skyrimspecialedition/mods/115955) because current Trolls sounded like lawn mower
- Added [Austio Silver Swords Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/58584)

### 0.3.8

Key Info

**Ignore missing plugins warning when loading a save. It doesn't matter!**

- Many small bug fixes. See [Trello](https://trello.com/b/cVEDt7At/vagabond-remastered) for details. (thanks for all the bug reports)
- Fixed an issue where percentage bonuses for lockpicking were doing almost nothing.
- Added [Dynamic Stat Scaler](https://www.nexusmods.com/skyrimspecialedition/mods/140409?tab=description)
  - Effectively replaces features of the [Enhance Enemy Attributes](https://www.nexusmods.com/skyrimspecialedition/mods/65861) mod that were removed in the previous update, but in a much more balanced manner
  - **ONLY** buffs enemies that are lower than player's level. The exact buff is +2% melee damage, +1% ranged damage, +5 HP, +10 armor amd +0.5% magic resistance per level below player
  - Completely script-free
- Nerfed armor scaling of non-boss enemies by around 25%
- Reduced base stamina cost of attacks and dodges by 20%
- Weapons with unique Weapon Arts (crafted with Void Shards) are now easier to obtain, requiring lower tier weapons than previously to craft them
- Reduced intensity of [Know Your Enemy 2](https://www.nexusmods.com/skyrimspecialedition/mods/93258) and [armor module](https://www.nexusmods.com/skyrimspecialedition/mods/94067) resistances even more
  - These were already pretty mild, but now the settings are *lowest possible*. My intention is that these resistances only have very minor impact on the game for immersion / optimization purposes without feeling too restrictive.
- Expanded the number of bosses that reward perk point on kill. (It was already *many* and the cap is 50 per playthrough)
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
