# ink_npp
Syntax-Highlighting for Ink files
## What it is
Just a simple XML file to import as User Defined Language in Notepad++ which allows syntax highlighting of files written in [Ink](https://github.com/inkle/ink).

## Issues
There are still some minor issues I wasn't able to work out, such as variable assigments being interpreted as stiches or closing brackets } following a redirection get dropped. So instead of 

   `{ putcomponentintent: -> put_component_inside_tent }`
   
it's better to have the closing bracket on its onw line:

  `{ putcomponentintent: -> put_component_inside_tent
  
  }`


## Installation

(from the [Notepad++ website](http://notepad-plus.sourceforge.net/uk/site.htm)

1. Download the user-defined language to your computer
2. Open the file with your favourite text editor (such as notepad++ or notepad)
3. Click start, run, type (or paste in) %APPDATA%\Notepad++ then click ok
4. Open userDefineLang.xml with a text editor
5. If this is the first userdefined language you are adding, copy/paste the entire first file (which you downloaded) into the userDefineLang.xml, replacing all that was there. If this is the second or more language you add, simply copy everything from the first file starting at `<UserLang...>` to `</UserLang>` and paste it at the end of the userDefineLang.xml right before `</NotepadPlus>`
6. Save the newly improved userDefineLang.xml
