rubeJsonToPyBox2D
=================
This module is used for loading pybox2d b2World from R.U.B.E. JSON file to memory.

**Attention**: while this module provides function to load b2World, original RUBE loader allows much more: replicating/retrieving objects, custom properties, images etc. See http://www.iforce2d.net/b2djson/ for the overview.

Usage
=================
from rubeJsonToPyBox2D import createWorldFromJson

b2_world = createWorldFromJson("b2world.json")

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
 - User data - not implemented.
 - R.U.B.E images - not implemented.
