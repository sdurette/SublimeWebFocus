SublimeWebFocus
===============

This repo is for building color coding for fex, mas, and acx files that are used by WebFocus.

Note to install this color coding for only webfocus related files, you have to copy the file WebFocus.sublime-settings to the Packages\User directory.

Or you can open a FEX file, then go to Preferences > Settings - More > Syntax Specific - User and a file will open called WebFocus.sublime-settings.

In that file place the line:
	"color_scheme": "Packages/WebFocus/WebFocus.tmTheme"

You can also add other lines such as turning on line numbering but the line above is required. Remember to put a comma at the end if you add lines after it.
