This database shows the grade point of the Mechanical Engineering students of Edinburgh University. The student table contains the id, first name,last name, department id and Matric No.
The dept_table shows the dept id, and dept name. The gradepoint_table shows the gradepoint_table id, student_table and gradepoint of each student.

INSERT INTO student_table VALUES(NULL,"Michael","Omokehinde" "09/30gd060"); 

INSERT INTO student_table VALUES(NULL,"Nancy","adesuwa"); 
 
INSERT INTO gradepoint_table VALUES(NULL,"computer technology");

SELECT * FROM student_table;

SELECT* FROM dept_table;

SELECT first_name,last_name FROM student_table WHERE id=1; 

DELETE FROM student_table WHERE id = 2;

UPDATE gradepoint_table SET first_name = surajudeen;



