# SQL-IEEE

CREATE TABLE Employee (
    Employee_id INT ,
    First_Name VARCHAR(20),
    Last_Name VARCHAR(20),
    Age INT ,
    Email VARCHAR(100),
    PRIMARY KEY (Employee_id)
);
DESCRIBE Employee;

DROP TABLE Employee_id

ALTER TABLE Employee ADD salary DECIMAL(20,3);

ALTER TABLE Employee DROP COLUMN salary;

SELECT * FROM Employee

INSERT INTO Employee VALUES(1,'Amr','Yasser',20,'amr.yassr.2@gmail.com');
