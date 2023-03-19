# Reset Visual Assist trial (including VS admin mode)

To reset Visual Assist trial do the following steps:

1. Remove "%TMP%\1489AFE4.TMP" file 
2. Delete "HKCU\Software\Licenses" key 
3. [For VS admin mode] Launch the [Process Monitor](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon) (disable capture, just launch it)
4. [Re]start Visual Studio

Tested on Visual Assist 10.9.2399 (Windows 11 21H2, Visual Studio 2019)
