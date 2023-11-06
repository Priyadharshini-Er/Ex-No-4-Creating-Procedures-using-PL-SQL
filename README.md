# Ex. No: 4 Creating Procedures using PL/SQL
## DATE : 25/9/2023
### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
 CREATE TABLE emp12(empid NUMBER,
  2  empname VARCHAR(10),
  3   dept VARCHAR(10),
  4  salary NUMBER);

CREATE OR REPLACE PROCEDURE insert_employee AS
  2  BEGIN
  3  INSERT INTO emp12(empid, empname, dept, salary)
  4  VALUES (1,'Priya','HR',50000);
  5  INSERT INTO emp12(empid, empname, dept, salary)
  6  VALUES (2,'swetha','IT',60000);
  7  INSERT INTO emp12(empid, empname, dept, salary)
  8  VALUES (3,'thanika','Finance',55000);
  9  COMMIT;
 10  end;
 11  /



       
```


### Output:
![Screenshot 2023-10-04 110916](https://github.com/Priyadharshini-Er/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119558093/eae2c2a2-db91-4722-9589-394e5828a7d3)
![Screenshot 2023-10-04 110928](https://github.com/Priyadharshini-Er/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119558093/746d2763-f625-4cbe-9d4a-7a6ccbb7d6e1)

### Result:
Thus,the output has been successfully verified!
