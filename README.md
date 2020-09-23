# UnrealEngine-MarketPlace-intructions-Linux
How to access download and install Unreal Engine Market Place assets on Linux..

Note : Run Epic games launcher using Xorg and not Wayland (Choosing Display server when logging in)

Downloading Unreal Engine Marketplace assets on Linux is very simple here are the steps:

1) Download Lutris - lutris.net/downloads

2) Donwloading Epic Games Launcher using lutris

![Screenshot from 2020-09-23 21-48-26](https://user-images.githubusercontent.com/40650341/94040639-d10fcb00-fde6-11ea-943f-073048674aa2.png)

3) Login into the epic games launcher

4) Now here is the main step - inside this directory-   epic-games-store/drive_c/users/yourusername/My\ Documents/
  
  Create a Directory Named ```Unreal Projects``` and inside that create a Directory by any project name lets call it ```Dummy```
  Now Create a ```Dummy.uproject``` file inside the Dummy folder and paste the following into it
  
```   {
	"FileVersion": 3,
	"EngineAssociation": "",
	"Category": "",
	"Description": ""
} 
```
Restart the epic games store if you have already opened it for Epic Games store to detect this Dummy Project.

Now when adding any asset from market place you would be able to add the asset into this Dummy Project which you can copy paste and use on any Unreal Project on Linux.

![Screenshot from 2020-09-23 22-05-08](https://user-images.githubusercontent.com/40650341/94042494-4bd9e580-fde9-11ea-8517-2ab8218ed026.png)

Note: Click Show All toggle when adding asset to the project. And select the engine version in this window 


 
  
  




