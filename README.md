rubeJsonToPyBox2D
=================
This module is used for loading pybox2d b2World from R.U.B.E. JSON file to memory.

Usage
=================
from rubeJsonToPyBox2D import createWorldFromJson

createWorldFromJson("b2world.json")

Dependencies
=================
Created with:
 - python 2.7.5
 - pybox2d ver. 2.3b0
 - R.U.B.E. 1.4

Documentation and references
=================
 pybox2d - https://code.google.com/p/pybox2d/wiki/Documentation
 Box2D documentation comes with Box2D package
 R.U.B.E. JSON structure https://www.iforce2d.net/rube/json-structure

Links
=================
 Sample JSON files can be downloaded somewhere here:
 https://www.iforce2d.net/rube/?panel=loaders

Issues
=================
Polygons and edges work fine.
User data - not implemented.
R.U.B.E images - not implemented.
Motor joint doesn't load properly.
Open chain shapes load with additional edge from last point to first.
Loop chain shapes raise an error.

If you know the cause of these bugs please post an issue or submit fix.
