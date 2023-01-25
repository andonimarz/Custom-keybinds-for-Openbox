# Custom-keybinds-for-Openbox

A custom config file with some new keybinds for window switching and snapping.
A script that shows in a pop-up window all the available keybinds. Just press ESC and it will disappear.

## Installation

Go to the following folder:

    cd ~/.config/openbox

Rename rc.xml as old_rc.xml or move it to a safe place. It's the config file and it will be your backup.

    mv rc.xml old_rc.xml
    
Paste the new rc.xml and keybinds files and reconfigure openbox.

    openbox --reconfigure

Now pressing Ctr+Alt+K you should see all the available keybinds including some new.
