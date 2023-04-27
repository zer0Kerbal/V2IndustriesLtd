---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
V2 Industries Limited (V2IL)
created: 26 Apr 2023
updated:

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

# [V2 Industries Limited (V2IL)][mod]

[Home](./index.md)

Provides a common agent, flag, and configs for MichealV2.0 products. For Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `V2Industries` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/V2Industries/V2IndustriesLtd`
* Extract the package's `V2Industries/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/V2Industries` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/V2Industries/V2IndustriesLtd`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/V2Industries/V2IndustriesLtd`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/V2Industries/V2IndustriesLtd`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [V2Industries]
      + [V2IndustriesLtd]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
              ...
      + [Flags]
        ...
      + [Localization]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * ManualInstallation.htm
      * changelog.md
      * License.txt
      * readme.htm
      * V2IndustriesLtd.version
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/V2IndustriesLtd "V2 Industries Limited (V2IL)"