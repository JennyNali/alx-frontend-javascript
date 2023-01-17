## 0x00. ES6 Basics


Welcome to the JavaScript ES6 Project
This project is designed to help you learn and understand the new features and syntax introduced in JavaScript's ES6 (ECMAScript 6) version.

ES6, also known as ECMAScript 2015, is a significant update to the JavaScript language, and it introduced a number of new features and syntax that make it easier to write and maintain complex JavaScript applications.

Some of the key features introduced in ES6 include:

Arrow functions:
A new syntax for defining functions that is shorter and easier to read than the traditional function syntax.

Classes:
A new syntax for defining classes, which provides a more familiar and intuitive way to create objects and encapsulate behavior.

Template literals:
A new syntax for defining strings that makes it easier to include variables and expressions within string literals.

Destructuring:
A new syntax for extracting values from arrays and objects, which makes it easier to work with complex data structures.

Modules:
A new system for organizing and sharing code, which makes it easier to build and maintain large applications.

This project includes a series of exercises and examples that will help you learn and understand these new features, as well as many others introduced in ES6.
To get started, simply clone the repository and follow the instructions in the exercises. If you get stuck or have any questions, don't hesitate to reach out!


**11-createEmployeesObject.js:** Writing a function named createEmployeesObject that will receive two arguments:
departmentName (String).
employees (Array of Strings).
The function should return an object with the following format:

{
     $departmentName: [
          $employees,
     ],
}


**12-createReportObject.js:** Writing a function named createReportObject whose parameter, employeesList, is the return value of the previous function createEmployeesObject.
createReportObject should return an object containing the key allEmployees and a method property called getNumberOfDepartments.
allEmployees is a key that maps to an object containing the department name and a list of all the employees in that department. If you’re having trouble, use the spread syntax.
The method property receives employeesList and returns the number of departments. I would suggest suggest thinking back to the ES6 method property syntax.


**100-createIteratorObject.js:** Writing a function named createIteratorObject, that will take into argument a report Object created with the previous function createReportObject.
This function will return an iterator to go through every employee in every department.


**101-iterateThroughObject.js:** Finally, write a function named iterateThroughObject. The function’s parameter reportWithIterator is the return value from createIteratorObject.
It should return every employee name in a string, separated by |.
Should return John Doe | Guillaume Salva.
Reminder - the functions will be imported by the test suite.
