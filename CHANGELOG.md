# Changelog #
Version 2.3 Forked by niebert
  * User interface updated and settings are defined to export to a MediaWiki as default.

Version 2.2
  * Updated excanvas to [r3](https://code.google.com/p/imgmap/source/detail?r=3) - should solve IE8 problems
  * Added Example with ExtJs integration, thanks to Colin Bell
  * New callback event: onDblClickArea
  * Fixed [Issue 21](https://code.google.com/p/imgmap/issues/detail?id=21): Example 1 and soon online editor supports background change
  * Fixed [Issue 23](https://code.google.com/p/imgmap/issues/detail?id=23): Possible to click on area in highlighter mode and fire a callback (follow the link)
  * Added Xinha plugin both as an example and a separate plugin
  * Examples got renamed to reflect what they do, plugins got separate packages, top level folder is now included in them.

Version 2.1
  * Separated most drawing-specific and gui-specific codes. This means easier integration with ANY kind of user interface.
  * GUI specific functions went to default\_interface.js
  * JSDoc toolkit based documentation using modified outline template of JProton.
  * Updated all examples to use separate interface code and map handling code.
  * Removed example 5, since all examples use callbacks now.
  * Fixed issue when dragging areas in Safari will cause selecting all kinds of things.
  * Fixed issue when scrolled image in Opera will result drawing with offset.
  * Fixed [Issue 13](https://code.google.com/p/imgmap/issues/detail?id=13): Suggestion: image url with timestamp
  * Fixed [Issue 14](https://code.google.com/p/imgmap/issues/detail?id=14): Javascript error in MSIE
  * Fixed [Issue 17](https://code.google.com/p/imgmap/issues/detail?id=17): Doesn't work with Adobe AIR 1.1 - new package built with latest SDK
  * Internal and generated html shape names are HTML conform (circle, rect, poly)
  * Zoom (scale) functionality (new function scaleAllAreas, new property globalscale)
  * Zoom introduced to all plugins.
  * Added CSS output and Wiki output formats.
  * Added bezier (quadratic curve) support (just for fun, not standard image map shape, disabled by default)
  * Updated FCKEditor example to use latest FCK.
  * TODO: Elliminated some memleaks using drip.
  * TODO: update tiny
  * AIR queries are now synchronous.

Version 2.0beta6
  * TinyMCE3 support (plugin zip and also as example8)
  * Adobe AIR version (air file and also as example7)
  * Changed example2
  * Additional languages

Version 2.0beta5
  * Added support for converting area types

Version 2.0beta4
  * Added Opera support

Version 2.0beta3
  * Added MAP id attribute support apart from existing MAP name usage.
  * Added function getMapId().
  * Added function getMapName().
  * Added function getMapInnerHTML().
  * Added TinyMCE support plus example. (Thanks to John Ericksen)
  * Added FCKEditor support plus example. (Thanks to Alfonso MartÃ­nez de Lizarrondo)
  * Added custom callbacks on certain imgmap events.
  * Added Safari support. (Thanks to Alfonso MartÃ­nez de Lizarrondo)
  * Improved handling of bad coordinates.
  * Fixed several bugs and issues.
