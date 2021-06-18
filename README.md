# Loot Spawner with Colored Models and Vehicle Spawner with Colored Models


## Youtube Tutorial

[![Pavlov VR - Set up my Loot Spawner with Colored Models - LSWCM](https://img.youtube.com/vi/oov2Kj2PoJc/0.jpg)](https://www.youtube.com/watch?v=oov2Kj2PoJc)




![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## What it does


When you use the original Loot Spawner, you have to guess where the weapons are facing.
This toolkit adds a list of items alphabetically you can pick from. When selecting for example the AK47, you will see the model itself and where it's pointing to.


This gives the ability to have:
- better placements of Loot and Vehicles
- easier way to select from an alphabetic list of items and weapons
- spawning tanks, seeing their full model


NOTE: If your Vehicle doesn't spawn, make sure it's not colliding with any objects, the vehicle will NOT spawn when Colliding




![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Installation


1. Copy the Content folder into your "/ProjectNameHere/" folder, (NOT this Content inside your Content folder)
2. Open your project and load your level
3. Move the Blueprints folder into your UGC folder
- DO NOT MOVE THE PROPS / MATERIALS FOLDER ! This will increase your filesize by atleast 200mb which is not needed since it's only in Editor
4. Right click the Content folder in editor and press Fix Up Redirectors
(. Open the "BP_LootSpawnerWM" and "BP_VehicleSpawnerWM" and press Compile and Save--IF the icon is orange.



### To Spawn Items:
1. Drag and Drop "BP_LootSpawnerWM" into your level
2. Under the LSWCM category, select the "Loot to Spawn" you would like to spawn


### To Spawn Tanks:
1. Drag and Drop "BP_VehicleSpawnerWM into your level
2. Under the VSWCM category, select the "Vehicle to Spawn" you would like to spawn




![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Changelogs
#### Changelog 18/06/2021
- Added SKS, Reddot Pistol
- Swapped Adrenaline Syringe and Trip Alarm model

#### Changelog 11/06/2021
- Added Canted Sight, Bayonet M1 Garand, Bayonet Mosin Nagant
- Swapped WW2 Ammo Crate and Medkit model

#### Changelog 06/06/2021
- Added Adrenaline Syringe, Bandage, Bayonet Lee-Enfield, Bayonet Trenchgun, Scope Mosin Nagant, Scope Springfield, Tranquilizer Gun, Tripalarm
- Added Tiger tank
- Swapped Syringe model

#### Changelog 15/05/2021
- Added Shorty AK, Ammo Crate, Antipersonnel Mine, Antitank Mine, Medkit, Pushbomb, Scope Lee-Enfield, SND Bomb (not working at this moment), Trenchgun
- Changed naming of galil to galul, scar to scur, vss to vzz


#### Changelog 31/03/2021
- Added AR9, BallisticsShield, DetectiveSMG, DNAScanner, FlareGun, Flashlight Rifle, (Galil), Goldengun
- Added Discombobulation Grenade, Healthstation, (Kriss Vector), Pistol and Rifle Laser, M16, Monocular
- Added NewtonLauncher, Pipe, Pliers, RPG, Scope KAR98, Tec9 Surpressed, Helmet Skin Changer (US,SVT,GER)
- Added Teleporter, TTT C4, TTT Knife, (VSSM)
- Updated M4 and SawedOff models


#### Changelog 13/02/2021
- Added missing Weapon (Galil, not spawnable at this moment but it's coming)
- Added the "Make Random List?" button, this enables Random Item Lists
- Renamed all "Tank" names to "Vehicle"
- Added ATV and Truck to BP_VehicleSpawnerWM


#### Changelog 23/12/2020
- Added missing Weapons (DP27, VSS, SCAR20, Kriss Vector)
- Optimised Blueprint (thanks Mark Dey aka Lance)
- Added TankSpawner (Panzer, Sherman, T34)


#### Changelog 21/07/2020
- Added the WW2 Weapons
- Changed the material slightly
- Added RocketLauncher material instance


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
## Credits

- Credits go to Davevillz's Pavlov VR for the original models in this package
- Mark Dey (Lance) for helping me optimise this Blueprint
- Coomzy for giving me this idea


If you find any bugs or have any ideas for improvement, please let me know on Discord
- KENNITHH#7175 -
