All Autocomplete Sublime Text
===========================================================

This fork includes hack to fix sass and css dash-bug
https://github.com/alienhard/SublimeAllAutocomplete/issues/18

Extends the default autocomplete to find matches in all open files.

By default Sublime only considers words found in the current file.


Configure
---------

You can define settings "apply_with_dash_hack_syntaxes" in AllAutocomplete.sublime-settings to select to which sytaxes apply "-dash hack"

You can also remove dash from "word_separators" option in syntax specific settings for CSS or SASS if you want to see all suggestions,
not only after pressing next dash.


Install
-------

If you have Package Control installed in Sublime just press ctrl+shift+p (Windows, Linux) or cmd+shift+p (OS X) to open the Command Pallete.
Start typing 'install' to select 'Package Control: Install Package', then search for AllAutocomplete and select it. That's it.

You can also install this package manually by entering the Packages directory of Sublime Text 2/3 and issuing on a terminal:

    git clone https://github.com/alienhard/SublimeAllAutocomplete


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