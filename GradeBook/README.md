# Introduction 
TODO: 
Console App:

We need an electronic grade book to read the scores of an individual student 
and then compute some simple statistics from the scores.
The grades are entered as floating point numbers from 0 to 100, and the statistics should show
us the highest grade, the lowest grade and the average grade.
At the end, a translation from numeric (0-100) grades to letter grades (F - A) is also required


Some steps

1) given a collection of grades, we need to show the average grade in a console application

2) add some class for the grade Book

3) compute lowest grade, highest grade and average grade in main Program

4) move computation code to the Book class but first create a Statistics class to hold the low, high, average grade

5) instead of hard coding the grades use Console.Readline to ask the user  to repeatedly provide grades 
from the console and only stop reading the input if he presses the letter "q"
*Make sure to parse the string into numbers before doing calculations

6) add necessary code to translate a point grade to a letter grade where A = greater than 90, B = greater than 80, 
C = greater than 70, D = greater than 60 and anything below  60 is an F

7) Add OOP into the equation, make it possible for having an InMemoryBook and a DiskBook which would save stuff on disk

8) Add grades to a text file on a new line for each grade introduced  by the user

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)