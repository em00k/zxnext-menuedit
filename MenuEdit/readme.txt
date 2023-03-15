MenuEdit for the ZX Spectrum Next 
---------------------------------
NO WARRANTIES! 

1.0 Inital Release 

1.2 Bugs fixed 
	enMenus.cfg not existing
	Backup cfg file now works
	Load cfg file now works
	
    New 
	Move entries up/down
	View config files (or any other text)
	Menus tidies up 
	Internet updates
	Warning for 2.07 incase too low to support

1.3	Fixed command line > 42 chars and spewing
	to the top of the screen 
	
	Added browser sort files 

	Added Shortcut Key on left side of menu item

	Only show OS notification if on lesser
	version than 2.07l

1.32	Fixed long command lines going crackers

	
In NextZXOS v2.7 + you can edit the default
menu items that appear on start up. This is 
done my configuring a configuration file in 
"c:\nextzxos\enMenus.cfg"

Normally you would have to edit with a text
editor such as qe - but that can be a little
tricky for new-comers so this tool attempts
to bridge that gap.

How to run
Launch the menuedit.bas from the Browser

When MenuEdit starts you will see a familiar 
NextZXOS menu list, cursor up and down will
change the selected menu option and left and 
right will move through other menus available
in the OS. 

You can press M to bring up the LOAD/SAVE/EXIT
menu

Select a menu option and press return to EDIT 
the menu name and command. 

When creating a command it is worth read the 
NextZXOS Guide as this will explain some of the 
internal functions. 

if you use a $ for the command an Action menu
will pop up, things should me self explanotory.

When you have finished editing you menus, PRESS M 
and Save Menu Cfg. You can then QUIT the program
and test your new menu.

If it all goes wonky you can PRESS M and choose 
Default Menu options and save. 

IF YOU SCREW UP YOUR MENUS!!
Dont despair, from basic type : 

erase "c:\nextzxos\enmenu.cfg"

Relaunch the tool, press m and choose Default menu
and then Save Menu CFG 


Enjoi! 

