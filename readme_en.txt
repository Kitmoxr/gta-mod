//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
//ENBSeries is a set of graphical modifications for games
//Description on the web page may not be equal to this info.
//created by Boris Vorontsov http://enbdev.com
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

PUBLISHING BINARY FILES OF ENBSERIES ON NEXUS SITES (TES NEXUS, SKYRIM NEXUS, ETC)
IS STRICTLY PROHIBITED. ONLY PRESETS AND SHADERS CAN BE HOSTED THERE.



ENBSeries v0.275 for GTA 5 (graphic mod).

Added high quality antialiasing for vehicles as new parameter in enblocal.ini and it's
require msaa to be enabled in game video options. Fixed bug with midnight time of the
day reading.



WARNING!
Set game video options to DirectX11 mode. Also mod is tested for almost maxed graphics
setting, so it may fail to work properly otherwise.
Do not run the game in online mode with ENBSeries installed, i'm not sure if you will
be banned or not.

//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
//CHANGES LOG
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Version 0.274:
Added programmable external shader for light sprites enblightsprite.fx, check shader
editor window for parameters of example. Added two types of light sprites which
works only when external shader is disabled. Added IgnoreDamageLimits parameter
to enblocal.ini.

Version 0.273:
Added parameters for spot and vehicle lights. Added patched compiler library for
upcoming features of the mod.

Version 0.272:
Added parameters for clouds and vehicles. Added time of the day separation to
split parameters in to dawn, sunrise, day, sunset, dusk and night modes. Weather
parameters are not used yet, so ignore them.

Version 0.271:
Added controls of night sprites and some others. Added parameter to turn on high
quality antialiasing, which require msaa to be active in game video options.

Version 0.270:
Added fps limiter, forcing vsync, fix for moon lit direction, some sky and lights parameters.



//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
//INSTALL
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Extract files from folder WrapperVersion to your game folder, where game execution file exist.



//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
//PROBLEMS
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
If game crashing or work not as expected, make sure you are not running XFire, Afterburner,
EVGA, other kind of tools and overlays (crapware). Antiviruses and various fake boosters
also affect mod wrong way. NVidia GeForce Experience can produce issues with the mod,
same with Steam Overlay enabled in-game.



//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
//
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
http://enbdev.com
Copyright (c) 2007-2015 Vorontsov Boris (ENB developer)



//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
//USED THIRD PARTY CODE/MIDDLEWARE AND THEIR LICENSES (THESE ARE NOT MOD LICENSES)
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Using AntTweakBar
Copyright (C) 2005-2015 Philippe Decaudin
AntTweakBar web site: http://www.antisphere.com



Using 3Dmigoto
3Dmigoto authors: Chiri, Bo3b Johnson, Ulf Jalmgrant (AKA Flugan), Ian Munsie (AKA DarkStarSword)

The MIT License (MIT)

Copyright (c) 2014-2015 the 3Dmigoto project authors (see the file AUTHORS.txt
for a complete list)

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
