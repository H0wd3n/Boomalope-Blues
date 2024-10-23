· [Requirements](https://github.com/H0wd3n/Boomalope-Blues/blob/main/Requirements.md) - [Install Instructions](https://github.com/H0wd3n/Boomalope-Blues/blob/main/Install-Instructions.md) - [Readme](https://github.com/H0wd3n/Boomalope-Blues/blob/main/README.md) - [Changelog/Updating](https://github.com/H0wd3n/Boomalope-Blues/blob/main/Updating%20-%20Changelog.md) - [Steam Collection](https://steamcommunity.com/sharedfiles/filedetails/?id=2950431243) ·
# Install Instructions
## The first step is of course make sure you have Rimworld installed through Steam and make sure any mods you already have are disabled.
- After that right click the game on steam, go to properties -> local files and verify integrity of game files to make sure Rimworld is installed correctly.
-Once the file verification is finished launch the game through steam and get to the main menu and then close the game.

## Downloading and installing the Rimworld mod manager called Rimsort. 
- This step is non-negotiable as it is how I mod Rimworld and it provides a way to edit your modlist externally without loading the game every time you make a change, has a nice interface, allows you to convert textures from mods to the .dds format which the game has a better time loading, save modlists incase you want to back them up and have multiple lists, and the most important part is sorting the mod load order efficiently with one button.
- You can download it [here]([https://github.com/rimpy-custom/RimPy/releases/tag/1.2.6.28](https://github.com/RimSort/RimSort)). Make sure you grab RimSort-v1.0.10-Windows_x86_64.zip if you are on windows.
- Once you have it downloaded make a folder in a place of your choosing and extract the contents using 7zip or whatever other program you use for zip files. You can delete the original zip after extracting if you wish.

## Using Rimsort
- Now from the folder you extracted Rimsort find the exe named Rimsort.exe and launch it. (I recommend creating a shortcut wherever you prefer to launch it quickly)
- After launching the program for the first time it will ask you to setup the path of where the game is installed and the config.
- The game location is where it is currently installed through Steam.
- The config location is in: C:\Users\*Your user name*\AppData\LocalLow\Ludeon Studios\RimWorld by Ludeon Studios\Config
- The Steam mods location should be: *Drive rimworld is installed on*:\SteamLibrary\steamapps\workshop\content\294100
- Lastly you The local mods location should be: *Drive rimworld is installed on*:\SteamLibrary\steamapps\common\RimWorld\Mods
- You can use autodetect but sometimes it does not always work.
- If Rimsorty says its undable to find SteamCMD click yes to set it up.
- Next at the top of Rimsort click the file tab and then click settings. Next click the databases tab and then here you need to click the option for Github on both and then click download. If it asks you to install git go ahead and click yes to open up the download page and install it. 
- After that restart Rimsort. 
- Last, go back to the databases tab and then click download button. If you ever open up Rimsort and it says something about the database being out of date do this step again and click update existing.

## Installing Performance Fish and Fishery - These are the only two local mods you will need to install.
- Performance Fish can be downloaded here: https://github.com/bbradson/Performance-Fish. Click the green code button at the top and then click "Download Zip".
- Fishery can be downloaded here: https://github.com/bbradson/Fishery. Click the green code button at the top and then click "Download Zip".
- After those are both downloaded go to the local mods folder for Rimworld and extract them both there. If you have Rimsort open click the resfresh button for the two new mods to show up.

## Downloading the rest of the mods
- Go to [this Steam workshop collection](https://steamcommunity.com/sharedfiles/filedetails/?id=2950431243) and click subscribe to all. This will download the rest of the mods through steam. Once that is finished, you can head to the next step.

## Installing the list 
- Now, after all the mods are downloaded through steam refresh Rimsort again and then click File at the top -> Import -> From Rentry.co. Now paste this link in the text box: https://rentry.co/but5hwau/
- Don't worry about any warnings those are alright. If there are any errors you may have done something wrong.
- Now all the mods should have been sorted and be in the Active tab( the left). Click sort again just to make sure the list is sorted correctly.

## If you do not own any of the dlc and just the base game you will need to disable the mods that require the dlc to work.

### Now click sort and then save. You're not done yet though!
## Converting Textures to .dds
### Now this part can take some time depending on your hardware.
- On the top of Rimsort click File -> Settings -> todds. On this page make sure the quality preset is set to "Optimized - Recommended for Rimworld". and then click the option that says Optimize active mods only and then click ok.
### Do know this step will probably use 100% of your CPU and cause it to get very warm, don't freak out just let it do its thing.
- As I mentioned before this process can take time, so be patient and let it finish.
- Now click the Textures tab at the top of Rimsort and then click "Optimize textures".
- Once it has finished you will see "Subprocess completed." You can now click the X to close that tab.
- Click the blinking refresh symbol once again and then click  sort, and then save.

##  Congrats! You have installed the modlist and everything is finished. I hope you enjoy it!
 - Don't worry about getting a few errors on startup. It's mostly normal for that to happen unless you see a giant wall of red text then something broke. Also if you are getting constant errors in-game and it is tanking your performance something is wrong.
 - Last thing, if you ever for whatever reason verify the games files on Steam after you finish this list you will have to do the texture conversion step again!
