Release notes for WriteExpress Rhymer for
Windows Vista, XP, 2000, 98, 95 and Me

Copyright (C) 1996-2007. WriteExpress Corporation
All Rights Reserved.
Revision 2/23/2007
=================================================================

This file contains important information--please read all of it. This information
supersedes the information in program's Help file.

Table of Contents
-----------------
1.  Manual Installation for Microsoft Word
2.  How to Uninstall WriteExpress Rhymer


1. Manual Installation for Microsoft Word
---------------------------------------------------------
If Rhymer does not appear on the Tools menu in Microsoft Word then setup was not able to correctly install its file for Microsoft Word.

Solution: Find the STARTUP folder under the folder where winword.exe is installed.
Locate and copy the file Rhymer.wll to that folder.

Techical Explanation: Rhymer for Word is a WLL (Word link library) file. Its file
Rhymer.wll must be installed in Word's STARTUP folder. When Word starts, it loads all the .wll files it finds in its startup folder. When Rhymer loads, it retrieves the path of its database from the Windows registry and then loads its database.

For Windows Vista:
Rhymer retrieves the path to its database from the WriteExpress.ini file, which gets installed in Word's STARTUP folder. Using Notepad or a text editor, open WriteExpress.ini file in Word's STARTUP folder. If the file does not exist then create it.

Write the following and save the file:

[Rhymer]
DataPath=C:\Program Files\WriteExpress\Rhymer



Note: For 4,001 Business, Sales & Personal Letters the folder is by default:
C:\Program Files\WriteExpress\4,001 Letters\Rhymer

To find the database folder, search your computer for the file Ww10en.rhw

2. How to Uninstall Rhymer
-----------------------------------------------
To uninstall Rhymer:

a. Click the Start button, click Settings, and then click Control Panel.
b. Double click the Add/Remove Programs icon.
c. Click WriteExpress Rhymer and Phonetic Finder and then click Add/Remove.

