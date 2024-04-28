# SQL Challenge

The background for the challenge is the following:

It's been two weeks since I was hired as a new data engineer at Pewlett Hackard (a fictional company). My first major task is to conduct
a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that
period are six CSV files. For this project, I'll design the tables to hold the data from the CSV files, import the CSV files into a
SQL database, and then answer questions about the data. That is, I'll perform data modeling, data engineering, and data analysis, respectively.

To complete the challenge, I first created different tables (Table_schemata.sql) and then I imported the csv files into each respective table
- dept_emp
- dept_manager
- salaries
- employees
- titles
- departments

After setting up the tables I complete the following queries (queries.sql):
- List the employee number, last name, first name, sex, and salary of each employee.
- List the first name, last name, and hire date for the employees who were hired in 1986.
- List the manager of each department along with their department number, department name, employee number, last name, and first name.
- List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
- List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
- List each employee in the Sales department, including their employee number, last name, and first name.
- List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
- List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

To complete this activity, I have used resources such as Office Hours and the assistance of ChatGPT to debug and optimize the code's functionality.
Additionally, I mostly used ChatGPT with the funcionality of REFERENCES function.

OpenAI. (n.d.). ChatGPT by OpenAI from https://openai.com/chatgpt
