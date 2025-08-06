![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond-Remastered/main/images/Banner.png)

<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/156283">Nexus</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/README.md">Installation</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/GAMEPLAY.md">Gameplay Guide</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/CHANGELOG.md">Changelog</a> |
  <a href="https://loadorderlibrary.com/lists/vagabond-remastered-2">Load Order</a> |
  <a href="https://github.com/Oghma-Infinium/Vagabond-Remastered/blob/main/Documentation/FAQ.md">FAQ</a> |
  Configuration |
  <a href="https://trello.com/b/cVEDt7At/vagabond-remastered">TRELLO</a> ]
</p>

---
<header>
    <h1>Contents</h1>
</header>

- [Optional Addons](#optional-addons)
  - [Mouse and Keyboard Support](#mouse-and-keyboard-support)
  - [Performance Optimizations](#performance-optimizations)
- [Changing FPS Limit](#changing-fps-limit)
- [Upscalers and FrameGen](#upscalers-and-framegen)
  - [ENB Frame Generation](#enb-frame-generation)
  - [Skyrim Upscaler](#skyrim-upscaler)
  - [Lossless Scaling](#lossless-scaling)
- [In-Game MCM Options](#in-game-mcm-options)
- [Wheeler](#wheeler)
  - [Wheel Editing](#wheel-editing)
    - [Creation](#creation)
    - [Insertion](#insertion)
    - [Ordering](#ordering)
    - [Deletion](#deletion)


# Optional Addons

The following sections detail the **supported** modifications to the list. Any other modifications should be discussed in the `#Vagabond Remastered-modified` channel of the [Waking Dreams](https://discord.gg/4WwqfK5yHg) support server.

### Mouse and Keyboard Support

Vagabond Remastered is by default designed to be played with a controller. However, the list ships with a premade mouse and keyboard configuration, designed for the list. In order to activate the mouse and keyboard config, please follow the steps below:

 1. Navigate to the `Optionals` separator under the Optional Addons section in the **left pane** of MO2.
 2. Activate the `Settings for M&KB gameplay` mod.
 3. Boot up the game.
 4. Open settings -> controlls and reset keybinds.
 5. ???
 6. Profit!

## Performance Optimizations

>[!IMPORTANT]
>Make sure to set your CPU Affinity before experimenting with other Performance Optimizations below!
<Details>
<summary>Setting CPU Affinity</summary>

 1. Click the `Puzzle Piece` button at the top of MO2 and select `Set CPU Affinity` and press `OK` on the pop-up box.
    ![](https://raw.githubusercontent.com/Oghma-Infinium/Vagabond/main/images/cpu%20affinity%20example.png)
 2. That's it, it's really that simple. **Please, please, please** do this before launching the game and whenever you update the modlist.

</Details>


Below are the list of mods you will find under the `Optionals` separator in MO2.
 1. `ENB Frame Generation`: This mod requires a GPU that supports DirectX 12.
 2. `ENB Anti-Aliasing - AMD FSR 3.1 - NVIDIA DLAA`: This mod requires a GPU that supports DirectX 12. It automatically enables correct AA type depending on your GPU brand.
 3. `Force 1080p resolution`: As the name implies, this mod can be enabled to force the game run on 1080p. Intended as optional performance boost for those with 1440p or 4K screens.
 4. `AVX 512 for HDT-SMP`: This mod contains the AVX512 version of the [Faster HDT-SMP](https://www.nexusmods.com/skyrimspecialedition/mods/57339) `.dll` file compatible with the list. It is ***highly*** suggested that you try out this addon if you have a CPU that supports AVX-512 instruction. If you do not know if your CPU supports AVX-512, then google it or use a tool like HWinfo. **ENABLING THIS MOD WITH AN INCOMPATIBLE CPU WILL EITHER CRASH YOUR GAME OR BREAK ALL SMP**.

Beyond what I can easily offer, you may want to consider reducing the `iShadowMapResolution` from `2048` to `1024` or `512` in the `profiles/Vagabond Remastered/skyrimprefs.ini`.   

>[!CAUTION]
>**DO NOT** use tools such as [Bethini](https://www.nexusmods.com/site/mods/631)! The `.ini` files have already been extensively tweaked, and many of the preconfigured settings set by these tools are not optimized for the list. 

**DISCLAIMER:** I will not provide troubleshooting or support for performance as everyones' PC is different and I can only know for certain how performance is on my own machine. In addition to this, I (Ylikollikas) am not some massive computer hardware nerd and I am not qualified to make definitive statements about hardware performance when I have not personally tested it, if that hardware is borderline / similar to the hardware that I **expect** to work best for the list.

# Changing FPS Limit

By default, Vagabond Remastered is capped to 61 FPS and has several settings that will target 61 FPS. If you wish to increase your FPS Limit then these are changes that are recommended.

The following `.ini` files must be edited **while out of game**. After tweaking these `.ini` files, you can uncap FPS or change the FPS cap in the in-game ENB GUI (`END` to open).

<Details>
<summary>SSE FPS Stabilizer & Shadow Boost</summary>

 1. Open the `SSE FPS Stabilizer & Shadow Boost` mod under the `Optionals` separator.
 2. In ShadowBoost.ini, under the `[Settings]` Header, edit `fTargetFPS = 60.000000` (line 2) to your new Target FPS.
 2. In SSEFpsStabilizer.ini, under the `[Settings]` Header, edit `TargetFps = 60` (line 13) to your new Target FPS.
</Details>

# Upscalers and FrameGen

## ENB Frame Generation

The list includes the [ENB Frame Generation](https://www.nexusmods.com/skyrimspecialedition/mods/144507) mod as an optional file under [Performance Optimizations](#performance-optimizations). While this mod is disabled by default, it can be enabled for potentially large performance gains at minimal quality loss. This mod is not considered a list modification. 

The Waking Dreams staff and I (Ylikollikas) do not endorse any other potential alternative to this mod, however there are other 3rd party software that can be utilized to achieve a similar effect.

## Skyrim Upscaler

While [Skyrim Upscaler](https://www.nexusmods.com/skyrimspecialedition/mods/80343) is an unsupported addition, it is asked about often enough that I felt I should put this here. In order to make sure your Upscaler works, you must change some lines in the `SSEDisplayTweaks.ini`.

In the `SSEDisplayTweaks.ini` make sure that `Fullscreen = false` (line 39), `Borderless = true` (line 48), and `BorderlessUpscale = false` (line 58) under the `[Render]` section.  

Additionally, if you intend on using the FrameGen features of the newer [Skyrim Upscaler](https://www.nexusmods.com/skyrimspecialedition/mods/80343) builds, go in the `SSEDisplayTweaks.ini` and set `FramerateLimit` (line 206) equal to **half** of your monitor's refresh rate.

All other installation concerns for Skyrim Upscaler (DLSS) should be discussed in the modifications channel in the discord.  

## Lossless Scaling

[Lossless Scaling](https://store.steampowered.com/app/993090/Lossless_Scaling/) is also an unsupported addition to the list. In order to make sure your Upscaler works optimally, you must change some lines in the `SSEDisplayTweaks.ini`.

In the `SSEDisplayTweaks.ini` make sure that `Fullscreen = false` (line 39), `Borderless = true` (line 48), and `BorderlessUpscale = false` (line 58) under the `[Render]` section.  

Additionally, if you intend on using the FrameGen features of the newer [Skyrim Upscaler](https://www.nexusmods.com/skyrimspecialedition/mods/80343) builds, go in the `SSEDisplayTweaks.ini` and set `FramerateLimit` (line 206) equal to **half** of your monitor's refresh rate.

All other configuration concerns for Lossless Scaling should be discussed in the modifications channel in the discord.

# In-Game MCM Options

Thanks to Wabbajack, MCMs will come pre-configured with the intended settings. The following is a list of MCMs that contain keybind or preference related settings.

>[!WARNING]
>Changing MCM Settings in any MCM that is not listed below is considered a list modification!

 - `Skyrim Unbound`: Can change various settings related to start. Choosing non-dragonborn is not recommended. Also, **do NOT choose vampire or werewolf start**, these cause stuff to break.
 - `Better Third Person Selection`: ???
 - `CollisionReset`: Change the keybind for resetting SMP physics (Default: `F10`). 
 - `Quick Beri`: Can change lantern hotkey (Default: `L` or long-press activate) and other related settings.
 - `EVG CLAMBER`: Change the EVG Clamber settings (Default: `Balanced`). This isn't recommended to be tampered with but you can.
 - `LOD Reload Bug Fix`: **(DEBUG ONLY)** Can fix unloaded LODs.
 - `moreHUD`: Can adjust certain widgets on the HUD.
 - `OBody NG`: Change the keybind for the OBody morphs menu (Default: `;`). **DO NOT ENABLE PERFORMANCE MODE!**
 - `One Click Power Attack`: Change the keybind for Power Attacks (Default: `RT`).
 - `Photo Mode`: Adjust the keybinds and settings for [po3's Photo Mode](https://www.nexusmods.com/skyrimspecialedition/mods/91701).
 - `Precision`: Can enable or disable Hitstop (Default: `Enabled`).
 - `Quest Journal Limit Bug Fixer`: **(DEBUG ONLY)** Refreshes all active quest objectives.
 - `QuickLoot IE`: Configure QuickLoot's settings and controls.
 - `Skyrim Outfit System`: Transmog system, read more on the [mod page](https://www.nexusmods.com/skyrimspecialedition/mods/42162) or in the [discord](https://discord.gg/4WwqfK5yHg).
 - `SmoothCam`: Change the SmoothCam Camera preset
 - `Sneak Vignette`: Adjust the opacity of the Vignette that appears while sneaking. Set `Vignette Opacity` to `0` in order to disable (Default: `67`).
 - `Swift Potion`: Change the hotkey for quick potion binds.  
     - Restore Health = `D-pad left`  
     - Restore Stamina = `LT + D-pad left`  
     - Restore Magicka = `D-pad right`  
 - `TK Dodge`: Change the hotkey for Dodging (Default: tap sprint or `C`).
 - `True Directional Movement`: Change the target lock hotkey (Default: `Right stick press`).
 - `TrueHUD`: Adjust core components of the HUD.

# Wheeler

Wheeler is utilized as an alternative to the vanila favorites menu (which can still be accessed with `G` on keyboard). For configuration help, please refer to the below documentation. Also please note that almost this entire section is copy-pasted from the [Wheeler mod page](https://www.nexusmods.com/skyrimspecialedition/mods/97345), and the mod page may provide more assistance with certain configuration help.

## Wheel Editing

Changes to the wheel can be made when you open the wheel in either the **inventory or magic menu**. When you open the wheel in these two menus, the background will grey out, suggesting that you're now in **edit mode**.

### Creation

By default, create an empty wheel using the `N` key and an empty slot using the `M` key. You can create as many wheels and as many slots in a single wheel as you'd like.

### Insertion

To insert an item or magic into the slot, hover on the item you desire in the inventory, open the wheel, and **left-click** (right shoulder) on the entry you wish to insert the item into.

### Ordering

To change a slot's order in a wheel, press the up/down arrow to swap its position with neighboring slots.  

To change a wheel's ordering among all wheels, press the left/right arrow to swap its position with neighboring wheels.

### Deletion

To delete an item from a slot, simply **right-click** on the item you wish to delete.
 - Right-clicking on an empty slot deletes the slot.
 - Right-clicking on an empty wheel deletes the wheel (you can't delete the last wheel).
