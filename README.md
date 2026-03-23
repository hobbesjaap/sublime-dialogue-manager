# Sublime Text Syntax for Godot Dialogue Manager

This repository provides a custom syntax highlighter for Sublime Text. It formats `.dialogue` files used by [Nathan Hoad's Dialogue Manager](https://github.com/nathanhoad/godot_dialogue_manager) in Godot 4.

I built this plugin to help me with the development of my game, [Fhaloness](https://www.hobbeshk.com/). Fhaloness is a 2D pixel art tactical narrative game. Managing complex dialogue requires clear visual structure. This syntax file makes reading and writing dialogue scripts easier.

## Features

This plugin provides specific colour coding for dialogue scripts. It isolates logic from spoken text. It recognises the following elements:

* Character names and optional portraits
* Dynamic character names using variables
* Dialogue choices
* Jump and return flow control symbols
* Logic keywords like if, else, match, and when
* Boolean values and math operators
* BBCode text formatting tags
* Translation identifiers

## Manual Installation

You can install this syntax file manually before it reaches Package Control.

1. Open Sublime Text.
2. Click Preferences in the top menu.
3. Select Browse Packages.
4. Create a new folder named `DialogueManager` in the packages directory.
5. Place the `dialogue.sublime-syntax` file into this new folder.
6. Open any `.dialogue` file to see the updated colours.

## Usage

Sublime Text will automatically apply the syntax to files with the `.dialogue` extension. You can also set it manually by clicking the bottom right corner of the editor and selecting Dialogue Manager.