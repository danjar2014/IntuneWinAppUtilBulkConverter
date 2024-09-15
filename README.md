# IntuneWinAppUtil GUI Tool

https://github.com/danjar2014/IntuneWinAppUtilBulkConverter

## Description

**IntuneWinAppUtil GUI Tool** is a user-friendly PowerShell application designed to simplify the conversion of PS1, CMD, BAT, and EXE files into the Intune Win32 format. It supports both bulk and single folder operations, streamlining the application packaging process for Microsoft Intune with an intuitive graphical interface.

## Requirements

- Script must be named install.exe , install.cmd , install.bat, install.ps1
- Windows 10/11
- PowerShell (with the ability to run scripts)
- Minimum 10MB of disk space

## How it works?

### Converting Files to Intune Win32 Format
1. Launch the IntuneWinAppUtil GUI Tool by running the `GraphicInterface.ps1` script.
2. Select the source folder containing the files you wish to convert.
3. Specify the destination folder where the converted packages will be saved.
4. Provide the path to the `IntuneWinAppUtil.exe` executable.
5. Choose whether to perform a bulk or single folder operation.
6. Click the "Run" button to start the conversion process.


### Bulk and Single Folder Operations
- **Bulk Operation:** Processes multiple folders in one go, creating corresponding Intune Win32 packages for each folder.
- **Single Folder Operation:** Processes one folder at a time, converting its contents into the Intune Win32 format.



### Information Button
1. Click the "i" button (information icon) located at the bottom right of the window.
2. A pop-up will display information about the tool and its creator.

## Reporting Problems

Bug reports and improvement suggestions are welcome! 

## Status

The project is actively developed and updated.
