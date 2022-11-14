# DonaldDuck-HD-Texture-Pack
An AI upscaled texture pack for Donald Duck: Goin' Quackers/Quack Attack.

Credits to RayCarrot for figuring out how to increase the ```TMPFixMemory``` value in "Game.dsb".

# Instructions on how to import the source textures into a Textures.cnt file:
Get the latest version of [Rayman Control Panel](https://github.com/RayCarrot/RayCarrot.RCP.Metro/releases).

Go to the "Utilities" tab and open the "Textures.cnt" file. It should be located in the "Data" folder of Donald Duck: Goin' Quackers.

Right click on the folder that contains the texture(s) you want to replace and click "Import & convert". If you want to replace textures in multiple folders just right click the root directory and import there. 

Once you've saved your changes make sure to sync the texture info before you start the game. "Utilities>Other" select the "Data" folder when syncing.

**IMPORTANT!!! Make sure you include the edited "Game.dsb" file before you release your texture pack!** The default "Game.dsb" file limits the texture memory causing the game to crash when loading higher resolution textures.
