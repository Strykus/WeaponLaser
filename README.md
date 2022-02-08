# WeaponLaser
Add Weapon Laser to almost all Weapons in Titanfall 2

Want to ask me something? feel free to dm in my discord: Avalar#2742
## INSTALLATION
![Release](https://user-images.githubusercontent.com/37307454/152735835-2719edc2-7c3e-4615-9522-97f49684a823.png)

This mod is compatible with:

[VTOL](https://github.com/BigSpice/VTOL) and [Thunderstore](https://northstar.thunderstore.io/) You can use one of those to install the mod

Or going on the GitHub page on [Release](https://github.com/Strykus/WeaponLaser/releases) section 

## File location and Overview

1: Go to `~/Titanfall2/R2Northstar/mods/WeaponLaser/mod/scripts/weapons/<name of the weapon/weapon type>_weapon_laser.txt`

You can find there:

>`archer_weapon_laser` - Archer

>`kraber_weapon_laser` - Kraber and Doubletake

>`hitscan_weapon_laser` - all Smg, Assault, Pistols, Lmg weapon types and DMR

>`projectile_weapon_laser` - L-Star, MGL, Softball, EPG, Cold War 

>`wingman_weapon_laser` - Wingman Elite

>`mastiff_weapon_laser` - Mastiff and Mozambique

>`smr_weapon_laser` - SMR

![l7](https://user-images.githubusercontent.com/37307454/153056715-45371570-f04d-4b5e-928a-52f783abc704.gif)


2: When opening file you will see something like this: 

    WeaponData
    {

            "projectile_launch_speed"                        "99999999"

   
            //remove comment "//" in front of color that you want(or change name after "first_" that already active) to use, and then save the file and reload the game 
            //or when in lobby type command in console: sv_cheats 1; weapon_reparse; reload_mods; sv_cheats 0
            //you can bind this command to any button by typing: bind f3 "sv_cheats 1; weapon_reparse; reload_mods; sv_cheats 0"
            //change color size after color name: 5,10,20,30,40,50,60,70,80,90,100  example: CH_grenade_arc_proto_path_first_golden_20
            //values without numbers at the end have size: _path_first_<your color> is 16 _path_<your color> is 32
            //rgb have 5,10,30,40,50,60,70.80,90,100 and 20 is default
   
            //change SMG,Assault,Sniper,Shotgun weapon types laser color and size below
    
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_blue"
            "grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_cyan"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_golden"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_green"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_magenta"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_orange"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_purple"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_pink"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_red"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_white"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_yellow"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_rgb"


            "grenade_arc_indicator_show_from_hip"            "1"
            }


# How to use!

 Remove comment `"//"` inside file `"hitscan_weapon_laser.txt or projectile_weapon_laser.txt or other"` in front of color that you want(or change name after "first_" that already
 active) to use, and then save the file and reload the game.
> Change color size after color name: `5,10,20,30,40,50,60,70,80,90,100` 

![command](https://user-images.githubusercontent.com/37307454/153057185-7a8706fb-6a18-41e2-8500-6f6b8ba2d104.gif)

When in lobby, type command in console: sv_cheats 1; weapon_reparse; reload_mods; sv_cheats 0
 You can bind this command to any button by typing: bind f3 "sv_cheats 1; weapon_reparse; reload_mods; sv_cheats 0"

![changelaser](https://user-images.githubusercontent.com/37307454/153057465-0ba63d97-7692-4ef8-b368-87f0c9ac77e8.gif)

>example: `CH_grenade_arc_proto_path_first_golden_20`

            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_cyan"
            //"grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_golden"
            "grenade_arc_indicator_effect"                    "CH_grenade_arc_proto_path_first_green_20"

 Values without numbers at the end have size: 

>`_path_first_<your color>` is `16`

>`_path_<your color>` is `32`

>rgb have `5,10,30,40,50,60,70,80,90,100` and 20 is `"CH_grenade_arc_proto_path_first_rgb"`



# laser Sowcase


![l1](https://user-images.githubusercontent.com/37307454/153057081-d1b9dcf9-c200-4d77-a2e0-b6d5db7ba8f5.gif)
![l2](https://user-images.githubusercontent.com/37307454/153056977-7039e983-97e3-49e3-bbd4-dc90d2e78efa.gif) 
![l3](https://user-images.githubusercontent.com/37307454/153056911-0c214e56-8157-41b6-8d4c-8a6134e36ec7.gif)
![l4](https://user-images.githubusercontent.com/37307454/153056871-9abef28c-3051-4e9b-b74f-b4ae86ddae41.gif)
![l5](https://user-images.githubusercontent.com/37307454/153056807-4556324e-653a-49df-8eb0-4a38508f32d3.gif)
![l6](https://user-images.githubusercontent.com/37307454/153056737-5503dec8-a8d2-4349-8f2b-4a2df455685f.gif)

## Release History
v1.0 - Release version. 
- Working as intended, can be applied on non hitscan weapons like Kraber,Wingman Elite, Double take but projectile will be broke
---------------------------------------

v2.0 - Color Update
- Added More Color variations : `blue; cyan; golden; green; magenta; orange; purple; pink; red.`
- Can be changed it `"hitscan_weapon_laser.txt"` and `"projectile_weapon_laser.txt"`
---------------------------------------
v2.1
- Added `yellow, white and rgb` colors
- Added sizes options for colors `5,10,20,30,40` `_path_first_` is `16` `_path_` is `32`
---------------------------------------
v2.2
- `Kraber and Wingman Elite` now have Custom Lasers `kraber_weapon_laser` and `wingman_weapon_laser` in WeaponLaser>mod>scripts>weapons
---------------------------------------
v2.2.1
- Made laser for Kraber and Wingman Elite better
---------------------------------------
v2.2.2
- Laser was added to `Mastiff Mozambique(bad visual compare to other wapons) Thunderbolt, Archer, Softball, MGL and Doubletake`

---------------------------------------
v2.3.0
- Laser was remover fot `Thunderbolt` due to crashes
- Added laser sizes for light blue `CH_grenade_arc_proto_path_first`
- Added laser for Titan weapons: `XO-16 for Monarch, Predator Cannon for Legion, Laser Shot for Ion, Energy Shot for Monarch`
- Added more size variation `50, 60, 70, 80, 90, 100`
---------------------------------------