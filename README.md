Photshop Get CSS Script
=======================

## Description
This will auto calculate the position and size of a layer in unit `%` and `px`. Layer can be a TEXT, GROUP, or IMAGE.

This script is focus only in position and size (as of the moment). It is versy simple, but very helpful to those html5 ad builder.

Multiple layer is not supported, Group them to able to get it's CSS property.

This has been tested in Photoshop CC 2015 (OSX) and 2014 (Windows).

Example result:

```
class {
	left: 0%;
	top: 0%;
	width: 100%;
	height: 100%;
}
```

## Installation
### OSX
1. Copy `getCSS.jsx` and paste it to your Adobe Photoshop `/Applications/Adobe Photoshop/Presets/Scripts/`
2. Open Photshop and create shortcut keys. At Menu `Edit > Keyboard Shortcuts` and in the popup dialog, click `File > Scripts > getCss` and create your own shortcut. (example: COM+ALT+CTRL+C)
3. Press OK and you are done.
 
### Windows
1. Copy `getCSS.jsx` and paste it to your Adobe Photoshop `C:\Program Files\Adobe\Adobe Photoshop\Presets\Scripts`
2. Open Photshop and create shortcut keys. At Menu `Edit > Keyboard Shortcuts` and in the popup dialog, click `File > Scripts > getCss` and create your own shortcut. (example: ALT+CTRL+SHIFT+C)
3. Press OK and you are done.
 
## How to use
1. Open any PSD.
2. Select any layer you want to get the position and press the shortcut you craeted.
3. It will popup the CSS position and size property

###
License: [MIT](http://www.opensource.org/licenses/MIT)  
Blame: Michael Trinitaria
###

