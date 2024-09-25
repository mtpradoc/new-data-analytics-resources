## SQL Practice ##

Navigate to sql-practice.com
1. Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)
2. Show first name, last name, and gender of all Female patients.

```
-- Answer 1
SELECT 
	first_name,
    last_name,
    weight
FROM patients
WHERE weight BETWEEN 100 AND 120
ORDER BY weight desc;
````
````
-- Answer 2
SELECT
	first_name,
    last_name,
    gender
FROM patients
WHERE gender = 'F';
```
