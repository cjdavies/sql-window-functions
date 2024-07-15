---
created: 2024-07-15T16:28:20 (UTC -07:00)
tags: []
source: https://www.coursera.org/learn/introduction-to-sql-window-functions/supplement/MhGNK/project-overview
author: 
---

# Project Overview | Coursera

> ## Excerpt
> Welcome to this project-based course Introduction to SQL Window Functions. This is a hands-on project that introduces SQL users to the world of window functions. In this project, you will learn how to explore and query the project-db database ...

---
## **Welcome to Your Guided Project!**

Welcome to **Introduction to SQL Window Functions**. This is an intermediate project-based course that should take approximately 2 hours 30 minutes to finish. Before diving into the project, please take a look at the course objectives and structure:

## **Guided Project Objectives**

In this course, we are going to focus on **three** learning objectives:

1.  Understand how SQL window functions work and when to use them
    
2.  Understand how the ORDER BY and PARTITION BY clauses work with the OVER() clause
    
3.  Manipulate data in tables using SQL SELECT statements together with window functions
    

By the end of this course, you will be able to use different SQL window functions to perform data aggregation, reporting, manipulation, and querying for database insights using the projectdb database.

## **Guided Project Structure**

This course is divided into **six (6)** parts:

1.  Course Overview: This introductory reading material.
    
2.  Reading: SQL files and data sets for the project
    
3.  Additional Reading: PostgreSQL Window Functions Documentation
    
4.  **Introduction to SQL Window Functions:** This is the hands-on project that we will work on together in Rhyme
    
5.  Graded Quiz: This is the final assignment that you need to pass in order to finish the project successfully.
    
6.  **Course End (Learner) Survey:** Tell us what you thought about this guided project!
    

## **Project Structure**

The hands-on project on **Introduction to SQL Window Functions** is divided into the following tasks:

## **Task 1: Getting Started**

-   Overview of the project
    
-   A brief introduction to the Rhyme platform
    
-   What are window functions in SQL?
    
-   Retrieve all the data in the projectdb database
    

## **Task 2: ROW\_NUMBER() - Part One**

-   Assign numbers to each row of the departments table
    
-   **Exercise 2.1:** Assign numbers to each row of the department for the Entertainment division
    

## **Task 3: ROW\_NUMBER() - Part Two**

-   Retrieve all the data from the employees table
    
-   Retrieve a list of employee\_id, first\_name, hire\_date, and department of all employees in the sports department ordered by the hire date
    
-   Order by multiple columns
    
-   Ordering in- and outside the OVER() clause
    

## **Task 4: PARTITION BY**

-   Retrieve the employee\_id, first\_name, hire\_date of employees for different departments
    
-   **Exercise 4.1:** Order by the hire\_date
    

## **Task 5: PARTITION BY WITH CTE**

-   Retrieve all data from the sales and customers tables
    
-   Create a common table expression to retrieve the customer\_id, customer\_name, segment, and how many times the customer has purchased from the mall
    
-   Number each customer by how many purchases they've made
    
-   **Exercise 5.1:** Number each customer by their customer segment and by how many purchases they've made in descending order
    

## **Task 6: Fetching: LEAD() & LAG()**

-   Retrieve all employees first name, department, salary, and the salary after that employee
    
-   Retrieve all employees first name, department, salary, and the salary before that employee
    
-   Retrieve all employees first name, department, salary, and the salary after that employee in order of their salaries
    
-   **Exercise 6.1:** Retrieve all employees first name, department, salary, and the salary before that employee in order of their salaries. Call the new column closest\_higher\_salary
    
-   **Exercise 6.2:** Retrieve all employees first name, department, salary, and the salary after that employee for each department in order of their salaries. Call the new column closest\_lowest\_salary
    

## **Task 7: FIRST\_VALUE() - Part One**

-   Retrieve the first\_name, last\_name, department, and hire\_date of all employees. Add a new column called first\_emp\_date that returns the hire date of the first hired employee
    
-   Find the difference between the hire date of the first employee hired and every other employees
    
-   **Exercise 7.1:** Partition by department
    
-   **Exercise 7.2:** Find the difference between the hire date of the first employee hired and every other employees partitioned by department
    

## **Task 8: FIRST\_VALUE() - Part Two**

-   **Exercise 8.1:** Return the first salary for different departments, Order by the salary in descending order
    
-   **Exercise 8.2:** Return the first salary for different departments. Order by the first\_name in ascending order
    
-   Return the fifth salary for different departments. Order by the first\_name in ascending order
    
-   Wrap up the project
    

## **Meet the Instructor**

My name is Olayinka Imisioluwa Arimoro and I will be taking you through this Guided Project. I am a guided project instructor with a deep interest in statistical learning and machine learning applications to human disease, clinical trials, and patient-reported outcomes. I am passionate about teaching others relevant skills in different sectors.

## **About workspaces**

This project runs on Coursera's hands-on platform called Rhyme. On Rhyme, you do projects in a hands-on manner in your browser. You will get instant access to pre-configured cloud desktops that have all the software and data you will need. So, you can just focus on learning. For this project, this means instant access to a cloud desktop with PostgreSQL pre-installed.

If you need help troubleshooting Rhyme, please refer to the [Coursera Help Center](https://learner.coursera.help/hc/en-us/search?query=rhyme&utf8=%E2%9C%93 "coursera help center") for more information.

## **Earn a Certificate**

After you have completed the **Introduction to SQL Window Functions** hands-on project, you will be able to assess your knowledge using an ungraded assignment. Once you are comfortable with the concepts, take the final quiz, score higher than 80% to [earn your certificate](https://learner.coursera.help/hc/en-us/articles/209819053-Get-a-Course-Certificate "link to article about how to earn a course certificate").
EOF