# VtolVR-Skalou-HORNET
Skalou's mods for VtolVR

# This repository is for modding the VTOLVR game with a HORNET theme from the VTOL FORMATIONS.  
# Visit the [VTOL FORMATIONS Discord](https://discord.com/invite/VTOLFormations "VTOL FORMATIONS Discord link")  

----------------------------

## Installation

- Download and install [UABEAvalonia](https://github.com/nesrak1/UABEA)

- Download a [release](https://github.com/skalou/VtolVR-Skalou-HORNET/releases) and unzip it in a working folder.  
  Select the "VtolVR-Skalou-HORNET-v.X.X.X.zip" (not the "Source code")
  
- Save the original files that will be modified in VtolVR:  
 Inside the  VtolVR game install repository:  
>  ...\Steam\steamapps\common\VTOL VR\VTOLVR_Data  
     
- save the file: "resources.assets" in a safe place.  
 If you mess with it, you can just delete it and [verify the game install with the steam tool.](https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB) 
 
- Just in case if worried (but we won't touch it), your saved profile should be in:  
>   %userprofile%\AppData\Roaming\Boundless Dynamics, LLC\VTOLVR\SaveData  
     
  
### Replace the needed files with UABEAvalonia:

- Copy/Paste the original "resources.assets" in a working folder and rename into "resources-ORIGINAL.assets"

- here is a short [Youtube tutorial](https://www.youtube.com/watch?v=BkkDR-95mR8) about an other Unity game, we will do the nearly the same.

- Launch the program UABEAvalonia.exe  
- File>Open , find the previously copied file "resources-ORIGINAL.assets" in your working folder.
- In the new opened window "Asset Info" View>Filter, Deselect All, check "Texture2D"  
- Search for the texture to be replaced: (clic on the "Name" column for alphabetical ordering for your mental health)  
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
- So finally, if done correctly, there is only 1 "resources.assets" file with our moddified textures in it.  
- You can launch the game, enjoy, and send us a picture on the [VTOL FORMATIONS Discord](https://discord.com/invite/VTOLFormations "VTOL FORMATIONS Discord link")  

## Contributors

A special thanks to all these people for their help.
- The people I read modding about and spent too many time on it.
-The VtolVR creators
- The Hornet's passionate, including the Guru Jeff
- Me
- My mum
- You


