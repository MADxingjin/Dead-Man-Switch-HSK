# HSK(ify) TODO.MD

WTF UF only allows one RecipeUser Per Recipe.

## Working on
Weap classify > COST HSKify

Sort by Weap Ammo, Size(dimension), And Human barearm usability.
Only human barearm equipable weapon is needed to modify into HSK Style, the rest just inject the cost for recipe maker and we are done.

1. Pistol
   1. DMS_KnuckledusterRevolver
   2. DMS_Revolver
2. Shotgun
   1. DMS_RiotShotgun
   2. DMS_AssaultShotgun
3. Rifle
   1. DMS_SurvivalRifle
4. SMG 
   1. DMS_TaticalPistol (it fires .50AE, and it a semiauto)
   2. DMS_PDW
   3. DMS_MiniMachineGun (yes I say this IS a SMG,even this one only fires .22LR,but it has 200 MAG SIZE.)
5. Sniper
   1. DMS_AssaultPiercer
   2. DMS_AssaultRifle
   3. DMS_MarksmanRifle
6. Heavy
   1. DMS_ElephantGun H
   2. DMS_SemiAutoRifle (.50BMG)
   3. DMS_BattleRifle
   4. DMS_AntiMaterialRifle
   5. DMS_LightMachineGun (.338)
   6. DMS_HeavyMachineGun
   7. DMS_GAU19Gatlinggun (.50BMG)
   8. DMS_M214Gatlinggun (556x45)
   9. DMS_SniperCannon (30x173,5,95)
   10. DMS_SniperGrenadeLauncher
   11. DMS_AutomaticGrenadeLauncher
7.  Launcher
   1. DMS_DoorBreaker
   2. DMS_Gun_Recoilless
   3. DMS_Gun_DragoonRifle
   4. DMS_Gun_DragoonGrenade
8. Specific
   1. DMS_Autocannon (20x102,60,78)
   2. DMS_GAU8Gatlinggun
   3. DMS_GAU4Gatlinggun
   4. DMS_GAU4Gatlinggun_Hold
   5. DMS_Tarbosaurus_Gun
   6. DMS_Gun_2A38M
   7. DMS_Gun_DawnbladeM
   8. DMS_Flameblaster



## Works Done

1. CE Ammoset missing in HSK CE
   Check all weap in game and record their ammo set & ammo type
   1.1 Patch ammo recipes to HSK style & cost rebalance

2. Building Stuffable
3. 


## TODO

1. Building 
   1. stuffable
   2. power consumption
   3. Prod type change
   4. Cost rebalance
2. Turret stuffable
   1. remove turret cannon pipe req.
   2. possibly make some weap chest?
3. Apparel
   1. Material recongize
   2. Cost
   3. rebalance
4. Faction StockGenerator
5. Mech cost
6. Mech WorkType adjust to HSK
7. Item cost

## REF All Ammosets used by DMS asof 2025-01-30
    30x165 ,used by GAU-8,but HSK has a builtin GAU-8 and it uses a different ammoset,no comment on that but if we patches it?
    30x173NATO # ! HSK has this one !
    762x385RCannonShell #added
    127x108,included in HMC,needed to add in loadfolders in case hmc is not loaded.
    81mmMortarShell
    45Colt410BoreSB # only used in DMS_KnuckledusterRevolver, so nerfed that gun to 45ACP only ,no additional import.
    12Gauge
    10Gauge # used in single weap,DMS_RiotShotgun. so patched that back to 12G & default proj to beanbag. no additional import
    22LR # Add, 2guns.
    `Survival Rifle` # this one is tricky
    .303
    .50BMG
    40x53mmGrenade # merged with 40x46,since only used in one weap.
    .50AE #add, two guns uses them
    338Lapua # CoreSK dont have this,but HMC added one 338 and wiki says they are interchangeable, so insert Mayrequire HMC 338 into the ammoset for compat
    20x102NATO # ! HSK has this one !
    RPG32Rocket #added for now
    556x45NATO
    SPG9Rocket # ! HSK has this one !
    37x223R # added for now
    60mmMortarShell_DF # Self Def
    `DMS_FlameThrower` # Self Def,

## REF Mech cost tier

Somehow current cost is way too high, still needs nerf.

Different from how CORESK patches their way to biomatterize biotech mechs,DMS mechs are mostly made of metallic,which means way more comp usage.

obviously Artifical muscle will require biomatter to grow with.
also wetware

Will add a recipe to allow manually create T/R part and CompFireControl at Stamping station.

Mechs with T/R parts will have more electronics parts required to gest with.
Mechs with builtin guns require additional weap parts to gest with.

BASE:tungsteel
W(ingot) + Al +Silcon(K)(Na) fast
W(raw ore) + Sulfur + Al + Silcon Slow
FUN:
designate WCo Alloy as tungsteel(very fast)



1. Soldat Based
   1. 4 Mech Parts = 2 for arms and legs, 1 for weapon attach, 1 for head.
   2.Additional Lead Bar is required as desc says clear "battery pack"
   * Sergeant requires more comp as its special ability obviously require a anttenla.

2. Ronin
   1. 2 Mech parts + 2 Adv Mech Parts for Arms
   * Protector requires additional rubber as shield damping.
3. Battle Friend
   1. 4 Mech parts for legs + 2 Adv Mech Parts for Arms (the body costs more as its size)
   2. For Lifter, it requires additional rubber for carrying damper
   3. For ShaftWorker, it requires additional USLD Metal(probably tungsteel) as drill head.
   4. Ape requires additional Electronic comp to control.
4. Humanoid
   1. Already requires tungsteel, it requires 4 adv mech parts to operate as a mil tier mech.
5. Super Heavy
   1. Gecko
6. Addon TODO
   1. Big sister requires additional resource to support its embedded structure.


## REF Heavy Mech Builtin Weapon
Iguana -> 5.56x45NATO SMG -> Rifle
Gecko -> Flamethrower -> Heavy
Tarbosaurus -> .50BMG HMG -> Heavy
Tarbosaurus -> CIDS shotgun -> Shotgun
