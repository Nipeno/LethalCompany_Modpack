# HDLethalCompany V1.3.0 - Sligili | CLIENT SIDE 🎈

## INSTALLATION 🛠
### Extract on the main game folder (where ```Lethal Company.exe``` is located). Make sure you have [BepInEx](https://github.com/BepInEx/BepInEx) installed

## CONFIGURATION ⚙
### Open ```BepInEx/config/HDLethalCompany.cfg``` with a text editor.

📃*This mod maintains the vanilla rendering aspect ratio ***to avoid breaking any HUD elements***.  
Calculate the value equivalent to your desired resolution -> ```DesiredResolutionWidth/860```*

- **RESOLUTION SCALE:** Set ```value``` to any number between ```1.000``` - ```4.500``` (The UI scanned elements have slightly incorrect offsets after 3.000)
  - ***0.923*** -> ***800x480*** (*Increases performance*)
  - ***1.000*** -> ***860x520*** (*Vanilla resolution*)
  - ***1.488*** -> ***1280x720*** 
  - ***2.233*** -> ***1920x1080*** (*Default mod resolution*)
  - ***2.977*** -> ***2560x1440*** 
  - ***4.465*** -> ***3840x2060*** 

- **POST-PROCESSING:** Set ```EnablePP``` to ```true``` or ```false``` - if false, disables the HDRP Custom Pass, therefore disabling color grading

- **VOLUMETRIC FOG QUALITY:** Set ```FogQuality``` to any of the following values ```0``` ```1``` ```2``` ```3``` - modifies the volumetric fog budget
  - ***0*** -> ***VERY LOW*** (*Lower than the Vanilla preset, increases performance*)
  - ***1*** -> ***LOW*** (*Vanilla preset and the default mod value*)
  - ***2*** -> ***MEDIUM*** 
  - ***3*** -> ***HIGH*** (*Can really impact performance at high resolutions*)

- **VOLUMETRIC FOG:** Set ```EnableFOG``` to ```true``` or ```false``` - if false, disables the HDRP Volumetric Fog. **Use this as a last resource in case lowering the fog quality is not enough to get decent performance**

- **ANTI-ALIASING:** Set ```EnableAA``` to ```true``` or ```false``` - if true, enables built-in SMAA

## CHANGELOG 🕗

- ***v1.3.0:***
     - The scanner should work now
     - Added a new parameter **Texture Quality** 
     - The DLL has been renamed
- ***v1.2.0:***
     - SMAA actually works now (UwU)
     - Added a new parameter **Fog Quality** 
     - Now the resolution scale multiplier value can go up to ```4.500``` without breaking the scanner (too much)
- ***v1.1.2:*** 
     - Read Me formatting :P
- ***v1.1.1:*** 
     - Fixed some typos
- ***v1.1.0:*** 
     - Fixed scanned elements not scaling correctly with the resolution
- ***v1.0.0:*** 
     - Release, broken version