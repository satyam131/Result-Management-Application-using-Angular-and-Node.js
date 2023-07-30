PROJECT NAME :- 
===============
Result Management Application using Angular and Node.js
-------------------------------------------------------

The Result Management Application is a comprehensive web-based solution developed using Angular for the frontend and Node.js with Express.js for the backend. The application serves two types of users: Students and Teachers. Students can log in by clicking a button on the homepage and view their results by entering their roll number and date of birth. Teachers, on the other hand, can access additional functionalities like viewing all records, adding new records, editing existing records, and deleting records.

Key Features:

1.User Authentication: The application offers two types of logins, one for Students and one for Teachers. Students can log in by clicking a designated button on the homepage.

2.Student Result View: Upon successful login, Students are directed to a result view page where they can enter their roll number and date of birth. If the entered roll number and D.O.B. match with the records in the database, the student's result is displayed. Otherwise, an error message is shown on the screen to inform the student of the mismatch.

3.Teacher Dashboard: Teachers have access to a comprehensive dashboard where they can perform various actions related to result management.

4.View All Records: Teachers can view all the student records present in the database, including the roll number, name, and result details.

5.Add New Record: Teachers can add new student records to the database by entering the roll number, name, and result details through the user interface.

6.Edit Records: Teachers have the capability to edit existing student records, allowing them to update result details for specific students.

7.Delete Records: Teachers can delete unwanted student records from the database, ensuring a clean and organized data set.

8.UI Experience: The application emphasizes an enhanced UI experience with a user-friendly and intuitive design. Bootstrap or Materialize can be used for styling, while CSS, SASS, or LESS can be employed for customization.

9.Express.js Backend: The backend is developed using Express.js, a popular Node.js framework, providing a robust and efficient server-side infrastructure.

10.Error Handling: The application implements proper error handling to provide meaningful error messages to users when required.

11.No External JS Dependencies: While Bootstrap or Materialize can be used for styling, the application avoids their JavaScript components, maintaining a lightweight and optimized codebase.

Overall, the Result Management Application using Angular and Node.js offers a seamless and efficient platform for both Students and Teachers to manage and access result data. Its modern UI design and robust backend infrastructure provide an enjoyable user experience and ensure smooth result management operations. The application serves as a valuable tool for educational institutions seeking an effective and user-friendly solution for result management.

TECHNOLOGY USED:-
==================
ANGULAR JS, NODE JS, EXPRESS JS, BOOTSTRAP, CSS.

PROJECT CLONE PROCESS.
======================
STEP 1 :- Clone this project.
STEP 2 :- run command on terminal in VS Code ->  npm i ;
STEP 3 :- run another command on terminal -> npm install json-server
STEP 4 :- run another command on terminal -> json -server --watch db.json
STEP 5 :- then run command on another terminal to launch angular web app application -> ng serve

PROJECT SCREENSHOTS:-
---------------------

LOGIN PAGE :-
<img width="909" alt="login page RMS" src="https://github.com/satyam131/Result-Management-Application-using-Angular-and-Node.js/assets/73646662/6b7c6ca1-c18c-4b98-bd48-e700a39c64a1">

TEACHERS PAGE:-
<img width="916" alt="teacher page RMS" src="https://github.com/satyam131/Result-Management-Application-using-Angular-and-Node.js/assets/73646662/824b6bfd-f7e6-4f1f-a658-69f7c86ab062">

ADDING NEW STUDENT BY TEACHER:-
<img width="886" alt="adding new student RMS" src="https://github.com/satyam131/Result-Management-Application-using-Angular-and-Node.js/assets/73646662/63ee8002-4ceb-4d4b-90ce-f5c2e8496fc5">

STUDENT SEARCH RESULT PORTAL:-
<img width="916" alt="student result search portal" src="https://github.com/satyam131/Result-Management-Application-using-Angular-and-Node.js/assets/73646662/62ad9f57-ec0f-485d-a255-259c395452dd">

==============================================================================================================================================================
# ResultManagementSystem

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

=============================================================================================================================================================================
