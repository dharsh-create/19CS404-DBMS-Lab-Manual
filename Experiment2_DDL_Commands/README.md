# Experiment 2: DDL Commands
```

**Output:**

![image](https://github.com/user-attachments/assets/591defed-3658-4976-a479-3704104d7909)

**Question 8**

![image](https://github.com/user-attachments/assets/db29c91b-9692-462e-ac58-ad7c8a035391)

```sql
ALTER TABLE Companies ADD COLUMN designation varchar(50);
ALTER TABLE Companies ADD COLUMN net_salary number;
ALTER TABLE Companies ADD COLUMN dob date;
```

**Output:**

![image](https://github.com/user-attachments/assets/36f6e886-cdbc-40c1-937c-7d2559a0e7b3)

**Question 9**

![image](https://github.com/user-attachments/assets/04c55e88-d808-4cce-9f43-0a4b2daa2943)

```sql
CREATE TABLE jobs(
job_id INT,
job_title TEXT DEFAULT '',
min_salary INT DEFAULT 8000,
max_salary INT DEFAULT NULL);
```

**Output:**

![image](https://github.com/user-attachments/assets/4d67b31f-2b95-4c12-add8-b3054eb0448f)

**Question 10**

![image](https://github.com/user-attachments/assets/baedcb9b-7706-43c1-afd3-a0ca26f7c903)

```sql
ALTER TABLE Student_details ADD COLUMN Email VARCHAR(50);
ALTER TABLE Student_details ADD COLUMN MARKS INT DEFAULT 0;
```

**Output:**

![image](https://github.com/user-attachments/assets/e2dcd365-c733-4639-9d0d-e9db05b3eda1)


## RESULT
Thus, the SQL queries to implement different types of constraints and DDL commands have been executed successfully.
