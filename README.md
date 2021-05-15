////////////////////////////////////////////////////////////////////////////////////////
//Loot Spawner with Colored Models AND Vehicle Spawner with Colored Models (LSWCM 2.7)//
////////////////////////////////////////////////////////////////////////////////////////

//What it does

When you use the original Loot Spawner, you have to guess how the weapons are facing.
This toolkit adds a list of items you can pick from and when selecting for example an AK47, you will also see how its oriented.

This gives the ability to have:
- better placements of loot and Vehicles
- easier way to select from an alphabetic list of items and weapons
- spawning tanks seeing their size

NOTE: If your Vehicle doesn't spawn, make sure it's not colliding with any objects, the vehicle will NOT spawn when Colliding




//Installation

1. Copy the Content folder from inside "LSWCM2.7.zip" to your "/ProjectNameHere/" folder
2. Open your project and load your level
3. Move the Blueprints folder to your UGC folder (Don't forget to Fix Up Redirectors)
- DO NOT MOVE THE PROPS / MATERIALS FOLDER ! This will increase your filesize by atleast 200mb which is not needed since it's only in Editor
- Right click the Content folder in editor and press Fix Up Redirectors
4. Open the "BP_LootSpawnerWM" and "BP_VehicleSpawnerWM" and press Compile and Save--IF the icon is orange.


//To Spawn Items:
1. Drag and Drop "BP_LootSpawnerWM" into your level
2. Under the LSWCM category, select the "Loot to Spawn" you would like to spawn

//To Spawn Tanks:
1. Drag and Drop "BP_VehicleSpawnerWM into your level
2. Under the VSWCM category, select the "Vehicle to Spawn" you would like to spawn



//Changelog 31/03/2021
- Added AR9, BallisticsShield, DetectiveSMG, DNAScanner, FlareGun, Flashlight Rifle, (Galil), Goldengun
- Added Discombobulation Grenade, Healthstation, (Kriss Vector), Pistol and Rifle Laser, M16, Monocular
- Added NewtonLauncher, Pipe, Pliers, RPG, Scope KAR98, Tec9 Surpressed, Helmet Skin Changer (US,SVT,GER)
- Added Teleporter, TTT C4, TTT Knife, (VSSM)
- Updated M4 and SawedOff models

//Changelog 13/02/2021
- Added missing Weapon (Galil, not spawnable at this moment but it's coming)
- Added the "Make Random List?" button, this enables Random Item Lists
- Renamed all "Tank" names to "Vehicle"
- Added ATV and Truck to BP_VehicleSpawnerWM

//Changelog 23/12/2020
- Added missing Weapons (DP27, VSS, SCAR20, Kriss Vector)
- Optimised Blueprint (thanks Mark Dey aka Lance)
- Added TankSpawner (Panzer, Sherman, T34)

//Changelog 21/07/2020
- Added the WW2 Weapons
- Changed the material slightly
- Added RocketLauncher material instance



//Credits

- Credits go to Davevillz's Pavlov VR for the original models in this package
- Mark Dey (Lance) for helping me optimise this Blueprint
- Coomzy for giving me this idea


If you find any bugs or have any ideas for improvement, please let me know on Discord
- KENNITHH#7175 -




- KENNITHH