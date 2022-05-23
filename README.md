# Super simple Elden Ring Backup tool

This is a window batch file(bat) for backup the Elden Ring save folder. Super lightweight, simple, use to use.

# Install

No installation needed. Just download the **eldenRingbackup.bat**, edit it and you can use it!

# Before use

1. Download **eldenRingbackup.bat**.
2. Right click on the bat file and choose edit. (notepad ++ will be better)
3. The code will show on the notepad like this: 
> `@echo off`
> 
> `xcopy /s/z {save folder location} {backup location}`
4. Edit the second line: `xcopy /s/z {save folder location} {backup location}`, replace the correct path of the folder in {  }.
5. Example: `xcopy /s/z C:\Users\xx\AppData\Roaming\EldenRing\123456789 D:\GameBackup\EldenRing\backup\123456789`.
6. Save it and run it!
