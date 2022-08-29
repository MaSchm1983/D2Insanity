# D2 Insanity - a Diablo2: Resurrected single player mod

This is a mod for D2R single player which is based in the outstanding good mod from BTneanderthal called [BTDiablo](https://github.com/BTNeandertha1/BTDiablo). I added some features myself, you can find a full list in this Readme file. I also reworked most uniques and sets as well as runeword. I'll list all runeword changes here and add all changes to uniques and sets later because this will be a lot of work todo, but just find them and see how they changes. If they seem to work no properly or are not balanced enough or too overpovered feel free to make some comments here within the Issue section. 

# Table of Contents
1. [Installation](https://github.com/MaSchm1983/D2Insanity#Installation)
2. [Bugs and Issues](https://github.com/MaSchm1983/D2Insanity#Known-bugs-and-issues)
3. [General Changes](https://github.com/MaSchm1983/D2Insanity#General-changes)
4. [Area changes](https://github.com/MaSchm1983/D2Insanity#Area-changes)
   - [General area changes](https://github.com/MaSchm1983/D2Insanity#General-area-changes)
   - [TC85 and higher areas](https://github.com/MaSchm1983/D2Insanity#mlvl-85-and-higher-areas)
5. [Item Changes](https://github.com/MaSchm1983/D2Insanity#Item-changes)
   - [Uniques](https://github.com/MaSchm1983/D2Insanity#Uniques)
      - [New uniques](https://github.com/MaSchm1983/D2Insanity#New-uniques)
      - [Changed uniques](https://github.com/MaSchm1983/D2Insanity#Changed-uniques)
   - [Sets](https://github.com/MaSchm1983/D2Insanity#Sets)
      - [New sets](https://github.com/MaSchm1983/D2Insanity#New-sets)
      - [Changed sets](https://github.com/MaSchm1983/D2Insanity#Changed-sets)
   - [Runewords](https://github.com/MaSchm1983/D2Insanity#Runwords)
      - [New runewords](https://github.com/MaSchm1983/D2Insanity#New-runewords)
      - [Changed runewords](https://github.com/MaSchm1983/D2Insanity#Changed-runewords)

## Installation
Within this mod you can find a bunch of new items, all items reworked, new sets, new content areas, increased monster density, quality of life changes and more. 
So play the mod you need to download the mod. After downloading you need to create a folder called "mod" in your D2R folder. It might look like

````bash
D:\Diablo II Resurrected\mods\
````
Unpack the zip folder into the mods folder. 
````bash
D:\Diablo II Resurrected\mods\D2Insanity
````
Now open your battle.net luncher and go to the D2R tab. Before lunching, click on the settings right next to the play now button and chose "game setting". Klick on "additional commands"
In this next feld you need to type
````bash
-mod D2Insanity -txt
````
Now lunch the game. You'll notice that your older SP saves are not available now. This is just because the mods using another folder to save the characters, which is good, cause we don't want to override old SP progress in vanilla D2R. Now you can create a new character and play the mod. 

You will notice, that all settings from your typically D2R experiance are resetted (sound, keybindings and so on). In addition to that, a feature of this mod is, that you have 3 additional stash tabs. But you will also notice, that those cannot be used yet. So fix both problems, the last step is, to find the new save game folder for this mods. Usually you find the D2R save games in your user folder in win10
````bash
C:\Users\<username>\Saved Games\Diablo II Resurrected\
````
you can see the new folder "mods" here. Go to the "D2Insanity" folder and you'll find the new character here. You need to copy the file "SharedStashSoftCoreV2.d2i" to this folder. The reason is, that this file now has 3 additional "byte sequences" to unlock storage for the new stash tabs. You can also copy and paste the "settings.json" and "custom.key" from your regular savegame folder ("C:\Users\<username>\Saved Games\Diablo II Resurrected\" to the "mods\D2Insanity" folder to rock the mod with your known settings from D2R vanilla. 

Have fun with testing the game and plz feel free to report bugs and issues here via. new Issues. 

Cheers.

## Known bugs and issues



## General changes

* reduced stamina drain
* Change resistance penalty on nightmare and hell from -40/-100 to -50/-120
* Change death EXP penalty on normal, nightmare and hell from 0/5/10 to 5/10/15
* Change maximum static field effekt on normal, nightmare and hell from 0/33/50 to 20/40/60
* Removed portal, armor, fire, explosion and poison shrines
* Increased chance of skill and gem shrines to appear
* Increased duration of xp, skill, combat and mana reg shrines.
* Increased stack size of tomes from 20 to 50 and keys from 12 to 50
* Increased size of horadric cube
* Including a loot filter
* Including merc to wear gloves, belts, shoes, an amulet and one ring



--------------------


## Area changes


### General area changes
* increase monster density on normal, nightmare and hell by 10%/20%/20%
* increase mlvl in cows from 81 to 83 and added an additional increase monster density in cows hell by 30% instead of 20%
* increase the occurance of champion packs, mainly on nightmare and hell difficulty
* mini uber areas (Matron's Den, Forgotten Sands and Furnace of Pain) now are lvl 85 areas
* Act 2 spawning point after login and traveling with Meshif is now between Lysander and Fara.
* Act 2 town portal now spawns near waypoint
* Act 3 spawning point after login and traveling with Meshif is now between Ormus and Cain
* Act 4 chest is now in front of the roof and Cain is near Jamella
* Act 5 Cain is now near the spawning point

### mlvl 85 and higher areas
* Act 1 Crypta
* Act 1 Mausoleum
* Act 1 Catacombs level 3 and 4

* Act 2 Stony Tombs
* Act 2 Maggot Lair lvl 1, 2 and 3
* Act 2 Ancient Tunnels

* Act 3 Arachnid Lair
* Act 3 Swampy Pit lvl 1, 2 and 3
* Act 3 Sewer lvl 1 and 2
* Act 3 Ruined Temple
* Act 3 Disused Fane
* Act 3 Forgotten Reliquary
* Act 3 Ruined Fane
* Act 3 Disused Reliquary
* Act 3 Durance of Hate lvl 2 and 3

* Act 4 River of Flame
* Act 4 The Chaos Sanctuary

* Act 5 Frozen River
* Act 5 Drifter Cavern
* Act 5 Icy Cellar
* Act 5 Abaddon
* Act 5 Pit of Acheron
* Act 5 Infernal Pit
* Act 5 Worldstone Keep lvl 1, 2 and 3
* Act 5 Throne of Destruction

-----------------
## Item changes

### Uniques

#### New uniques
* Ring: High Heavean's Blessing (ilvl85, lvl70 req): 
    - 10%-20% faster cast rate
    - 5-15 to all attributes
    - 20%-30% cold resist
    - 20%-30% poison resist
    - cannot be frozen
    - 20% Better change of getting magic item

#### Changed uniques
* Trollhunter's Glory: Added 18% change to cast lvl 10 amplified damage on hit.
* The Redeemer:
    - 2-3 Paladin Skills
    - 20%-30% faster cast rate 
    - 40 to mana
    - Requirements -60%
    - 2-4 to Redemption
    - 2-4 to Holy Bolt
    - +3 to light radius
    - Mana after each kill 2-4
* Wraithflight:
    - 8% chance to cast lvl 12 amplified damage on hit
    - 190-250 enhanced damage
    - 20%-30% increased attack speed
    - 9%-13% life steal
    - mana after each kill 10-15
    - replanish quantity
    - ethereal
* Giant Skull
    - 30%-60% enhanced damage
    - 25-35 to strength
    - 20%-30% chance of crushing blow
    - 50-100 to life
    - socketed 1-3
* Verdungo's: Removed maximum Stamina, added +10 increased attack speed
* Nosferatu's Coil    
    - +20% increased attack speed
    - +10-20 to Strength
    - mana after each kill 2-4
    - slow enemy target by 10%
    - 3%-6% life steal
    - +10% chance of open wounds
* Firelizard's Talons
    - 2-3 to Assassin Skills
    - 2-3 to Wake of Fire
    - 20%-40% increased attack speed
    - -5 to -10 to negative enemy fire resistance
    - 40-60 to mana 
    - 40-70 to fire resistance
    - 10%-30% Better change of getting magic item
* Eschuta's Temper: Added 5-10 to negative enemie fire and light resistance

--------------

### Sets

#### New sets


#### Changes sets


### Runewords
- Removed spirit runeword for shields
- new runeword "purity" for 4os shields (changed former spirit)
- spirit now works for staves and secpters as well

#### New runewords

- Madness: SolIoEth, Helmet
    - 20% increased attack speed
    - 3%-6% lifesteal
    - 12% faster hit recovery
    - 10%-20% enhanced damage
- Purity: MalGulHelAmn, Shield
    - +2 to all skills
    - 30%-40% faster cast rate
    - lvl 5-10 cleansing aura
    - 48% faster hit recovery
    - +69-92 to mana 
    - +25 to vitality
    - + 35 lightning resistance


#### Changed runewords

- Spirit: Only works for weapons, staves and scepters now. 
    - reduced faster hit recovery to 48%
    - reduced mana to 50-70
    

