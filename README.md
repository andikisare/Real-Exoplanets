# Real Exoplanets
 Version: 0.9.6
License: All Rights Reserved

### Installation Instructions for Use with the Stock Solar System
1) Dependencies (install these before Real Exoplanets)
	- Kopernicus
	- Module Manager
	- Modular Flight Integrator	
2) After REX's dependencies have been installed, install Real Exoplanets by extracting the "RealExoplanets" and "REX-Textures" files into the KSP GameData folder.
3) (Optional) For visuals to function, you must install SVE.
	
### Installation Instructions for Use with RSS
1) Dependencies (install these before Real Exoplanets)
	- Real Solar System
	- Kopernicus
	- Module Manager
	- Modular Flight Integrator
2) After REX's dependencies have been installed, install Real Exoplanets by extracting the "RealExoplanets" and "REX-Textures" files into the KSP GameData folder.
3) (Optional) For visuals to function, you must install RSSVE.

### Using the Settings File
The settings file for REX is located in RealExoplanets/Settings.cfg. It can be used to do the following:
	1) Set custom scale factors
	2) Enable or disable systems to your desire
	3) Enable or disable stock-alike names
- Explanation of each setting:
	- "stellarDistanceScale:NEEDS[RealSolarSystem]" - sets the scale factor for stellar distances when using RSS. A value of 10 would mean stars are 10 times further away than in real life.
	- "stellarDistanceScale:NEEDS[!RealSolarSystem]" - sets the scale factor for stellar distances when RSS is NOT installed.
	- "sizeScale" - scale factor for all distances, including planetary radii, when RSS is NOT installed.
	- "massScale" - scale factor for all masses when RSS is NOT installed.
	- "atmoScale" - scale factor for atmosphere heights when RSS is NOT installed.
	- "rotScale" - scale factor for rotational periods when RSS is NOT installed.
	- "[SystemName]" - enables or disables the respective stellar system.
	- "stockNames" - enables or disables stock-alike names when RSS is NOT installed.
