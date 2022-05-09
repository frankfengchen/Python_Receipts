# Python_Receipts
The purpose of this project is to help people with accounting needs. Basically people need to save their scanned receipts with the dollar amount in the file name, for example:
"<date>_description_$xxx.xx.pdf"; save all receipts in the same category to one folder, and this tool can then sum it up for them.

This python script will:
1. Scan all files and folders under current folder
2. Look for the last "$" then convert the numeric characters after the "$" to a number
3. Add up all the numbers to come out the a sum/total
4. Create a text file with a summary; the script will prompt if any errors are found.
