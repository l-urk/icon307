# Shell-Icons-307
Change all default folder icons to icon 307


Using the tutorial :
https://www.winhelponline.com/blog/change-open-folder-icon-explorer-and-registry-editor/



Otherwise , make a new registry folder at HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer called Shell Icons


So you will be at HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Shell Icons

Put the s_foldericon file at C: drive

And create two new strings, 3, and 4, and have their values point the s_foldericon.dll . So it will look like C:\s_foldericon.dll

or replace with a cusotom icon.ico ... *Will only work on some versions of windows 10 as an icon file*



Refresh and you're done
