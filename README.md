
MenuEdit 1.40 for the ZX Spectrum Next 
--------------------------------------

Version 1.40 : 16/03/23 

  - FIXED : Last item could not open M menu 
  - FIXED : Auto menu item name from a selected file
  - ADDED : Shortcuts on menus 1-8 etc 
  - ADDED : Space to exit menu
  - UPDATE: Suggest template from file selected extension
            templates for : NEX, BAS, TAP, SNX, Z80, SNA
  - UPDATE: Command line increased to 126 for presets
  - UPDATE: Other cosmetic changes & under the hood improvments	

Version 1.32 : 15/03/23

  - FIXED : Lone command lines causes memory leak then crash, they are now limited to 83 chars
  - FIXED : Junk shown on Browser text

Version 1.3 : 15/03/23

  - FIXED : Command Line would reset to position 0,0 if > 42 chars, then spew the screen
  - FIXED : Browser sorting 
  - FIXED : Only show version warning on NZXOS less than 2.07
  - ADDED : CLEAR 65367 to BASIC loaders 
  - ADDED : Shows shortcut key on left of menu items

Version 1.2 : 15/01/23
  - FIXED : Issue when no enMenus.cfg exist
  - FIXED : SAVING / LOADING config files
  - FIXED : Backup to any file
  - FIXED : erroneous " from Basic line
  - ADDED : Move items up / down 
  - ADDED : View cfg from menu with .more
  - ADDED : Internet up date  

DOWNLOAD HERE : https://github.com/em00k/zxnext-menuedit/archive/refs/heads/main.zip

This is targeting the latest NextZXOS 2.07l

<img src="https://raw.githubusercontent.com/em00k/src-gifs/main/PIC-2023_01_13_21_58_27.png">

Bumbling idiot walk through : https://www.youtube.com/watch?v=ecLf6MvCqtA

NO WARRANTIES! MAKE SURE YOU ALWAYS BACK UP YOUR SD CARD SHOULD SOMETHING BREAK!!

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




