![Loading screen 4](https://github.com/Gallahorn/Ultraviolence/assets/13502434/17f09e42-3cac-4ff8-bf04-130578da4acd)
<br>
<br>
<br>
<br>

## Quicklinks

- [Install with GOG version](https://github.com/Gallahorn/Ultraviolence/blob/main/Advanced%20features.md#installation-with-gog-version)
- [How to update the list](#how-to-update-the-list)
- [How to use tattoos and body overlays](#how-to-use-tattoos-and-body-overlays)
- [Resetting mods](#resetting-mods)
- [How to unlock romance options](#how-to-unlock-romance-options)
- [How to use paired poses](#how-to-use-paired-poses)
- [Important Keybinds!!!](#keybinds)

<br>
<br>
<br>
<br>

# Installation with GOG version.

## Make sure you have all DLC installed.
    If you dont have REDmod go to the store and "buy" it its free.
    Then launch the game once and login to Redlauncher if prompted for it.
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/2c140828-c499-485b-a7e6-79618879d2f9)

## Enable modding.
    Then you need to enable modding under Features section in GOG.
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/51e78720-5059-4467-8538-a31c693ba24d)

## Then continue from [here](https://github.com/Gallahorn/Ultraviolence/tree/main?tab=readme-ov-file#make-sure-you-read-everything-here-and-do-everything).

<br>
<br>
<br>
<br>

![Updatelist](https://github.com/Gallahorn/Ultraviolence/assets/13502434/ebfd59a4-3064-4ebf-b6b5-08c28908265f)




# How to update the list:

## Before you update your list
    Before you update your list you need to do some things to make sure things goes smoothly.
    You will need to backup some files from overwrite. The files you need to backup are:
    
    Stocks/data/persistent

    And you back them up like this in the image:
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/4777ff5a-2701-4ca1-b467-aba4b858d967)

    Then you should clear out overwrite 

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/a222e637-437e-4553-b28c-d71fe3168342)

## After that you will need to go do [Step 1](https://github.com/Gallahorn/Ultraviolence/assets/13502434/4777ff5a-2701-4ca1-b467-aba4b858d967) in the main readme.

    Very important to do this step to make sure your game folder is clean.

## Updating your list

    To update your list you just need to start Wabbajack like normal and install the list with overwrite checked
    and the install paths pointing to the right folder same with the download folder.
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/08397dfc-23be-4725-af9d-167c0050d5d2)

## After you updated the list you might need to re-order your tattoos or overlays again. Check below for instructions.

## Make sure Lizzies Braindance and Romance messages Extended are working.

    Also make sure you always after every update go back to H10 and you should get a popup about Lizzies Braindances 
    when you enter the apartment and you need to turn on the TV and you should get a message about 
    Judy Romance Messages Extended and Panam Romance Messages Extended. 
    If that dont happen leave the apartment and enter again.



<br>
<br>
<br>
<br>

![Tattoos and Overlays](https://github.com/Gallahorn/Ultraviolence/assets/13502434/e76f3427-2c73-49a4-95e8-240ed4b454c1)




# How to use Tattoos and Body overlays

    The list currently supports VTK overlays but you can only have ONE active at the time
    and to change it you will need to do the following steps.

## 1. Ensure you are using the default vanilla skin option

    For overlays, the vanilla version of UNIVERSAL SKIN TONE must be selected; other options
    produce visual errors when used with overlays.
    
![image](https://github.com/user-attachments/assets/d95a1d84-1eb0-4cf5-8a02-bebee5aa993b)

## 2. Find the tattoo you like and check it in MO2

    For any mod, you can right-click, and select 'Visit on Nexus' to view the mod on Nexus.
    The name of the mod will correspond to a specific file from the mod's page.

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/9019a472-52e4-406b-9185-51a906a20f3f)

## 3. Open Red4-conflicts and resolve load order

![image](https://github.com/user-attachments/assets/e88584c3-7a5f-4221-a5a1-f010b93d0b65)


        You will need to go to the bottom of the left panel and find your overlays
        and drag them up to the top like in the second image. 
        Currently you can only move the files one at the time.
        The overlays should sit above most files, especially any body or head related files.
        After you moved each of the files, you can close Red4-conflicts and start the game.
        The overlays will always be present on your V, like a layer of skin texture underneath
        tattoo options applied in character creator.
        
![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/c5d6e099-b669-496e-b159-8d13eb372831)

![image](https://github.com/user-attachments/assets/648dc25d-35c1-46ef-bb90-2fc88bfec59d)

<br>
<br>
<br>
<br>

![Resetting](https://github.com/Gallahorn/Ultraviolence/assets/13502434/6f7252a3-0070-414c-93ba-38d630247f1a)

# Resetting mods

## How to reset Lizzies Braindance.

        Sometimes after an update you will need to reset Lizzie's Braindance

        Reseting mod
        If you can't find the NPC for BD inside the Lizzie's, use this CET command to reset the quest:

        Game.GetQuestsSystem():SetFactStr("lizzies_bds_reset", 1)

        Then save the game and load the newly created savegame. NPC should be available again.

        If you don't have any options with the NPC, use this command:

        Game.GetQuestsSystem():SetFactStr("lizzies_bds_active", 0)


<br>
<br>
<br>
<br>

![Romance](https://github.com/Gallahorn/Ultraviolence/assets/13502434/ea4d9da6-6cc8-424a-9dc2-b9d9dcbf2654)

# How to Unlock Romance Options

    To unlock romance options you need to follow the instructions below. At the moment its only Panam to female thats supported.
    You need to do this before you meet Panam so do it at the start of the game.

    1. Open CET

    2. Open Respector and then click Quick Tweaks
<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/89b667d0-9196-4ac3-96da-6e549f1ba0d2)


    3. Write "panam romance" in the search bar then click on the option shown in the image below

<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/19cfccd0-acb2-4ac7-ac97-0315d727de29)

    4. Click on Switch to Yes and make sure the Current State changes to YES and then save and reload the save to make sure it stays.

<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/450cb7c5-d013-454f-9a6e-cff7280485fa)

<br>
<br>
<br>
<br>

![paired](https://github.com/Gallahorn/Ultraviolence/assets/13502434/b0ded6ab-bd70-488c-b2b9-26eba7be7a0f)

<br>

# How to use paired poses

    First open Photomode and enable nibbles
    
<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/5ac6123b-c994-4970-bfcd-1ccae7c80243)

<br>

    Then open CET with what ever key you bound it to and open the AMM menu and 
    go to settings -> Photo Mode Nibbles Replacers and select what type of body 
    you want the replacers to have.
    
<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/e8c15fad-6471-4f45-8729-2ee32095f925)

<br>

    Then Save and reload that save. After that go in to photomode again and enabled the replacer 
    and you will see nibbles looking like a human.
    
    Then you will open CET and AMM again and go to Tools -> Target Replacer then click Open Target Tools
    after that go to Scan tab and pick the main character you want to use. After main character 
    are selected you can change the appearances of that char in the Target Tool Window thats open
<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/166ae7a2-7f3d-447a-9f98-526ee2a711d6)

<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/80375cd4-df74-46d9-87fc-18477936bd2f)

<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/16671e17-199a-43fe-acd5-27c9acb6c093)

<br>

    After that you can close CET and pose the models with making sure the cordinates in photo mode 
    match up between V and Replacer. Some poses only work for certain body types in most cases it 
    will tell you what the pose is for Female, Male or Big Male

<br>

![image](https://github.com/Gallahorn/Ultraviolence/assets/13502434/ae353f66-acdd-4ad3-9e0f-f86d2616afd8)

    
    You can also use strapons from The Rvccon Dumptster or Mr Stud by using the following commands to spice up
    your images.

    Game.AddToInventory("Items.jamiecross_mrstudxl_01",1) -- CC Skin tone 1 
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_02",1) -- CC Skin tone 2
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_03",1) -- CC Skin tone 3
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_04",1) -- CC Skin tone 4
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_05",1) -- CC Skin tone 5
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_06",1) -- CC Skin tone 6
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_07",1) -- CC Skin tone 7
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_08",1) -- CC Skin tone 8
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_09",1) -- CC Skin tone 9
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_10",1) -- CC Skin tone 10
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_11",1) -- CC Skin tone 11
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_12",1) -- CC Skin tone 12
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_13",1) -- Golden
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_14",1) -- Glow Rod
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_15",1) -- Silver
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_16",1) -- Holo Green
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_17",1) -- Holo Red
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_18",1) -- Holo Blue
    
    Game.AddToInventory("Items.jamiecross_mrstudxl_19",1) -- Holo Pink﻿﻿


<br>
<br>
<br>
<br>
<br>

![Keybinds](https://github.com/Gallahorn/Ultraviolence/assets/13502434/77c608e3-c92a-4e06-b075-c0d46e12b45f)




# Keybinds

    CET - 
    
        Should pop up so you can pick it when the game starts.
    
    Flashlight - 
    
        Keybind it to what you want in CET Bindings
    

    LimitedHud - 
    
        F6 to show/hide minimap 
        F8 to show/hide UI after your settings.

    Advanced Driving Controls -
        
        This mod makes the driving a lot smoother and more controller like.
    
        Cars:
            
        Accelerate slower with just W.
        Acclerate Faster With LShift.
        Brake slower with S.
        Brake faster with LCTRL.

        Bikes:
            
        Accelerate slower with just W.
        Acclerate Faster With LShift.
        Brake slower with S.
        Brake faster with LCTRL.
        Lean Forward with UP. (You need to rebind to UP, as LShift doesn't work anymore)
        Lean Backward with DOWN  (You need to rebind to DOWN, as LCTRL doesn't work anymore)

  <!--  Huditor - 
    
        Make sure you turn on the HUD and minimap with the LimitedHud keys before
        trying to move the HUD around.
              
        Shift-U and then arrowkeys left and right to select different objects. 
        Scroll to make them bigger/smaller.
        Drag around with the mouse to move them.
        X to reset all the Widgets.
    -->
<!--    Enchanced Vehicle System

        F1 - Double Tap to toggle power state.
             Hold to turn engine on/off
             Hold Longer after engine stop to trigger headlight shutoff

        F1+1 - Multi tap to toggle single light settings
               1. Headlights 
               2. Tail lights 
               3. Utility lights 
               4. Blinker lights 
               5. Reverse lights 
               6. interior lights
               
               Hold Toggle all lights
        

        F2 - Open doors
             Multi tap toggle single door
             1. Driver 
             2. Front Passanger 
             3. Back Left 
             4. Back Right
             
             Hold Toggle all doors

        F2+2 - Multi tap to toggle hood/trunk/spoiler
               1. Hood 
               2. Trunk 
               3. Spoiler
               
               Hold Toggle hood and trunk

        F3 - Multitap to toggle windows
             1. Driver 
             2. Front Passanger 
             3. Back Left 
             4. Back Right
             
             Hold toggle all windows

        F4 - Press Toggle interior lights
             Hold toggle crystal dome.

        Crystal Coat Key (default key Y)
             2. Toggle crystal coat on/off
             3. Display Color Menu

             Hold Display Color Menu 
        -->

<br>
<br>
<br>
<br>



