# Topic Modeller


Java Assignment OOP Yr2 by Adrian Lasan (C22435564)

# Program Goals:

- Aceept 2 text files.

- Add stop words.

- Display % of matching words in selected text files.

- Try design GUI well

# Operations Order:

Button Panel: Displays all the buttons that are usable.

# Select Button:

Usage:
Select Files: Click on the "Select File" button to choose the files you want to compare. You can select two files for comparison.
Click Compare: Once the files are selected and the threshold is set (if desired), click on the "Compare" button.
View Results: After the comparison is completed, the program displays the results in the table. Additionally, if a threshold was set, only the top matching words above the threshold percentage will be displayed.


# Compare Button:

Usage:
Select Files: Click on the "Select File" button to choose the files you want to compare. You can select two files for comparison.
Click Compare: Once the files are selected and the threshold is set (if desired), click on the "Compare" button.
View Results: After the comparison is completed, the program displays the results in the table. Additionally, if a threshold was set, only the top matching words above the threshold percentage will be displayed.

Appearance:
The "Compare" button is adorned with an icon to enhance visual appeal.
It has a dark gray background with white text for better visibility.

Functionality:
The button triggers the CompareFilesActionListener class, which handles the comparison process.
Upon clicking, it retrieves the selected files and threshold value, then initiates the comparison using the compareFiles method.


# Add StopWord Button:

Usage:
TextField: Type in stop word that you want to use.
Click Add Stop Word: Adds the written stop word to the stop word set list and reads it out of the file comparison.

# Clear Button:

Usage: 
Click: Clears all files and reset the stop word list for the next 2 files to be chosen.

# Program:

# MyGUI: 
All of java swing and java util components are in this class its also holds all the code without any 
external program class. Has all the ActionListners and private classes. Holds design of the GUI with icons for the buttons
, colour and buttons. This give the GUI a user freindly experience with a simplistic style. Error checking.

