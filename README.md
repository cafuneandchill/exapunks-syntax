# EXAPUNKS Syntax

[![License](https://img.shields.io/github/license/cafuneandchill/exapunks-syntax)](https://github.com/cafuneandchill/exapunks-syntax/blob/master/LICENSE)
[![Version](https://img.shields.io/github/v/tag/cafuneandchill/exapunks-syntax?label=version)](https://github.com/cafuneandchill/exapunks-syntax/tags)

A package for [Sublime Text](https://www.sublimetext.com/) that provides syntax highlighting for the assembly language used in the game [EXAPUNKS](http://www.zachtronics.com/exapunks/).

## Installation

Clone or download the repository into the Packages directory of your Sublime Text install.
To find the location of your Packages directory, choose `Preferences > Browse Packages...` within Sublime Text.

By default, syntax highlighting will be applied for files with the extension `.exa` or `.exapunks`.
Alternatively you can manually select *EXAPUNKS* under `View > Syntax` from the menu. Source code files containing `NOTE EXAPUNKS` as a first line are automatically assumed to have EXAPUNKS syntax.

## Preview

The actual highlighting colors depend on the chosen color scheme.
The following image shows a preview for the default color schemes *Monokai*, *Sixteen* and *Mariana*:

![Preview](https://i.imgur.com/XXpRk8u.png)

Some of the syntax rules were updated to follow Sublime Text's scope naming guidelines and assign more specific scopes.
Depending on the chosen color scheme, highlighting colors might have changed when compared to a [previous version](https://github.com/cafuneandchill/exapunks-syntax/tree/legacy) of the syntax definition file.
