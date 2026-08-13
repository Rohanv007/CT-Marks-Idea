# CT-Marks-Idea

# CT-Marks Web App

## 1. Problem Statement

In colleges, CT (Class Test) marks are often managed manually. This can lead to mistakes while entering marks, calculating totals and percentages, or maintaining student records. It can also take a lot of time for teachers to prepare results.

Students may also face problems when they want to check their marks or understand their performance. There should be a simple system where teachers can manage marks and students can easily check their results.

So, our idea is to create a **CT-Marks Web App** where all the marks can be managed in one place. The application will have different access for Admin, Faculty, and Students according to their roles.

## 2. Users and Their Roles

### Administrator

The Administrator can be an HOD, Principal, or Department Head.

The Administrator will be able to:

* Manage students and faculty.
* Add or manage subjects and classes.
* View marks and overall results.
* Publish results and report cards.
* Check the overall performance of students.
* Manage user accounts and permissions.

### Faculty / Teacher

Teachers will manage the marks for the subjects and classes assigned to them.

They will be able to:

* Enter CT marks of students.
* Correct marks if there is any mistake before submitting.
* Submit the final marks.
* View the performance of their class.
* Check automatically calculated totals, averages, and percentages.

### Student

Students will have limited access to the application.

They will be able to:

* Login to their account.
* View their CT marks.
* Check their subject-wise performance.
* View total marks, average, percentage, and grade.
* View their published report card.

## 3. UI Flow

The basic flow of our application will be:

```text
                    Login
                      ↓
                Authentication
                      ↓
              Role-based Dashboard
                      ↓
       ┌──────────────┼──────────────┐
       ↓              ↓              ↓
     Admin          Faculty        Student
       ↓              ↓              ↓
 Manage Users     Enter Marks     View Marks
       ↓              ↓              ↓
 View Results     Check Marks     View Results
       ↓              ↓              ↓
Publish Results   Submit Marks    Report Card
```

We will try to keep the UI simple and easy to understand so that users can quickly find the features they need.

## 4. Input From Each User

### Administrator

The Administrator may enter:

* Student details
* Faculty details
* Class and branch details
* Subject details
* CT/test details
* Maximum marks
* User account details

### Faculty / Teacher

The teacher will enter:

* Student roll number
* Student name
* Subject
* CT number
* Marks obtained
* Test date

After entering the marks, the system will check the values and automatically calculate the required results.

### Student

Students will mainly enter:

* Username / Email
* Password

Students will only be able to view their marks and results. They will not have permission to change or edit their marks.

## 5. Application

The main purpose of this application is to make the process of managing CT marks easier for both teachers and students.

Instead of maintaining marks manually, teachers can enter them into the application. The system will then store the marks and automatically calculate things like total marks, average, percentage, and grade.

Some of the main features we are planning are:

* Secure login for different users
* Separate dashboards for Admin, Faculty, and Students
* Easy marks entry
* Checking marks before submission
* Automatic calculation of results
* Student and class performance view
* Result and report-card generation
* Publishing of results
* Secure storage of marks
* Different permissions for different users

The main goal of our project is to **make CT marks management simple, less time-consuming, and more transparent**, while also reducing manual calculation and data-entry mistakes.
