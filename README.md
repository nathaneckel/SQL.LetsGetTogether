# SQL: Let's Get Together

Given the scenarios, add the the directed queries to the "answers" directory's files.


## Introduction to Joins

Insert the missing parts in the **JOIN** clause to join the two tables **Enrolments** and **Students**, using the **StudentID** field in both tables as the relationship between the two tables.

```
SELECT *
FROM Enrolments
LEFT JOIN Students
[insert clause here];
```
*(Add your query to the file exercise1.sql)*

Choose the correct **JOIN** clause to select all records from the two tables where there is a match in both tables.
#
```
SELECT *
FROM Enrolments
[insert clause here]
ON Enrolments.StudentID=Students.StudentID;
```

*(Add your query to the file exercise2.sql)*


Choose the correct **JOIN** clause to select all the records from the **Students** table plus all the matches in the **Enrolments** table.


```
SELECT *
FROM Enrolments
[insert clause here]
ON Enrolments.StudentID=Students.StudentID;
```

*(Add your query to the file exercise3.sql)*

## Grouping records by Column
List the number of **Students** in each **Country**.


*(Add your query to the file exercise4.sql)*

List the number of **Students** in each **Country**, ordered by the **Country** with the most **Students** first.


*(Add your query to the file exercise5.sql)*



List the number of **Students** in each **Country**, ordered by the **Country** with the most **Students** first, where the number of students is greater than 10.

*(Add your query to the file exercise6.sql)*
