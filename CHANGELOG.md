Release Notes
=============

# **1.3 (2019-12-08)**

Please note that the app is still not signed nor notarized by Apple so macOS will complain about that upon the first start (use the "Open" menu command).

**new features:**

- support for macOS 10.15 Catalina
- faster directory scanning (about 2 times faster)

# **1.2 (2019-02-28)**

please note that macOS 10.13 or later is required

**new features:**

- new application icon thanks to Anton Repponen
- support for dark mode on 10.14
- tree map: the rendering is done in full resolution on Retina displays
- German, French and Spanish localizations re-added
- Disk Inventory X is now 64 Bit (Intel only ;-)
- project updated to Xcode 10.1

**bug fixes:**

- various small bug fixes and improvements (mostly due to changes in macOS)

# **1.0 (2005-10-09)**

**new features:**

- Finder context menu plugin with a "Open in Disk Inventory X" command for folders and volumes (have to be installed manually in the preference window!)
- a new selection list which can show all files of a specific kind or all files (to show the selection list, use the new context menu in the kind statistic or select menu "Window->Selection List").
- an option whether the assignment between colors and file kinds are shared between open windows or not (so every kind has in all windows the same color - like before - or the assignment is done for each window separately)
- performance improvements when dealing with a large number of files
- sortable columns in the kind statistic drawer (and in the new selection list, of course)
- a warning is shown prior deleting a file or folder on a network volume (items on a network volume can only be deleted, not moved to trash)

**bug fixes:**

- DIX crashed when refreshing a file or files if DIX has zoomed into a folder
- the "select parent" shortcut did not work if the file view had the focus: the shortcut is now changed to Apple-U (previously Command-P).

# **1.0 beta (2004-12-06)**

(runs only on Mac OS X 10.3+; 10.2 is no longer supported!)

**new features:**

- the scanning process is now 3 times faster (thanks to Dave Payne from Apple)
- show the free space and the space occupied by not shown files (on the selected volume) and like a file in the treemap
- show physical (# of used clusters) or logical (size of content) file size
- ignore creator code (so all those PDF files are shown as "PDF File" and not as "Acrobat PDF File" or "PDF File")
- option to use a small font in the file list and the file kind statistic drawer
- refresh (reload) all or an individual file or folder
- preferences
- toolbar
- The source code for the tree map is now a separate framework to be easily integrated into other applications.

# **0.8 (2004-03-18)**

**bug fixes:**

- program sometimes hanged while scanning folder (reason: overwritten or deleted files)

**new features:**

- a "move to trash" command
- folders can be opened by dragging them on the application icon
- switch between vertical and horizontal splitting in the main window
- Afrikaans translation by Marius van Wyk
- French translation by Daniel Girod
- German translation
- small interface enhancements
- no more uncontrolled pouring of messages to console.log

# **0.7 (2004-03-07)**

- initial public release
