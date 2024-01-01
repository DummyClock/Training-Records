# Training-Records
For Chic-Fil-A
December 31, 2023

Warning: Each Google Sheet must have at least 1 row of data
-------------------------------------------------------------Background---------------------------------------------------------------
This is a simple micromanagement software designed to automate and systemize the training process for a Back of House Chic-Fil-A team. Refer to the training process graph for a visual representation. 

---------------------------------------------------------------SetUp---------------------------------------------------------------
If this code is being copied over into another Google Scripts project, do the following things as well. ["Or else code no work :( ]

While on a Google Spreadsheet File
1) Link Spreadsheet with Google Forms
     - Create Google Forms and Link them to 1 single spreadsheet
     - Rename the Linked Sheets with the following names: "List_of_Trainers", "Skill_Board", "Requests", "Retraining_Requests", "Initial_Training", "Retraining", "Breading", "Buns", "Dish", "Fries", "Prep", "Rotations", Screens", & "Set-Ups" (Note: The name of these sheets must be spelt exactly the same)
     - Reference the Sample.xlsx for an example setup. Note: The code will work as long as you have the first 6 sheets set up.

While in the Google Scripts Editor
1) Add Gmail API and Calender API
     - This can be done by going to the Editor Tab (of Apps Script) and clicking the Floating '+' button next to "Services." 
     - From there, it will prompt you to add a service. You may have to repeat this process twice in order to get both APIs.
2) Add Triggers
     - Off to the side of the page, there's an alarm clock icon. Click it! In the corner, there will be a giant button saying "+ Add 	Trigger." Click it! You will be greated by a Pop-Up window with dropdown menus. The first dropdown selection should be set to 	'autoSort.' The second dropdown should be set to 'head.' The third dropdown should be set to 'From Spreadsheet.' The last dropdown 	should be set to 'On Form Submit'
3) Grant Authorization
     - In the Google Scripts page, you must click the "Run" button.
     - When you initially test the code, it will ask for code authorization. It's meant to act as a warning before giving a piece of code 	access to your data. Grant it access if you wish to use the code.


--------------------------------------------------------------Caution---------------------------------------------------------------
This code was designed to work with Google Sheets via Google Scripts. It was created to automate the sorting process of any new data that enters a sheet via Google Forms. The sorting process is specific, and reliant on the positioning of certain columns. Therefore, it is highly advised to avoid changing the position of the columns. Granted, changing the column order won't break the code, as it will only disorganize the data. 



