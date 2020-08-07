# Product Name

This is a batch downloader for Google images as a Windows executable which does not require any installation.

[![NPM Version][npm-image]][npm-url]
[![Downloads Stats][npm-downloads]][npm-url]

This executable provides simple and fast way to search and download Googe images in a simple GUI for users not using Python. The download functionalities come from google-images-download by hardikvasa (https://github.com/hardikvasa/google-images-download/), and this project adds a simple Tkinter GUI and has packaged in PyInstaller executable.

Start by entering your search terms (keywords, colour, specific site, # limit) into the entry boxes in the interface, then click "Search". The program will search Google, automatically download thumbnails (quantity up to the limit), and display the thumbnails in the interface. The images can be downloaded either altogether with the "Download all" button or individually by clicking on the image (work in progress).

![](interface.png)

## Installation

Windows:

Download Semiotics.Engine.v[x.y.z].zip from https://github.com/eyjho/google_images_download_exe/releases. Extract into your working directory, and run using the shortcut. No installation required. All images will be downloaded into the \Pictures directory by default, which will be in the same directory as the shortcut, or the directory above the .exe file. Note that the shortcut in the package is a relative link, and therefore will not work if moved. For a moveable shortcut, find Semiotics Engine\Semiotics Engine.exe, and create a shortcut.

![](directory.png)

OS X & Linux: TBC

## Usage example

![](gui_search.png)

_For more examples and usage, please refer to the [Wiki][wiki]._

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

Eugene (https://github.com/eyjho)

Distributed under the MIT license. See ``LICENSE`` for more information.

https://github.com/eyjho/google_images_download_exe

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[wiki]: https://github.com/yourname/yourproject/wiki
