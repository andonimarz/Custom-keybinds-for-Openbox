# Custom keybinds for Openbox

A custom config file with some new keybinds for window switching and snapping.
A script that shows in a pop-up window all the available keybinds.

## Installation

Go to the following folder:

    cd ~/.config/openbox

Rename rc.xml as old_rc.xml or move it to a safe place. It's the config file and it will be your backup.

    mv rc.xml old_rc.xml
    
Paste the new rc.xml and keybinds files and reconfigure openbox.

    openbox --reconfigure

Now pressing Ctr+Alt+K and a pop-up window should appear with all the available keybinds including some new.
Just press ESC and it will disappear.

	Desktop switching 
		"C-A-Left"			Move to FIRST desktop 
		"C-A-Right"			Move to SECOND desktop 
		"C-S-A-Left"			Send to FIRST desktop 
		"C-S-A-Right"			Send to SECOND desktop 
	Window switching with tab 
		"A-Tab"				Switch to NEXT window 
		"A-S-Tab"			Switch to PREVIOUS window 
	Window switching with the arrow keys 
		"A-S-Right"			Cycle to RIGHT window 
		"A-S-Left"			Cycle to LEFT window 
		"A-S-Up"			Cycle to TOP window 
		"A-S-Down"			Cycle to BOTTOM window 
	Keybindings to toggle fullscreen 
		"F11"				Fullscreen 
		"S-Super-A-Up"			Maximize 
		"S-Super-A-Down"		Minimize 
	Half screen window snapping (Ctrl+Win+Arrowkey) 
		"A-Super-Left"			SNAP LEFT 
		"A-Super-Right"			SNAP RIGHT 
		"S-A-Super-Left"		SNAP LEFT 40% 
		"S-A-Super-Right"		SNAP RIGHT 60% 
		"A-Super-Down"			SNAP DOWN 
		"A-Super-Up"			SNAP UP 
	Quarter screen window snapping (Ctrl+Alt+Win+Arrowkey) 
		"C-Super-Left"			SNAP UP-LEFT corner 
		"C-Super-Down"			SNAP DOWN-LEFT corner 
		"C-Super-Right"			SNAP DOWN-RIGHT corner 
		"C-Super-Up"			SNAP UP-RIGHT corner 
	App keybindings
		"C-A-h"				File explorer: pcmanfm-qt
		"C-A-v"				Visual Studio Code 
		"C-A-k"				Keybindings 
