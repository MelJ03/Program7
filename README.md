<h1>Visual Programming Program 6</h1>
<p>We want a program which will keep track of a list of students and their grades. The program will use a dictionary of structures. The structure will contain the student name and the number of points earned and points possible for each of 3 tests. The program has text boxes for the student name and the points earned and points possible for each of 3 tests. It has 5 buttons marked Add, Find, Update, Remove, and Clear.</p>
<p>The user must enter data and click the Add button. This will copy the data into a structure and add it to the dictionary. The key for the dictionary is the name of the student. If there is already a dictionary entry with that name, a message box will show an error message.</p>
<p>When the Find button is clicked, the program looks for the name in the Name text box to see if this is the key to an item in the dictionary. If it is, the program will find the structure with that name and show that data in the text boxes. If no record is found in the dictionary with that name, a message box will show an error message.</p>
<p>When the user clicks the Update button, the program will copy the information from the text boxes into the instance of the structure that corresponds to the item selected in the list. Since the key for the dictionary is the student name, it cannot be updated. Only the test values can be updated. If you wish to allow for the user changing the name of a student, you will also have to delete the record with the incorrect name and add a new record (with the correct test values) using the correct name. If no record is found in the dictionary with that name, a message box will show an error message.</p>
<p>The Remove button will look for a dictionary entry with the name given in the textbox. If the record is found in the dictionary, it will be removed. Otherwise, a message box will show an error message.</p>
<p>The Clear button will empty the text boxes for the student name and the points earned and points possible.</p>
