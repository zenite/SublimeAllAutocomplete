All Autocomplete Sublime Text
===========================================================

Extends the default autocomplete to find matches in all open files.

By default Sublime only considers words found in the current file.

This is a fork of https://github.com/alienhard/SublimeAllAutocomplete/

This fork includes hack to fix SASS and CSS dash bug
https://github.com/alienhard/SublimeAllAutocomplete/issues/18/
http://sublimetext.userecho.com/topic/222861-/


Install
-------

If you have Package Control installed in Sublime just press ctrl+shift+p (Windows, Linux) or cmd+shift+p (OS X) to open the Command Pallete.

start typing "Package Control: Add Repository", press Enter and insert
	https://github.com/andruhon/SublimeAllAutocomplete
press Enter, start typing "Package Control: Install Package", press Enter, start typing
"All Autocomplete" and select one with "https://github.com/andruhon/SublimeAllAutocomplete" URL

You can also install this package manually by entering the Packages directory of Sublime Text 2/3 and issuing on a terminal:

    git clone https://github.com/andruhon/SublimeAllAutocomplete


Configure
---------

You can define settings "apply_with_dash_hack_syntaxes" in AllAutocomplete.sublime-settings to select to which sytaxes apply "-dash hack"

You can also remove dash from "word_separators" option in syntax specific settings for CSS or SASS if you want to see all suggestions,
not only after pressing next dash.


LICENSE
-------

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
Version 2, December 2004

Copyright (C) 2013 Adrian Lienhard <adrian.lienhard@gmail.com>

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.

DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

0. You just DO WHAT THE FUCK YOU WANT TO.