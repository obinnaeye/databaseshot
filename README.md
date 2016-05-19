# databaseshot
My database snapshot is here

Here is the querry report:

SELECT id, FROM poultry_management WHERE department = '%turkey%';

SELECT COUNT(id) FROM poultry_management WHERE present_gdp = 2000000;

SELECT * FROM department ORDER BY dep_reg DESC LIMIT 10;

DELETE FROM poultry_management WHERE dep_reg = 474;

TRUNCATE TABLE department
