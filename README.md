# Lethal_Company_Automodder
 An automodding script for lethal company by ZeroRickMore.  

## How to use
First execute `Install_On_Desktop.exe` to get the files on your desktop, then you can completely delete the folder you downloaded from GitHub and just keep that one.  
After doing that, you can follow the next steps, guiding you through what each .exe does.  

- Basically, you will only ever need to click on `automodder_RUNNER.exe` every time you want to update the mods.  
- When told to, you may need to run `automodder_UPDATER_and_RUNNER.exe`, for important software updates.  
- If you mess up the files (will not happen if you just click on the .exe files), you can rollback to the default state by running `automodder_RESETTER.exe`.

Please note that the mods list is found at the [GitHub Gist](https://gist.githubusercontent.com/ZeroRickMore/9e17fe424dc5443b7ebe9c86887cdfe9/raw/MODS_LIST.txt), so if you want a completely customizable experience with being able to choose your mods, let me know, and I'll implement it.  

As of now, only the owner of the GitHub Gist (me) can choose the mods being downloaded and managed.

### automodder_RUNNER.exe
 ```
 The core of the automodder, runs the sequence to download and update the mods found at [GitHub Gist](https://gist.githubusercontent.com/ZeroRickMore/9e17fe424dc5443b7ebe9c86887cdfe9/raw/MODS_LIST.txt)
 ```

### automodder_UPDATER_and_RUNNER.exe
 ```
 Updates everything fetching from this repository, and runs automodder_RUNNER.exe right after.
 Useful if you want to stay up to date.
 ```

### automodder_RESETTER.exe
 ```
 Useful if you touched something you did not have to touch or deleted some files by accident.
 Restores the original state of your automodder so that you can run it cleanly right after.
 ```
