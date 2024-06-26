# Console-Unit Testing
This project served as an opportunity to learn about unit testing. In this project, I've created unit tests for the Coding Tracker App that I've created before.I've created a CodingTracker.Tests project, parallel to the coding tracker and reference it in my csproj file. I've only test the validation methods, making sure the app correctly prevents the user from giving incorrect inputs

![the result of unit testing](unit-testing-image-1.jpg)

## Features
- Track shifts per employee. Add, edit, or delete both shifts and employee with a responsive database (delete the employee? All their shifts are gone too!)

![alt text](image-1.png)

## Getting started
- After cloning repo, make sure you have MSSQL server set up.
- IMPORTANT: replace your own MSSQL server information in the OnConfiguring method of ShiftLogContext.cs.
- Log those shifts!


## Comments
- While this is just a simple project meant for learning about APIs and practicing the repository pattern, all are welcome to use this as a template for an ASP.net API or any other purpose you can think of.

## Credit
This project was originally forked from the [C# Academy repo](https://github.com/TheCSharpAcademy/CodeReviews.Console.ShiftsLogger). It has been reuploaded to its own independent repo because the fork contained other students' versions of the project. Shout out to Pablo for making such a great resource!