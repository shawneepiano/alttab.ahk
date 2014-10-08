TO DO (maybe):
==============

- reduce UI to allow faster switches
- stick items to top or bottom of list
- use listview insert command to place windows at specific locations in list?
- get best practices with compiz and other compositing programs for other ways of dealing with alt tab
- develop more keyboard shortcuts like those used with VistaSwitcher
- sort the window list with shortcuts
- incorporate window images based on AeroThumbnails library
- get rid of a lot of the fluff and unused code
- get on forums and post to people to try to get more cooperation
- make it work with Win8 apps

LATEST VERSION CHANGES:

since 09-10-13:
- fix close app from reopening the all window list if closing app from Group
- sometimes windows don't come to the front (outlook)

since 08-29-13:
- return passing window to previous zorder

since 08-08-13:
- remove a majority of UI
- add EXE only mode to cycle between current application windows
- added coloring for max
- get color schemes to work on startup
- bring focused window to the font when cycling

since 25-04-06:
+: Groups of windows are shown in tabs - they can be re-arranged by drag-and-drop.
+: Settings tab.
+ & FIX: Updates to the listview colour code - much smoother now (thanks to ambi for updating the Listview script).
+ & FIX: Sorting of columns with direction indication ([+] or [-])
+: Mouse wheel over the TASKBAR scrolls the list - Middle button SELECTS a window in this mode (it normally CLOSES a window!).
+: Save data on big changes (in addition to program exit) - e.g. new group created, hotkeys changed
CHANGE: Selections with the mouse are now made with a double click (or just release the Alt key) instead of a single one.
CHANGE: Adjusted display position to be centered by default.
CHANGE: Dialog windows only indicated by red higlight (not by title too).
CHANGE: Not Responding windows indicated in a new column (not by title).
CHANGE: Many speed optimisations and code improvements (it's almost decipherable now ;-))
FIX: Handling of "Not Responding" windows with no delays.


> For older changes, see the forum: http://www.autohotkey.com/forum/viewtopic.php?t=6422

Keyboard Shortcuts (from Vista Switcher)
==================

Below is the full list of keyboard shortcuts that you can use with VistaSwitcher.

System-Wide Key Combinations

Hot Keys	Description
Alt + Tab	Switch between open windows
Alt + ` (Backtick)	Switch between open windows of a single application (for example, MS Word documents or Explorer folders)
Ctrl + Alt + Tab	Switch between open windows on the current monitor (monitor with the mouse pointer or active window)
Win + F12 *	Show the list of all open windows ("Sticky" mode)
Win + F11 *	Show the list of open windows of the active application ("Sticky" mode)
* You can reassign these hotkeys in the VistaSwitcher Preferences, General tab.

Task List Navigation

Shortcut Keys	Description
Arrow Keys,
Page Up, Page Down,
Home, End	Navigate the task list
` (Backtick)	Navigate to the next window of the selected application
1, 2, ..., 9, 0	Select the task number 1, 2, ..., 9, 10 (hold down the number key for a while to switch to the selected task)
Shift + Arrow Keys	Select the current task and navigate the list
Insert, S	Select the current task and go to the next
Backspace, D	Deselect the current task and go to the next
A	Select all / Deselect all
Delete	Remove selected task(s) from the list
Window Management

Shortcut Keys	Description
Space, Enter	Switch to the selected task
F2, M	Minimize selected task(s)
C	Cascade selected tasks on the desktop.
V	Tile vertically selected tasks on the desktop
H	Tile horizontally selected tasks on the desktop
F6, <	Restore selected task(s)
F7, >	Maximize selected task(s)
F4, X	Close selected task(s)
F8, T	Terminate selected task(s)
Other

Shortcut Keys	Description
F9, -	Sort the task list by title
F10, +	Sort the task list by application (groups on the taskbar)
E	Explore the EXE path of the selected task
P	Open the Preferences dialog
App (or Menu)	Show the context menu
