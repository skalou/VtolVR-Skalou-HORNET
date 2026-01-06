# VtolVR-Skalou-HORNET
Skalou's mods for VtolVR

# This repository is for modding the VTOLVR game with a HORNET theme from the VTOL FORMATIONS.  
# Visit the [VTOL FORMATIONS Discord](https://discord.com/invite/VTOLFormations "VTOL FORMATIONS Discord link")  

![Hornet-Bobblehead-presentation-02.png](/assets/images/Hornet-Bobblehead-presentation-02.png)

![Hornet-GLoves-presentation-02.png](/assets/images/Hornet-GLoves-presentation-02.png)
----------------------------

## Installation

- Download and install [UABEAvalonia](https://github.com/nesrak1/UABEA)

- Download a [release](https://github.com/skalou/VtolVR-Skalou-HORNET/releases) of this mod and unzip it in a working folder.  
  Select a "VtolVR-Skalou-HORNET-v.X.X.X.zip" (not the "Source code")  
  
 - **Save the original files that will be modified in VtolVR:**  
  Inside the  VtolVR game install repository:  
   ```...\Steam\steamapps\common\VTOL VR\VTOLVR_Data```
	- save the file "resources.assets" in a safe place.  
  
	If you mess with it, you can also just delete it and [verify the game install with the Steam tool.](https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB) 
 
- **Just in case if worried, your saved profile, should be in:**  
   ```%userprofile%\AppData\Roaming\Boundless Dynamics, LLC\VTOLVR\SaveData```
   
   Here you can change your suit colors with the Hornet settings:  
   [Discord-Flight Suit](https://discord.com/channels/1410252871433453684/1439421813640794244/1439421839137837057)  

	```
	suitColor = (0.1646613, 0.1646613, 0.1646613)  
	
	vestColor = (0.773757, 0.6258824, 0)  
	
	gSuitColor = (0.773757, 0.6258824, 0)  
	
	strapsColor = (0.5186933, 0.5186933, 0.5186933)
   ```

  NOTE!!!! Only put the Suit Color, Vest Color, gSuit Color, and Strap color on  to a Pilot you have already created in game.
  
### Replace the needed files with UABEAvalonia:

- The goal is to replace some textures inside the "resources.assets" file.  

- Copy/Paste the original "resources.assets" in a working folder and rename into "resources-ORIGINAL.assets"

- here is a short [Youtube tutorial](https://youtu.be/BkkDR-95mR8?si=RCD3OP57SUt8dht7) about an other Unity game, we will do nearly the same.

- Launch the program UABEAvalonia.exe  
- File>Open , find the previously copied file "resources-ORIGINAL.assets" in your working folder.
- In the new opened window "Asset Info" View>Filter, Deselect All, check "Texture2D"  
- Search for the texture to be replaced:  
  Clic on the "Name" column for alphabetical ordering for your mental health  
	- for the bobblehead: tex_bobbleHead  
	- for the gloves: tex_newglove  
	- etc...  	
- Clic on the needed texture to be replaced, then clic "Plugins/Edit Texture/OK"  
- On the new opened window, clic "Load", find the corresponding moded texture ("tex_bobbleHead-Hornets-XX.png" etc...) in the previously downloaded and unzipped folder (are you organized?)  
- Clic "Save", it should close the "Texture Edit" window.    
- Save: in the "Asset Info" window (not the "UABE" window) : File>Save As... (resources-HornetXX.assets if you are not inspired)  
- Export the newly created file to the VtolVR game install (inside ...\VTOL VR\VTOLVR_Data)  
- Delete the original "resources.assets"  (you previoulsly saved it in a safe place, right ?)
- Rename your newly imported "resources-HornetXX.assets" into "resources.assets"  
- So finally, if done correctly, in the "VTOLVR_Data" game folder, there is only 1 "resources.assets" file with our modified textures in it.  
- You can launch the game, enjoy, and send us a picture on the [VTOL FORMATIONS Discord](https://discord.com/invite/VTOLFormations "VTOL FORMATIONS Discord link")  

## Contributors

A special thanks to all these people for their help.
- The people I read modding about and spent too many time on it.
- The VtolVR creators
- The Hornet's passionate, including the Guru Jeff
- Me
- My mum
- You,  
  you can download the ressources from this Github,
  there are saved textures in .pnd format with layers for [PAINT.NET](https://www.getpaint.net/) and also exported for photoshop .psd (I don't have it),  
  modify as you will. 
  
  


