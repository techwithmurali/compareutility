# compareutility
Utility to compare Files , Excels in Python

1. **FileName**: **CompareFiles.py**

This program takes two directory names as input and compares the files in the two directories and returns output with results of matching.
The CompareFiles.bat can be executed for the same.

2. **FileName**: **Excel_Text.py**
  If we want to compare two excels we can use this program to convert the Excel to Text Files first and then use the CompareFiles.py to compare the Text files.
  
  This program takes the directory name containing Excel files as input and creates a folder called output where the equivalent text files are placed.
  
  Separate Text files will be created for each sheet in the Excel and the Excel name will be in the format - ExcelName_SheetName.txt
  
3. **FileName**: **XML_Text.py**
  This program formats an XML and converts it to a text file so that it can be compared in any Text comparision utility (CompareFiles.py) 
  
  The output files will be in format filename_f.txt where filename.xml is input file.
  
  
  
