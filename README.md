# Warthunder_CheckTeamStat
Stat checker for Warthunder.
All of the information on the overlay or console is taken from the official warthunder website.
This information can be viewed by anyone.
 
Thanks to <b>Yonisen</b>, <b>Naysayer</b>, <b>kotiq</b>, <b>f0xeri</b>, for helping create this program, my version is an english translation and modification to include more relevant data.

## Installation

- Download and install <a href="https://www.python.org/ftp/python/3.10.6/python-3.10.6-amd64.exe">Python</a><br>
!!!At the begining of the installation dont forget to check the box to "add python.exe to PATH"<br>
- Download the repo and extract it to its own folder. <br>
- Open the folder `Warthunder_CheckTeamStat` and run `install.py` Wait for the installation to complete.<br>
- Move the folder `Warthunder_CheckTeamStat` to the WarThunder folder<br>

These actions only need to be done once after downloading the repository. 

## Game setup

Make sure the game is running in Full Screen window mode:

<img src="https://github.com/Penguax/Warthunder-TeamStatLookup/blob/main/data/screen1.png">

## Default shortcut key (Ctrl+J)

1. Open the folder `Warthunder_CheckTeamStat` and run `xvm.py`<br>
The script will run in the background and wait for your shortcut command (by default `Ctrl+J`)<br>
2. Once youre loaded in game, run the shortcut keybinds (by default `Ctrl+J`) and the program will open a chrome browser and collect the player stats. 
3. To close the results if the overlay is enabled, you can hold Alt to make the cursor visible and close the overlay. 
<img src="https://github.com/Penguax/Warthunder-TeamStatLookup/blob/main/data/screen2.png">
<img src="https://github.com/Penguax/Warthunder-TeamStatLookup/blob/main/data/screen3.png">
<img src="https://github.com//Penguax/Warthunder-TeamStatLookup/blob/main/data/screen5.png">
Note: If displaying the data in the console, the results may be duplicated.

## Button customization

To change the default keyboard shortcut, open the `buttons.ini` file and edit the shortcut, save your changes after.<br>
Here is an example of what might be written in this file:

<img src="https://github.com/Penguax/Warthunder-TeamStatLookup/blob/main/data/screen4.png">

If you do not know how to register a mouse button, run the script `testMouse.py` from the same folder and click the button you are looking for.
It will tell you its correct name

## Disable overlay in game

If you have multiple monitors, then perhaps the console output is enough for you.<br>
To disable the overlay, open the file `buttons.ini` and remove the `+` sign that appears at the end of the `button.ini` file.

<img src="https://github.com/Penguax/Warthunder-TeamStatLookup/blob/main/data/screen7.png">
