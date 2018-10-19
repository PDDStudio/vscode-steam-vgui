# Steam VGUI Syntax & Code Snippets

> Syntax Highlighting & Code Snippets for Steam's [VGUI DSL](https://developer.valvesoftware.com/wiki/VGUI_Editing).

[![Build Status](https://travis-ci.org/PDDStudio/vscode-steam-vgui.svg?branch=develop)](https://travis-ci.org/PDDStudio/vscode-steam-vgui)

## Introduction

This extension is a port of the [language-steam-vgui](https://github.com/StaticRocket/language-steam-vgui) extension for [Atom](https://atom.io) with some adjustments.

## Ingormation About VGUI Editing

The following excerpt is taken from [Valve's Developer Documentation](https://developer.valvesoftware.com/wiki/VGUI_Editing#Styles):

> **Note:**  
> The information below is extracted from the Valve internal document on how to edit, so it may in some cases be wrong or reference tools that don't exist.

To make a skin for Steam (post 2010 UI update), you need to take a copy of resource/styles/steam.styles file and copy it to skins/<your skin name here>/resource/styles/steam.styes. The existence of that file will make Steam put that skin as an option in the settings->interface dialog (Steam will need to be restarted for it to show). From there you can start editing. You can put new files or existing steam files you want to replace under your skins folder. Good luck!

## Features

- Syntax Highlighting for `.layout`, `.res` files
- _(Coming soon)_ Code Snippets for creating new GUI controls

## Known Issues

None yet. You can checkout the issue section of this repository. 
Please report any bug or 

## Special Thanks

The extension icon uses resources from [mbtskoudsalg](https://mbtskoudsalg.com/explore/steam-icon-png/#1).

## Release Notes

Users appreciate release notes as you update your extension.

### 0.0.1

Initial release of `vscode-steam-vgui`
