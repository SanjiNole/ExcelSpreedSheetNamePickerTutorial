# ExcelSpreedSheetNamePickerTutorial
Tutorial for making simple name picker on Excel Spreadsheet

![Screenshot (212)](https://github.com/user-attachments/assets/04a97144-fb19-4b0c-b820-78dc759adbf9)
Here are the list of my names I have lined up. Today I will be showcasing how to make a name generator using a simple formula.

![Screenshot (213)](https://github.com/user-attachments/assets/8eaa8e97-0bb6-4c3d-b38d-2b879d401860)
In a random cell I typed this in 
=INDEX(A1:A10, RANDBETWEEN(1, COUNTA(A1:A10)))
This works because: 

INDEX(A1:A10, ...): This function retrieves a value from the specified range (A1:A10).

RANDBETWEEN(1, COUNTA(A1:A10)): This generates a random integer between 1 and the number of names in your list.

COUNTA(A1:A10): This counts the number of non-empty cells in the range A1:A10, ensuring the random number is within the correct range.

![Screenshot (214)](https://github.com/user-attachments/assets/657e028d-d1af-4859-aeed-63547eabbadd)
From there I imputted the command and funny enough I generated the name goku on the first try Haha

![Screenshot (215)](https://github.com/user-attachments/assets/339664c0-8bd7-445b-9cbf-c8f2c8c3812c)
I then typed randomly in the cell below that one and went from Goku to Lassie 
This is because the formula I typed generated that as a random integer
