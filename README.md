# Task 2 INSERT,UPDATE,DELETE
CREATE TABLE employee (
    emp_id INT PRIMARY KEY,
    emp_name VARCHAR(100) NOT NULL,
    age INT,
    salary INT,
    job_title VARCHAR(50),
    email VARCHAR(100) UNIQUE,
    phone_number VARCHAR(15)
    );
Insert into employee (emp_id,emp_name,age,salary,job_title,email,phone_number) values
('1','Uday','30','45000','Developer','uday11@gmail.com','9554762315'),
('2','Alex','28','55000','Programmer','sahu12@gmail.com','9812457542'),
('3','Harry','32','50000','Analyst','alex13@gmail.com','9956431755');

UPDATE employee
SET emp_name = 'SAHU'
WHERE emp_id=2;

DELETE From employee
WHERE emp_id=2;
