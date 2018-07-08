INSTALLATION
rutracker.eu.org/viewtopic.php?pg=1&t=4127588

0) Uninstall VA (if you have installed it before).
0.0) Manually check for alive _folders_ of pervious version of VA in extensions folders (paths are described
below) and remove them by yourself, because of VA uninstaller's bug
1) Locate all places where va_x.dll's are reside in your MSVCs (paths are described below)
2) Replace all found va_x.dll with our one (from this torrent)
3) PROFIT (you may see "License: trial" - don't worry, all should work without any limitation)


Places where Visual Assist extension (va_x.dll and another stuff) resides in different versions of MS Visual Studio are listed below:

-------------------
MSVC version | path
-------------------
msvc2008     | find in installation path (by default c:\Program Files (x86)\Visual Assist X\)

msvc2010     | %USERPROFILE%\AppData\Local\Microsoft\VisualStudio\10.0\Extensions\Whole Tomato Software\Visual Assist\__version__\

msvc201[1|2] | %USERPROFILE%\AppData\Local\Microsoft\VisualStudio\11.0\Extensions\__random_dir__\

msvc2013     | %USERPROFILE%\AppData\Local\Microsoft\VisualStudio\12.0\Extensions\__second_random_dir__\

msvc2015     | %USERPROFILE%\AppData\Local\Microsoft\VisualStudio\14.0\Extensions\__random_dir__\
-------------------

Notes: in my case
__version__ is "10.9.2217.0"
__random_dir__ and __second_random_dir__ are generated and looks like "v3tpxirz.5pr"

Have a nice coding :3

P.S. If you like Visual Assist - byu a license (tell "thank you" to the VA developers)
