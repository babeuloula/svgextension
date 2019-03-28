# SVG Viewer Extension for Windows Explorer

Extension module for Windows Explorer to render SVG thumbnails, so that you can have an overview of your SVG files.

## NOTE

New signed installer have been uploaded from version 0.1.1 thanks to www.certum.eu! In this version only the installer is signed, but from now on both the DLLs and the installers will be signed.

## Installation

You can just simply use the provided binary installers. Make sure you download the right architecture.

**IMPORTANT**: The 32 bit installer will run on a 64 bit system, but the extension will not function.

## Build

The easiest way to build it is with the provided Qt project file. I suggest to use Qt Creator. Requirements:

- Qt SDK
- Windows 7 SDK
- Qt SDK 64 bit (for 64 bit builds only) NOTE: You have to compile Qt for 64 bit by yourself.

## Thanks to

- Qt @ [http://qt.nokia.com/](http://qt.nokia.com/)
- Jeremy @ urk:[http://www.codemonkeycodes.com/2010/01/11/ithumbnailprovider-re-visited/](http://www.codemonkeycodes.com/2010/01/11/ithumbnailprovider-re-visited/)