**Shapes2D** is a useful Unity tool for easily creating art assets in the Unity editor. This Shapes2D fork attempts to implement several temporary fixes:   
  * Added anti-aliasing toggle support for fixing the blurry sprites after export;
  * Introduced resolution multiplier in order to get rid of the pixelation in shapes;
  * Resolved problems with polygon/path editor in 3D scene view;
  * Fixed corner rounding issues on camera screen space;
  * Patched the unloded (invisible) sprites issue after initiating the shapes;
  * Fixed incorrect colors on linear color space;
  * Added some useful tips and links in the inspector to save you from many headaches.
 
Known issues:
  * Overlapping masks (one solution is to export the sprite).

Untested:
  * 2D shapes;
  * World Space Canvas Preview.

Please note that this is highly experimental and it may produce further bugs. Please take a backup before updating to this version. If you continue to experience further issues, you should revert to the official [stable](https://https://github.com/all-iver/shapes2d) version, which you can restore by copying Assets/Shapes2D into your project's Assets folder, or you can get Shapes2D on the [Unity Asset Store](https://assetstore.unity.com/packages/tools/sprite-management/shapes2d-make-art-fast-62586) (deprecated). For the fix only, replace your Shape.cs and ShapeEditor.cs with the new ones.

Documentation is online at [http://sub-c.org/Shapes2D/documentation](http://sub-c.org/Shapes2D/documentation).

Discord at [https://discord.gg/U7x8Yum](https://discord.gg/U7x8Yum). Feel free to ask questions and request help.

I didn't write the plugin, the original author is [@all_iver](https://twitter.com/all_iver). Go show him some love. \o/

🥞
