# VtolVR-HORNET-Skalou

# This repository is for modding the VTOLVR game with a HORNET theme from the VTOL FORMATIONS.  
# Visit the [VTOL FORMATIONS Discord](https://discord.com/invite/VTOLFormations "VTOL FORMATIONS Discord link")  

![HORNET_3.png](/assets/images/HORNET_3.png)

![Hornet-FlightSuit-presentation-01.png](/assets/images/Hornet-FlightSuit-presentation-01.png)

![Hornet-Bobblehead-presentation-02.png](/assets/images/Hornet-Bobblehead-presentation-02.png) ![Hornet-GLoves-presentation-02.png](/assets/images/Hornet-GLoves-presentation-02.png)

![Hornet-Helmet-theGh0st-presentation-02.png](/assets/images/Hornet-Helmet-theGh0st-presentation-02.png)

----------------------------

## Installation

- Download [UABEAvalonia](https://github.com/nesrak1/UABEA)  
  Here is the [releases page](https://github.com/nesrak1/UABEA/releases) with the download link.  
  It's a tool needed to replace some files in the game.  
  If not sure, you probably need "uabea-windows.zip" and the requirements.  
- Unzip it somewhere in a working folder.   
[A Youtube tutorial about UABEAvalonia](https://youtu.be/FZ0XPDhJv74?si=BdtxaVw1L_DBBAVi)  

- Download a [release](https://github.com/skalou/VtolVR-Skalou-HORNET/releases) of this mod and unzip it in a working folder.  
  Select a "VtolVR-Skalou-HORNET-v.X.X.X.zip" (not the "Source code")  
  
 - **Save the original files that will be modified in VtolVR:**  
  Inside the  VtolVR game install repository, by default:  
   ```
   C:\Program Files (x86)\Steam\steamapps\common\VTOL VR\VTOLVR_Data
   ```
	- save the file "resources.assets" in a safe place.  
  
	If you mess with it, you can also just delete it and [verify the game install with the Steam tool.](https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB) 
 
- **Just in case if worried, your saved profile, should be in:**  
   ```
   %userprofile%\AppData\Roaming\Boundless Dynamics, LLC\VTOLVR\SaveData
   ```    
   You can save these files too, for safety. 
   
### Flight suit colors:
   
- In the profile folder: 
   ```
   %userprofile%\AppData\Roaming\Boundless Dynamics, LLC\VTOLVR\SaveData
   ```
   
   You can edit your suit colors with the HORNET settings in the file "pilots.cfg":
		
	[Discord-Flight Suit](https://discord.com/channels/1410252871433453684/1439421813640794244/1439421839137837057)  
   
	```
	suitColor = (0.1646613, 0.1646613, 0.1646613)  	
	vestColor = (0.773757, 0.6258824, 0)  
	gSuitColor = (0.773757, 0.6258824, 0)  
	strapsColor = (0.5186933, 0.5186933, 0.5186933)  
   ```
	
 [Here's a quick video on where to put the values above](https://www.youtube.com/watch?v=eVjFoAYreAY)
	
> [!NOTE]  
> Only put the Suit Color, Vest Color, gSuit Color, and Strap color on  to a Pilot you have already created in game.
  
### Replace the needed files with UABEAvalonia:  

### Using a UABE mod package installer (NEW way):  
A new easier way than manually changing each file is to use a UABE Avalonia mod package installer (the .emip file in the download).  

- Launch the program UABEAvalonia.exe  

![EMIP-install-01.png](/assets/images/EMIP-install-01.png)  
- File>Load Package File, find and select a VtolVR-HORNET-Skalou-EMIP-v.X.Y.Z.emip file previously downloaded >Open  

![EMIP-install-02.1.png](/assets/images/EMIP-install-02.1.png)  
- A new "Load Package" UABE windows open, double-click on the wanted selected changes, it should be marked as "(selected)".  
Select the Base Folder, it's your VtolVR game install directory, by default:  
   ```
   C:\Program Files (x86)\Steam\steamapps\common\VTOL VR\VTOLVR_Data
   ```  
		
![EMIP-install-03.png](/assets/images/EMIP-install-03.png)   
- The UABE program hang for a few seconds, then should open a new windows "Asset Info" windows.  
  File>Save  
  The UABE program hang again for a few seconds for the time to apply the changes but don't tell you when it's finished.  
- You can close all the UABE windows and launch the game.  

### Manual method (OLD way):

- The goal is to replace some textures inside the "resources.assets" file.  

- List of modified objects:

| Obeject  | Asset file | Type |  Name |
| ------------- | ------------- | ------------- | ------------- |
| BobbleHead  | resources.assets  | Texture2D  | tex_bobbleHead  |  
| Gloves  | resources.assets  | Texture2D  | tex_newglove , tex_newglove_spec (if needed)  |
| Helmet | resources.assets  | Texture2D  | hqh_dif  |

### Example with the bobblehead:  

- Here is a short [Youtube tutorial](https://youtu.be/BkkDR-95mR8?si=RCD3OP57SUt8dht7) about an other Unity game, we will do nearly the same.  
- Copy/Paste the original "resources.assets" in a working folder and rename into "resources-ORIGINAL.assets"  
- Launch the program UABEAvalonia.exe  
- File>Open , find the previously copied file "resources-ORIGINAL.assets" in your working folder.
- In the new opened window "Asset Info" View>Filter, Deselect All, check "Texture2D"  
- Search for the texture to be replaced:  
  Clic on the "Name" column for alphabetical ordering for easier search  
- Clic on the needed texture to be replaced, then clic "Plugins/Edit Texture/OK"  
- On the new opened window, clic "Load", find the corresponding moded texture ("tex_bobbleHead-Hornet-Skalou-vX.Y.Z.png" etc...) in the previously downloaded and unzipped folder (are you organized?)  
- Clic "Save", it should close the "Texture Edit" window.  
- Save: in the "Asset Info" window (not the "UABE" window) : File>Save As... (resources-Hornet-XX.assets if you are not inspired)  
- Export the newly created file to the VtolVR game install (inside ...\VTOL VR\VTOLVR_Data)  
- Delete the original "resources.assets"  (you previoulsly saved it in a safe place, right ?)  
- Rename your newly imported "resources-Hornet-XX.assets" into "resources.assets"  
- So finally, if done correctly, in the "VTOLVR_Data" game folder, there is only 1 "resources.assets" file with our modified textures in it.  
- You can launch the game, enjoy, and send us a picture on the [VTOL FORMATIONS Discord](https://discord.com/invite/VTOLFormations "VTOL FORMATIONS Discord link")  

   
> [!NOTE]  
> For now, only the base game aircrafts and the T-55 are affected for the Bobblehead, not the DLC (EF-24G and AH94),
> maybe doable by modifying the DLC files, but I haven't tried.
  

## Contributors

A special thanks to all these people for their help.
- The people I read modding about and spent too many time on it.
- The VtolVR creators
- The Hornet's passionate, including the Guru Jeff
- Me
- My mum
- You,  
  you can download the ressources from this Github,
  there are saved textures in .pnd format with layers for [PAINT.NET](https://www.getpaint.net/) and also an exported version for Photoshop .psd (I don't have it),  
  modify as you will. 
  
  


