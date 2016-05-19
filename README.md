# databaseshot
//My database snapshot is here

//Here is the querry report:

// This shows all id where department contains turkey in poultry_management table

SELECT id, FROM poultry_management WHERE department = '%turkey%';

// This shows the number of times where present gdp is 2000000 in poultry_management table
SELECT COUNT(id) FROM poultry_management WHERE present_gdp = 2000000;

// This shows all field in department, arranging them in descending order of dep_reg
SELECT * FROM department ORDER BY dep_reg DESC LIMIT 10;

// This deletes the row where dep_reg is 474 in poultry_management table
DELETE FROM poultry_management WHERE dep_reg = 474;

// This will reset the table primary key (ie id) in department table 
TRUNCATE TABLE department
