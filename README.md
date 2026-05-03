# ZoneStripperExt
ZoneStripper Shell Extension

![image](https://github.com/user-attachments/assets/0d80b99b-c727-4561-bc46-9e3846a73ba3)

**Update (03 May 2026):** The menu entry was not showing up for folders, which the comments indicated would be supported. This is simply an issue with the .reg file; I thought the entry for * would include folders, but it does not. The registry file now has an additional entry for folders. You don't need to rebuild the DLL, just merge the updated .reg file (rebuilding will also do this if you wanted to). I've tested that the functionality to remove identifiers from items in selected folders works.

This is a companion to my [ZoneStripper program](https://github.com/fafalone/ZoneStripper) to remove the Zone.Identifier NTFS alternate data stream, also known as 'The mark of the web', that indicates to Windows and MS Office that a file came from the internet.

It adds options to remove it or change it to trusted, and if you select a folder it will be applied recursively to all files within that folder and subfolders.

It has a helper module that automatically merges the .reg file after building.

On 64bit Windows you should build both the 32 and 64bit version so it also appears in 32bit apps.
