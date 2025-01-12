# SQl👨‍💻

SQL (Structured Query Language) is a domain-specific language used for managing and manipulating relational databases. This README provides an overview of essential SQL concepts, commands, and best practices.

## 🔧SQL Basics

### 🛠️Key Components:

1. Tables: Data is organized in rows and columns.

2. Columns: Define the structure of the table (e.g., id, name, salary).

3. Rows: Represent individual records in a table.

4. Primary Key: A unique identifier for each record.

5. Foreign Key: Establishes relationships between tables.

## Practice Questions📖

With these questions i perform my queries and solves the problem statements:

## First : I Create a database 

### input:
![Screenshot 2025-01-11 175105](https://github.com/user-attachments/assets/dbe51ec8-a161-4960-8014-803223ad8130)

### Output:
![Screenshot 2025-01-11 175132](https://github.com/user-attachments/assets/0bfb5bcb-76f4-4a96-b24d-b12c22decf45)

## Second: I create two tables

### Input:
![Screenshot 2025-01-11 175219](https://github.com/user-attachments/assets/a20231d2-6085-4a1f-9de3-a195fa5fdabd)

### Output:
![Screenshot 2025-01-11 175515](https://github.com/user-attachments/assets/59787a64-f837-4934-b098-7baa5360956b)

## Third : I insert data into the Department table

### Input:
![Screenshot 2025-01-11 175455](https://github.com/user-attachments/assets/46860c50-5e83-4c54-80a5-ee3582512bf7)

### output:
![Screenshot 2025-01-11 175544](https://github.com/user-attachments/assets/bc1cdb87-da11-4452-a8fb-0b56a44c9d00)

## Fourth: I insert data into the Employee table

### Input:
![Screenshot 2025-01-11 175637](https://github.com/user-attachments/assets/4095c004-e3f5-443d-98ca-16dc356ae8e6)

### output:
![Screenshot 2025-01-11 175742](https://github.com/user-attachments/assets/9602a750-a2f4-4fc7-a7da-f7f7af9766c8)

## Fifth : I practice questions by taking these two tables and solve them:

### Question 1. Find the Second Highest Salary

Problem: Find the second highest salary from the Employee table.

#### Input: Using Limit subquery
![Screenshot 2025-01-11 180505](https://github.com/user-attachments/assets/2f91c65b-a785-4b2e-803b-bfa1ee06b40d)

#### Output:
![Screenshot 2025-01-11 180520](https://github.com/user-attachments/assets/11136ac3-15c4-4aca-9933-d0893c096841)

#### Input: Using Window Function:
![Screenshot 2025-01-11 181052](https://github.com/user-attachments/assets/16795194-db79-40d2-8055-06b41a094261)

#### Output:
![Screenshot 2025-01-11 181107](https://github.com/user-attachments/assets/740d603e-345c-4905-80a7-d2ec32b768cb)

### Question 2. List of Departments with More Than 2 Employees

Problem: List department names where the number of employees is greater than 2.

#### input:
![Screenshot 2025-01-11 182104](https://github.com/user-attachments/assets/11d5f66c-d4bd-4f57-ba9a-4b01d5a89a61)

#### Output:
![Screenshot 2025-01-11 182114](https://github.com/user-attachments/assets/96632bfa-1cec-4f2e-86cf-46488c1375ea)

### Question 3. Find all the Employees Who Earn More than all the employees of Legal department 

Problem: Find names of employees who earn more than Legal.

#### Input:
![Screenshot 2025-01-11 184406](https://github.com/user-attachments/assets/f13cc622-c46a-4d02-802d-4a7755bfde96)

#### Output:
![Screenshot 2025-01-11 184421](https://github.com/user-attachments/assets/4bd1cba0-6129-466c-8390-5138f5abc288)

### Question 4. Retrieve the Top 3 Highest-Paid Employees in Each Department

Problem: List the top 3 highest-paid employees from each department.

#### Input:
![Screenshot 2025-01-11 185739](https://github.com/user-attachments/assets/118fa983-ae69-4345-b8f9-2967ca699667)

#### Output:
![Screenshot 2025-01-11 185753](https://github.com/user-attachments/assets/cf60782b-4533-460c-98b7-ed743507f92b)

### Question 5. Retrieve names of employees whose names start with "A" and end with "n".

#### Input:
![Screenshot 2025-01-11 190751](https://github.com/user-attachments/assets/c8f18db2-cb66-4fc6-8489-c9197ac43844)

#### Output:
![Screenshot 2025-01-11 190800](https://github.com/user-attachments/assets/18d871f7-b4c4-49e1-9e6a-d2747dd2a528)

### Question 6. Display the total count of employees grouped by their department.

#### Input:
![Screenshot 2025-01-11 191524](https://github.com/user-attachments/assets/e32223b5-ab5a-4e80-bbf8-4cf7f9352254)

#### Output:
![Screenshot 2025-01-11 191536](https://github.com/user-attachments/assets/dd7743dc-b053-4188-9249-24f15ea9080e)

### Question 7. Find All Employees Who Have Not given Any E-mail id.

#### Input:
![Screenshot 2025-01-11 190302](https://github.com/user-attachments/assets/f16ad860-edbb-4d23-a0eb-2ca5d2dff0ed)

#### Output:
![Screenshot 2025-01-11 190313](https://github.com/user-attachments/assets/bbe57981-be54-4b3a-9bf4-16fc0c066e94)

I have not any such Employee so that's why my output is shown nill.

### Question 8. Find the maximum, minimum, and average salary of employees in each department.

#### Input:
![Screenshot 2025-01-11 192054](https://github.com/user-attachments/assets/4a71d91e-9ccd-4f80-9509-b161b9ca8530)

#### Output:
![Screenshot 2025-01-11 192104](https://github.com/user-attachments/assets/7782da76-1c87-4151-8b81-0d106854cfdb)

### Question 9. Write a query to fetch the names of employees who earn more than the average salary in their department.

#### Input:
![Screenshot 2025-01-11 192601](https://github.com/user-attachments/assets/b809d05d-88ee-4143-8ffd-f2f037e6e087)

#### Output:
![Screenshot 2025-01-11 192610](https://github.com/user-attachments/assets/9a59aec8-d8e6-4206-92cc-3281ca72a954)

### Question 10. Find the names of employees who work in the same department as "John Doe".

#### Input:
![Screenshot 2025-01-11 194547](https://github.com/user-attachments/assets/8734f94e-0b7b-4005-a11b-c3699050c05c)

#### Output:
![Screenshot 2025-01-11 194559](https://github.com/user-attachments/assets/7cc80804-3214-4a15-aead-8e158a123e48)

### Question 11. Fetch employees with salaries in the top 10%:

#### Input:
![Screenshot 2025-01-11 200602](https://github.com/user-attachments/assets/181d7160-6620-461c-a3a9-ac638fa7f1f6)

My Sql doesn't support percentile_cont function that's why i use ntile function, if your sql support the percentile_cont function then use that.

#### Output:
![Screenshot 2025-01-11 200613](https://github.com/user-attachments/assets/fd477309-3671-4a96-8f4a-c9ee176d0dbc)

### Question 12. Write a query to find employees with the same salary.

#### Input:
![Screenshot 2025-01-11 202109](https://github.com/user-attachments/assets/9dcd7a5d-94b8-419d-a5aa-e7239858d514)

#### Output:
![Screenshot 2025-01-11 202118](https://github.com/user-attachments/assets/fb2d4044-e76c-4d3c-b5e5-472e91412eda)

### Question 13. Calculate the running total of salarie.

#### Input:
![Screenshot 2025-01-11 202607](https://github.com/user-attachments/assets/0934e4f9-7e85-43f3-bc57-80f6975d44fd)

#### Output:
![Screenshot 2025-01-11 202702](https://github.com/user-attachments/assets/9c4a487d-9a8a-434d-aa94-522b708fd026)

### Question 14. Fetch the department with the highest average salary.

#### input:
![Screenshot 2025-01-11 204413](https://github.com/user-attachments/assets/a5302a40-0a83-49b5-bd82-6a6fcadf975f)

#### Output:
![Screenshot 2025-01-11 204422](https://github.com/user-attachments/assets/e1eb0ba8-9553-47a8-b7ee-02d5d7376deb)

### Question 15. Find the percentage contribution of each employee's salary within their department.

#### Input:
![Screenshot 2025-01-12 151429](https://github.com/user-attachments/assets/bd843ad8-8b9b-4ce0-b514-2bfb8ac996ca)

#### Output:
![Screenshot 2025-01-12 151445](https://github.com/user-attachments/assets/cdfd59a1-1b0b-420c-954d-d0013f656539)


----------
## Conclusion:👁️

SQL is a powerful language for managing relational databases. By mastering its features and adhering to best practices, you can effectively query, manipulate, and maintain your data systems.
I show you a query that apply on these two tables these are very affective and useful for future.
----------

Thank you Using Query🥳

