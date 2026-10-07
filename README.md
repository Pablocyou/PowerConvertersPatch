# PowerConvertersPatch
A patched .class for PowerConverters 1.3.4 to work with Buildcraft 3.1.5


Grab your copy of PowerConverters 1.3.4, delete powercrystals/powerconverters/TileEntityEngineGenerator.class, and replace it with the one in the patch zip.

You are good to go! It also fixes bricked worlds by using the original version with Buildcraft 3.

The original version is only compatible with Buildcraft 2.2, since 3.x changed the method useEnergy to use floats instead of ints.

This patch casts as float on the PowerConverters side of the code.
