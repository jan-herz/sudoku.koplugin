# KOReader Sudoku Plugin

This plugin brings a straightforward Sudoku experience to KOReader so you can solve puzzles while reading.

## Features
- Multiple difficulty levels
- Controls optimized for touch
- Automatic progress saving

Forked to add several QoL improvements:
* True RGB32 color support for color E-Ink displays (red errors, customizable active cell background)
* Optional auto-remove notes feature (clears from row/col/box)
* Faux-bold styling for given numbers to improve contrast on high-DPI screens
* Automatic portrait mode lock during gameplay (restores previous orientation on exit)
* Clean, centered status bar without coordinates

(Also incorporates @appel's great features):
* Highlight selected number across the board
* Grey out numbers that are complete
* Refined font size to prevent note overlap

Huge thanks to the original developer and @appel for the great foundation!

## Installation
1. Copy the `sudoku.koplugin` folder into KOReader's `plugins` directory.
2. Restart the KOReader.

🇭🇺 **Magyar verzió:** A magyar nyelvű menühöz és üzenetekhez másold a "hungarian_version" mappában található "main.lua" fájlt a plugin mappájába, felülírva az eredetit.

## Credits
* The original foundation of this project was created with assistance from Windsurf (AI).
* This fork's improvements were developed with assistance from Google Gemini (AI).
