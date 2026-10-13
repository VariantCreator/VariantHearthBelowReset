# Variant HearthBelow Reset

Fixes HearthBelow holes not closing when resetting or leveling with the PlanBuild rune or admin hoe.

## 🟢 Install

Download [1.0.1](https://github.com/VariantCreator/VariantHearthBelowReset/releases/download/v1.0.1/VariantHearthBelowReset-1.0.1-Hexium.zip). Install with your mod manager, or place `VariantHearthBelowReset.dll` in `BepInEx/plugins`.

Install this patch on clients that use the terrain tools.

## 🔵 Use

- **Reset terrain** restores the selected HearthBelow cave edits.
- **Level terrain** closes surface holes while preserving separate deeper caves.

Cave restoration cannot be undone.

## 🟣 Mods

Use BepInEx and HearthBelow 0.7.0. HearthBelow must be installed on the server and all clients.

Use either the **PlanBuild rune** or **World Edit Commands** terrain tools. **Infinity Hammer** uses World Edit Commands for its admin hoe. The integrations work separately; you do not need both. DigDeeper can stay installed.

## ⚙️ Settings

Open `BepInEx/config/VariantMods.HearthBelowReset.cfg`.

- **Show Popups** is off by default. Turn it on to show this mod's messages.
- **PlanBuild** and **World Edit Commands** each switch their integration on or off.

<details>
<summary>ServerGuard allowlist</summary>

Add this line under your existing `allowed_mods:` list for this DLL:

```yaml
  - VariantMods.HearthBelowReset|65e15e9bc51e4ae275f0aa5a60c47b6711dbd60e106aee118e68223596ac14c9
```

</details>

[Changelog](https://github.com/VariantCreator/VariantHearthBelowReset/blob/main/CHANGELOG.md)
