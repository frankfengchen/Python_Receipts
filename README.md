# Python_Receipts (sum_in_dir.py)
The purpose of this project is to help people with accounting needs. Basically people need to save their scanned receipts with the dollar amount in the file name, for example:
"<date>_description_$xxx.xx.pdf"; save all receipts in the same category to one folder, and this tool can then sum it up for them.

This python script will:
1. Scan all files and folders under current folder
2. Look for the last "$" then convert the numeric characters after the "$" to a number
3. Add up all the numbers to come out the a sum/total
4. Create a text file with a summary; the script will prompt if any errors are found.
5. Report below errors:
    - File names that don't contain a "$" symbol

All the files/directories should put the $ amount at the end of the file name starting with a "$" symbol (of course the file extension is after everything else)
Some examples for valid names:
	- "20220101_Rudys_$101.22.pdf" (this if a PDF file)
	- "20220101_Remodel_$3679.82" (this is a directory)

[Command line usage]
 	- In Windows, add the program location to PATH, open Cmd Prompt, type: 
 		- "sum_i_dir.py" (this is for normal mode)
 		- "sum_i_dir.py debug" (this is for debug mode)
