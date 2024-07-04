# Shell-Icons-307
Change all default folder icons in Windows 10/11 to icon 307

**Using the tutorial :**
https://www.winhelponline.com/blog/change-open-folder-icon-explorer-and-registry-editor/

**Or my tutorial here:**
Download the .dll file from THIS REPOSITORY and put the icon307 file at C:\icon307
Otherwise , make a new registry key at HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer 
Call "Shell Icons"
So you will be at HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Shell Icons
And create two new strings, 3, and 4, and have their values point the icon307.dll
Type in the path inside the value data box.
Or replace with a cusotom icon.ico ... *Will only work on some versions of windows 10 as an icon file*
Refresh (And restart) and you're done.

**Or automatically by using the batch script:**
You can run icon307.bat as Administrator to add the registry keys automatically where icon307.dll is located "C:\icon307.dll"
