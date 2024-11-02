# ZoneStripperExt
ZoneStripper Shell Extension

![image](https://github.com/user-attachments/assets/0d80b99b-c727-4561-bc46-9e3846a73ba3)


This is a companion to my [ZoneStripper program](https://github.com/fafalone/ZoneStripper) to remove the Zone.Identifier NTFS alternate data stream, also known as 'The mark of the web', that indicates to Windows and MS Office that a file came from the internet.

It adds options to remove it or change it to trusted, and if you select a folder it will be applied recursively to all files within that folder and subfolders.

It has a helper module that automatically merges the .reg file after building.

On 64bit Windows you should build both the 32 and 64bit version so it also appears in 32bit apps.
