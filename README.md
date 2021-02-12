# B3D Exporter for Blender 2.79 & Bforartists 1.0.0
**B3Dexport.py 3.4** - A Blender 2.79 / Bforartists 1.0.0 .b3d export script - for OpenB3D/Blitz3D/MiniB3D.  
**License:** gpl-2.0  
Basically the same as the forked MineTest version but just with "Export Textures" enabled by default, as well as a few bugfixes.  

**Changelog:**  
> Version 3.4  
* Added an optional tickbox for exporting only the KeyFrames in the exported file. (Enabled by default, but makes a significantly smaller .B3D file size, however looses the "bezier" interpolation if enabled)  
* Fixed a bug where whenever blender had the first frame as 0, the exported model will crash in OpenB3D/Blitz3D/MiniB3D.  
> Version 3.3  
* Added an optional tickbox for exporting called "Export each object as its own .b3d file".  
* Moved the Object Mode switching code to a more suitable place.  
> Version 3.2.2  
* Fixed a bug where if no object was selected at all, the script would fail when exporting.  
* Updated script help links to point to the issues URL here instead.  
* Updated readme
> Version 3.2.1  
* Fixed an overflow array issue when exported .B3D models are loaded in OpenB3D/MiniB3D.  
* Fixed Textures/Animations not exporting properly if left in Edit/Pose Mode.  
* Bundled in .b3d model format specifications text file.  

**Installation:**  
In your Blender 2.79b or Bforartists application, follow these steps.  
1. Click the **File** tab  
2. Click **User Preferences**  
3. Click the **Add-ons** tab  
4. On the bottom, click **Install Add-on from File...**  
5. Select the downloaded **B3Dexport.py** file  
6. Tick the addon  
7. Click **Save User Settings** and Enjoy!  
