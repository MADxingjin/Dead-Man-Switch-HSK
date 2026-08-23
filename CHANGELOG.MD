# Changelog.MD
Not a strictly formated changelog.

## 2026 Summer

2026-05

Branch Made: TryBackport1.6

Merged upstream DMS

Added Rimotamic compat to enable mechanoid nuclear battery production

Backported 1.6 research proj


## 2026 Spring

Branch: TryBackport1.6

### Added

Backported hyrax a small early caravan carry mech to 1.5, fires a .22lr machinegun, itself is fragile though.

Backported Part of FF Framework (AOBA`s new framework in 1.6) to 1.5, specificly, the semi auto bill system.
Backported Auto Ammo Stamp(print?) to 1.5, uses FFF semi auto bill system to compatible with standard CE ammo crafting bills.(THIS IS NOT A UF barrel reskin)


### Updated

Updated Geochelone cost to remove artifucle cost, add internal wire cost, and included builtin turret cost (weapon comp). Chat with AOBA the original mod author, these metal "turtle" are actually tanks that moves via track instead of artifucle body+ tungsteel shell.

Updated universal heavy mounted machinegun caliber from 5.56x45NATO to 7.62x51NATO to actually be a **"Full power cartridge"** mounted MG as zh_chs and zh_cht translation says.

## 2025-12

Created Branch: TryBackport1.6
This branch will be a testing ground for backporting some 1.6 new mech to 1.5 while HSK hasn`t upgrade to 1.6.

## 2025-10

### Changed

Nerfed most automatrid by rearranging their weaponpool (weaponTags) when generated as NPC. elinmates situation where DMS_Mech_Raider(pirate variant of soldat) in early game holds a plasma blaster and 1shot plate armor colonist.
Also Drastically increased automatrid combat power to make them less common in early event

## 2025-08

## 2025-07

### Fixed

Duplicate Ammo .338 Calibre with HMC , CTRL+CV HMC 338 instead.

## 2025-05-W3

### Fixed

- 762x385mmR Cannon recipe pharse failure because a misplaced comment mark.

### Removed

.22 AP-I as it`s unrealistic.

## 2025-05-W1

### Changed

- Artifuscle now grows at Organ lab.
- Artifuscle bionic now grows at organ lab.
- Reverted turtle artifuscle cost. They are, by original author means, metallic only.
- Research Project changed to HSK Parent, should their location change in ResearchTreeSK is still under consideration.
- Tech Project from wetware computer and all after are now spacer tech.
- DMS Starting Scene now gives a 338 marksman rifle and 11 Mags of FMJ ammo for self defense.
- DMS Starting Scene now also gives various material for instantly build a "DMS_MechGestatorSamll" and power it via the ship reactor in pregenerated structure on the map.
- DMS Starting Scene now begins with various industrial techs researched, to match HSK Biotech mechanitor scene.

### Removed

- UF Artifuscle Table, previously introduced to balance the cost.