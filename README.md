# Task-1
Task 1 :Database Setup and Schema Design.


-- Create the EMPLOYEE table
CREATE TABLE EMPLOYEE (
    empId INT PRIMARY KEY,
    name VARCHAR(15),
    dept VARCHAR(20)
);

-- Insert records into the table
INSERT INTO EMPLOYEE (empId, name, dept) VALUES (1, 'Dave', 'Accounting');
INSERT INTO EMPLOYEE (empId, name, dept) VALUES (2, 'Clark', 'Sales');
INSERT INTO EMPLOYEE (empId, name, dept) VALUES (3, 'Ava', 'Sales');

-- Fetch all data from the table
SELECT * FROM EMPLOYEE;
