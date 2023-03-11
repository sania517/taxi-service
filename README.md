# 🚕🏣 TAXI-SERVICE

### Project description:
> A simple web-app which allows CRUD operations, developed with using SOLID pattern.
> Used N-tire principle for the application: Dao, service and controller layers. 
> Developed Authentication via registration.
> 
### Pages:
|   № | Page                                  |
|----:|---------------------------------------|
|   1 | Authentication for drivers (Sign in)  |
|   2 | Index page with list of pages.        |
|   3 | Display all drivers                   |
|   4 | Display all cars                      |
|   5 | Display all manufacturers             |
|   6 | Add driver (with credentials)         |
|   7 | Add car                               |
|   8 | Add manufacturer                      |
|   9 | Add driver to a car                   |
|  10 | Display all cars for signed in driver |


### Technologies were used to create this project:

- JDK v.11;
- Maven v.4.0.0;
- Java JDBC;
- MySQL database;
- Apache Tomcat software 9.0.71;
- Servlet v.4.0.1;
- HTML/CSS;
- JSTL;
- JSP;
- GIT;

---------------
<h2 id="instructions"> Instructions
</h2>

* Clone the repo from [here](https://github.com/svitlana-tertyshna/taxi-service);
* Install MySQL;
* Configure Apache Tomcat version (IMPORTANT): 9.0.5;
* Copy and run [SQL script](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
* Configure [Connection Util](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
* By default, you will be redirected on page login.jsp.
* The access to main functionality will be opened after registration process on index.jsp page.
* Feel free to look through opened links.
