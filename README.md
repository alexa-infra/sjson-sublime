# sJSON syntax highlighting for Sublime Text

Provides syntax highlighting for '.sjson' files. Changes in JSON format (see JSON specs http://json.org/) are described here http://bitsquid.blogspot.nl/2009/10/simplified-json-notation.html

* Assume an object definition at the root level (no need to surround entire file with { } ).
* Commas are optional
* Quotes around object keys are optional if the keys are valid identifiers
* Replace ':' with '='

## Installation:
* first option
** copy current folder content to "Sublime Text 2/Packages/User/" folder
** restart sublime text editor is not needed
* second option:
** zip current folder content
** rename archive to sJSON.sublime-package
** copy archive to "Sublime Text 2/Installed Packages/" folder
** restart sublime editor

## Notes:
* see http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html for instructions, specs
* source is placed in sJSON.JSON-tmLanguage (json)
* sJSON.JSON-tmLanguage is converted to (Plist) sJSON.tmLanguage file by using AAAPackageDev package

**License: MIT**