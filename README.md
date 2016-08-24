# Desktop-sweeper
A program to clean up my filthy desktop, or any other folder that needs it

Requires two .txt files, 'doctypes.txt' and 'mediatypes.txt'. 
These are provided and should be added to as needed.
These files contain file extensions, each on a new line, WITHOUT a leading '.'.S

The program asks the user to select a directory to clean, then reads through 
all the files in the chosen directory and sorts them into __MEDIA, 
__DOCUMENT, and __MISC folders, based on the filetypes in the two .txt files.

The following file types will not be moved: lnk, db, appref-ms, tmp.

Outputs a log file in txt format describing the files read and moved, this will
be saved in the directory the script is located.

============================================================
IMPORTANT! Has only been tested on windows 7 and windows 8.1 
============================================================

Would be easy to edit this script to sort any folder into subfolders based on file types
