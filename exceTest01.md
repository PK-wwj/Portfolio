Tasks to perform:

*1.Save the CSV file as an XLSX file:** Change the ‘Viewing’ in the ToolTip to ‘Editing’inorder to save the file as an XLSX file. The file is converted when you click ‘Convert’ in the prompt.
    


*2. **Column widths:** Sort out the widths of all columns so that the data is clearly visible in all cells.
ctrl+a, choose all data and double click column border to autofit column width

*3. **Empty rows:** Use the Filter feature to look for blanks and remove all empty rows from the data.
choose all data and use Table button: insert-> table -> table
after adding filter, get the blank line and delete them

*4. **Duplicate records:** Use either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data.
Data -> remove duplicates, choose all columns

*5. **Spelling:** The original source file data has not been checked for errors in the spelling. Check for spelling mistakes in the data and fix them.
review -> Spelling and Statistics
![[Pasted image 20251229204532.png]]

*6. **Whitespace:** Use the Find and Replace feature to remove all double-spaces from the data.
ctrl+f , find double space and replace to one space


*7. **Department names:** When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now split over two columns in the data. Use Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.

​    Add a new column(choose column B, right click , insert new column) 
​    After that input A2+B2 in C2
​    Click C3,(Data -> Flash Fill)
​    Delete Column A and B