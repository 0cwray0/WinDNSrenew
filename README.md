# WinDNSrenew


## Purpose:
The purpose of this batch script is to wipe the DNS cache of a Windows PC based upon the number of seconds that the user inputs.</br>

This is meant for very niche purposes such as connectivity issues or more hands off machine management, and carries NO stated warranty.</br>  

## Usage:
Upon execution ["-1" will refresh on a keypress] ["1-99999" function as stated] ['d' for current DNS] ['e' for exit] ['h' for help]</br>
</br>
To Run:
```
cd navigate\to\directory\where\batch\file\resides
WinDNSrenew.bat
```

## Issues:
Certain operators still evade the input sanitization I've instituted. Ex. ([<],[>],[,],[|],["],[;])

