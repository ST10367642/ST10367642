- 👋 Hi, I’m @ST10367642
A  summary of the changes you made in response to the lecturers' feedback 
I've improved the functionality and clarity of the original code in a few places in response to the lecturer's criticism. 

To make sure the user provides a positive integer for the number of ingredients and stages, I have first introduced input validation. To accomplish this, utilize the int.TryParse function, which yields a boolean result indicating if the parse of the user's input was successful. The user is prompted to submit a valid positive integer if the parsing fails. 

Second, to keep the materials and steps, I've switched out arrays with lists. This is due to the fact that lists can expand dynamically when new items are added, whereas arrays have a fixed size. Lists are therefore a better option for storing user-generated data. 

Thirdly, to make the code easier to read, I inserted whitespace. This involves consistently indenting code blocks and inserting blank lines in between.

Fourthly, I created the strings that show the processes and ingredients using StringBuilder. When joining numerous strings together, this method proves to be more efficient than utilizing string concatenation. 

Lastly, I've included a note that points out possible places to add further functionality, including scaling, quantity resets, and data clearing. This will assist the user in expanding the application and including new features as required.

All things considered, these modifications have enhanced the code's functionality and readability, making it easier to use and maintain.


To compile and run the software
To get the software to compile and run, do the following: 

Launch a text editor or Visual Studio or Visual Studio Code, or any other Integrated Development Environment (IDE) that supports C#.
The code should be copied, pasted, and saved as Recipe.cs or another file ending in.cs. 

Point a command prompt or terminal window to the directory containing the saved.cs file. 
Run the following command to compile the code using the C# compiler (csc): 
As a result, the.cs file and the.exe file will have the identical name. 

Open the.exe file to launch the program:
for Full Screen at./Recipe.exe 

Enter the number of steps and ingredients in your recipe, as well as the names, quantities, and units of each item, by following the prompts. 
The application will show the recipe along with a list of ingredients and instructions.

