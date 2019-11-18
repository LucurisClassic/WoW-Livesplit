# WoW-Livesplit
Automatically split your runs when a boss dies.

### Requirements
  * Python
    * Pip
    * Pynput (installed via pip)
  * [Memoria](https://www.curseforge.com/wow/addons/memoria) - Takes a screenshot when a raid boss dies.
  * [LiveSplit](http://livesplit.org/) - A tool used by speed runners for Ocarina of Time, Super Mario Bros, and more.
    [LiveSplit layout example](https://imgur.com/dxKTVi9)

### Live Split Setup
  1. Open Live Split and right click on the interface.
  2. Import the layout and choose from file `Molten_Core.lsl`.
  3. Import the splits (for example from the included file `MC.lss`) OR set up your own splits.
  4. In Settings assign a hotkey for splits and resets.
  5. Make sure Global Hotkeys are enabled.
  
### Python Script Setup
  1. Change the key stroke on line 23 of splits.py to match the setting in Live Split.
  2. Unbind the key in WoW Keybinds.
  
  
### Running the Script
  * Open Command Prompt from the Start Menu.
  * Type: python C:\path\to\splits.py
  * Press the hotkey when you initiate the first pull and the script will handle the rest.
