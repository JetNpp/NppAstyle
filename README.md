# NppAstyle
Format code/source for [ c c++ cs[c#,csharp] java javascript objc[m,mm] ]

## Notepad++ Astyle Plugin
### usage
- select code; press key : alt + f
- only work for selected part, and style is fixed/simple.
- usually use this plugin to format code sample in text file, not for whole source file.

## download

[Release](https://github.com/JetNpp/NppAstyle/tree/master/bin "Release")

## install
- compiled by [Visual C++ Redistributable Packages for Visual Studio 2019]
- copy the .DLL file into the plugins folder within your Notepad++ installation folder (e.g. \Program Files (x86)\Notepad++\plugins\ for x86 version). After updating npp to 7.6.6, it seems should put these plugins in seperate folder with same name as the plugin dll.

### env info
|env   | ver|
| - | - |
|__os__|windows 8 x64|
|__compiler__|MSVC 2019|
|NppAstyle.Ver|0.11.2.20|
|NppAstyle.dll|windows,x86|
|NppAstyle(x64).dll|windows,x64|

[logo]:https://github.com/JetMeta/ZToolKit/blob/master/Avator/jz_l.png "JetZux"

## Change Log
### [0.11.2.20] - 2025-01-07
- +.update AStyleLib to 3.6.6

### [0.11.2.19] - 2023-07-26
- +.update AStyleLib to 3.4
- +.webkit style

### [0.11.2.18] - 2022-04-16
- +. remove option pad-paren-in

### [0.11.2.18] - 2019-05-29
- +.fix disable some add/remove options of astyle.

### [0.11.2.18] - 2019-04-24
- +.update AStyleLib to 3.1

### [0.11.2.17] - 2019-04-17
- +.add support to objc (objective-c) files (.m .mm), as needed.

### [0.11.2.17] - 2018-04-30
- +.fix : not execute format when select "none" style

### [0.11.2.16] - 2017-11-04
#### added
- +.support format javascript code/source

### [0.11.2.15] - 2017-06-27
#### added
- +.format code clip in generic text.

### [0.11.2.15] - 2017-05-21
#### added
- +.cmake files.

### [0.11.2.15] - 17-04-07
#### added
- +.about dlg.
- +.compiler info.

### [0.11.01] - 16-11-15 
#### update
- m.update AStyleLib to 2.05.1

### [0.00.01] - 14-05-21
#### init
- usage : select text ; then press key : alt + f
