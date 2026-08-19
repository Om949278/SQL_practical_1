create table student(
    student_id int primary key,
    name varchar(20) not null,
    marks int);

insert into student(student_id,name,marks) values (1,'Rahul',60);
insert into student(student_id,name,marks) values (2,'Manthan',70);

select * from student where marks=60;
select * from student where marks=70;

This SQL code first creates a table named student with three columns:
student_id as the primary key, name as a non-null text field, and marks
as an integer field. After defining the structure, two records are inserted 
into the table—one for Rahul with 60 marks and another for Manthan with 70 marks.
Finally, two SELECT queries are executed: the first retrieves the row where marks
equal 60, which returns Rahul’s record, and the second retrieves the row where 
marks equal 70, which returns Manthan’s record. In short, the code demonstrates 
how to define a table, insert data, and filter results using conditions in SQL.
