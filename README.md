# Vegetation Models for Unity

Unity-compatible 3D models of trees (and eventually other vegetation). At the moment, all models are [CC-0 1.0 from Shapespark](https://sketchfab.com/3d-models/shapespark-low-poly-plants-kit-de9e79fc07b748d1a6ac055b49ee5c67).

Note that these models currently contain `.meta` files to aid with the import into Unity.
Normally, Unity would create these files upon package import in order to avoid GUID collisions and
to ensure files are appropriately referenced; however, due to a bug preventing importing
UnityPackage files from the command line, I haven't figured out how to appropriately force
Unity to create these on import. As a result, these models might break on different Unity versions
and when used with many other assets.


