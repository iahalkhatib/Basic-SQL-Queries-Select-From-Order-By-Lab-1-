![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/83e2c87e-caba-4c80-bd1c-6129a687cbb0)


# Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1

# 1. Task 1. Retrieve Employee Device Data 

In this task, I need to obtain information on employee devices because my team needs to update them. The information I need is in the machines table in the organization database.
First, I need to retrieve all the information about the employee devices.
I'll run the following query to select all device information from the machines table.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/4a03293a-6d6b-4e9b-a463-ecf4c2f52be8)


Next, I want to focus on the email client running on various devices. I'll run the following query to select only the device_id and email_client columns from the machines table.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/f77f72aa-b710-4673-8794-04b0073a8881)


Now, I need information on the operating systems used on various devices and their last patch date. I'll complete the query to return only the device_id, operating_system, and OS_patch_date columns from the machines table.


![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/d41eb868-c6c5-498c-90a0-2ac29179178c)


# 2. Task 2. Investigate Login Activities 

In this task, I need to analyze the information from the log_in_attempts table to determine if any unusual activity has occurred. First, I'll investigate the locations where login attempts were made to ensure that they're in expected areas (the United States, Canada, or Mexico). I'll write a SQL query to select the event_id and country columns from the log_in_attempts table.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/73e0b5e3-e087-43c8-b1a8-13c4a699fd0f)



Next, I need to check if login attempts were made outside of the organization's working hours. I'll write a SQL query that selects the username, login_date, and login_time columns from the log_in_attempts table.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/0c35e4ab-876b-4a2f-8b31-720089371ddf)


Now, I need to get a complete picture of all login attempts. I'll write a SQL query that selects all columns from the log_in_attempts table, using a single symbol after the SELECT keyword.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/c693054b-51f5-45cc-ba1c-b590b6c236e7)


# 3. Task 3. Order Login Attempts Data 



In this task, I need to use the ORDER BY keyword to sequence the data returned by my query according to the login date and time. First, I need to sort the information by date. I'll run the following query, which orders log_in_attempts data by login_date

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/b883485e-6e50-40e6-9af8-84298bef74d3)



Now, I need to further organize the previous results by ordering them by login_time. I'll modify the query from the previous step by adding the login time to the ORDER BY clause. I'll replace X with the appropriate column name:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-SelectFrom-OrderBy-Lab-1-/assets/170050432/0e0d42b7-b865-4ec8-b909-c26a19605f70)


I have completed this activity, and I now have practical experience in running basic SQL queries to:

- Select specific columns from a table
- Select all columns from a table by using an asterisk (*)
- Sort query results using the ORDER BY keyword

These basic queries form the foundation for running more advanced queries and applying filters later.

