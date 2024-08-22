# Lethal_Company_Automodder
 An automodding script for lethal company by ZeroRickMore, not for commercial use

## How to use

- Open "LETHAL_COMPANY_PATH.txt" and type the path that leads to your Plugins folder inside of Lethal Company - BepinEx Steam folder.  
It looks something like this:  

        C:\SteamLibrary\steamapps\common\Lethal Company\BepinEx\plugins

- Modify MODS_LIST.txt according to your necessity only if necessary.  
You usually do not touch it unless you are picking the mods.

- Just run one of the executables and win.

## Program workflow

- Get mod names and URLs from [GitHub Gist](https://gist.githubusercontent.com/ZeroRickMore/9e17fe424dc5443b7ebe9c86887cdfe9/raw/MODS_LIST.txt) or MODS_LIST.txt

- Get path to lethal company bepinex plugins folder from LETHAL_COMPANY_PATH.txt

- Asks the user if the path is correct and makes sure the user knows the content will be overwritten, and prints subfiles for extra clarity.   
(Old folder will be backed up anyway)

- Backup old plugins folder

- Delete old plugins folder

- Creates a new empty plugins folder 

- Downloads each mod one by one, creating a folder with its name for each

- Finish !

## Autoupdater workflow

- Download program from github repo https://github.com/ZeroRickMore/Lethal_Company_Automodder_Distribution/archive/refs/heads/main.zip

- Extract program

- Move updated automodder_runner.exe and MODS_LIST.txt to the correct folder

- Run automodder_runner.exe in a new terminal window

