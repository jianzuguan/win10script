# Ultimate Windows Toolbox
This script is the culmination of many scripts and gists from github with features of my own. I am building this script to be a swiss army knife of Windows tools to help setup and optimize machines.

## My Additions
- One command to run
- Full GUI implementation
- Winget install
- Install popular programs with one click
- O&O Shutup 10 CFG and Run
- Dark/Light mode
- Semi-configurable

## How to Run
Paste this command into Powershell (admin):
```
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/jianzuguan/win10script/master/win10debloat.ps1'))
```
Or, shorter:
```
iwr -useb https://raw.githubusercontent.com/jianzuguan/win10script/master/win10debloat.ps1 | iex
```

For complete details check out https://christitus.com/debloat-windows-10-2020/
