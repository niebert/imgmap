# imgmap: Javascript based ImageMap Editor

With the imagemap editor you can easily draw ALL the standard image map shapes (rectangle, circle, polygon),
and you can have full control over the generated HTML code as well.

![Online Image Editor](https://niebert.github.io/imgmap)


## Purpose of the Fork
change the User Interface provided by Adam Maschek:
* set the default imagemap main export format to the MediaWiki
* use the javascript code in an HTML file the docs/ folder in GitHub,
* rename buttons and change layout for the Source Selector,
* add a "Create Image Map" Button to the user interface

## Technical Description
The editor natively uses the canvas HTML element to draw the shapes on a given image.
The ExplorerCanvas (http://excanvas.sourceforge.net/) library from Google is used to get the same result in browsers, that do not support the
canvas element but can use VML instead. ExplorerCanvas works quite well, however it is still beta quality,
and not as fast as the native canvas drawing, so expect some lags in IE.
The editor is currently tested to work in Chrome, Firefox, Safari, Opera 9+ and IE 6+.

![Screenshot of the Image Editor](img/imgeditor_screenshot.png)

## Acknowledgement
Thank you to Adam Maschek for sharing the code for Javascript ImageMap Editor on Github
See the online editor at: http://www.maschek.hu/imagemap/imgmap

The image map editor is based on the code of Adam Maschek.


## Note:
The code repository was originally hosted at google code and migrated to github on March 30, 2015

