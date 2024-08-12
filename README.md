# Database 

To design, implement, test and demonstrate elements of relational database applications – as well as provide evidence for data analysis

## Installation
- Must have Oracle APEX
- Download the Schema File

## Analysis
A list of annual salary of each employee who does not earn commission, in surname alphabetical order:

```
SELECT LAST_NAME, SALARY 
FROM EMPLOYEES
WHERE COMMISSION_PCT IS NULL
ORDER BY LAST_NAME;

```
Simply put this query retrieves the last names and salaries of employees who don't have a commission percentage specified and it arranges them alphabetically by last name.
*Shown in Figure 1*

### Figure 1
![image](https://github.com/user-attachments/assets/57a50a05-d486-4e67-929c-5ef0c0b9150e)

A list of departments, corresponding city, country and region names - in city name order

```
SELECT DEPARTMENT_NAME,CITY,COUNTRY_NAME,REGION_NAME
FROM
  DEPARTMENTS D
JOIN
  LOCATIONS L ON D.LOCATION_ID = C.COUNTRY_ID

```
This query retrieves department-related information along with the corresponding city, country, region details and sorts the results based on city names.
*Shown in Figure 2*

### Figure 2
![image(1)](https://github.com/user-attachments/assets/84b7f3b6-cbcd-47e9-8655-e65123416529)


![image(2)](https://github.com/user-attachments/assets/c8278127-17f4-47c6-ab5b-a663a9d78d29)


![image(3)](https://github.com/user-attachments/assets/e730e1c0-b896-4a5c-be48-977bccc47bb9)


![image(5)](https://github.com/user-attachments/assets/a07b137b-39a3-4d33-8c95-f28d0058ea1c)


![image(6)](https://github.com/user-attachments/assets/a691b190-7355-4e8e-9fcf-34aa4e278879)


![image(7)](https://github.com/user-attachments/assets/6a6be1f3-5308-4d3a-ae11-ee51be3ad66a)
![image(8)](https://github.com/user-attachments/assets/d504e519-33ef-4ebf-af30-da2cc5e4f936)
![image(9)](https://github.com/user-attachments/assets/7436edb6-08e3-4970-9ed2-329e57913f05)
![image(4)](https://github.com/user-attachments/assets/718ecb0d-4b2d-46ae-af29-46ddd22b27e1)


## Contributions!

Contributions are welcome! 
Please fork this repo and submit a pull request with your improvements!
