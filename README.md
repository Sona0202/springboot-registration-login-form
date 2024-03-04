# registration-login-form
1.Initialize Spring Boot Project:
Use Spring Initializr or your preferred IDE to create a new Spring Boot project.
Include dependencies for Spring Web, Spring Data JPA, and MSSQL JDBC driver.
![Screenshot (111)](https://github.com/Sona0202/springboot-registration-login-form/assets/130206732/5d867616-26c0-4c31-945b-d606ccc95f4e)
![Screenshot (120)](https://github.com/Sona0202/springboot-registration-login-form/assets/130206732/9c706762-ce89-453f-b914-04eb0b0e8429)


2.Set Up MSSQL Database:
Install and configure MSSQL Server.
Create a new database for your application.
Configure Spring Boot's application.properties  to connect to the MSSQL database.
![IMG_20240304_133035](https://github.com/Sona0202/springboot-registration-login-form/assets/130206732/6f502fa9-2aaa-4d89-8c54-e6341c9d7956)

3.Create Entity Classes:
Define Java classes representing your database tables using JPA annotations.
Establish relationships between entities if needed.

4.Implement Repository Layer:
Create repositories by extending JpaRepository or CrudRepository interfaces.
Implement custom queries if required.

5.Develop Service Layer:
Create service classes to handle business logic.
Implement methods for CRUD operations and other business logic.

6.Implement Controllers:
Create RESTful controllers to handle HTTP requests.
Map endpoints to appropriate service methods.

7.Develop HTML Frontend:
Create HTML files for your frontend views.
Use Thymeleaf or any other templating engine if needed.
Integrate Bootstrap or other CSS frameworks for styling.

8.Implement Login Functionality:
Create login and registration forms in HTML.
Implement backend authentication and authorization using Spring Security.
Configure security settings in your Spring Boot application.
9.![Screenshot (119)](https://github.com/Sona0202/springboot-registration-login-form/assets/130206732/4791d4e9-91ca-4cfd-b286-3fda7749adbb)

10.run yor application in 8080 port.
![IMG_20240304_144600](https://github.com/Sona0202/springboot-registration-login-form/assets/130206732/12fa6e18-7d18-4777-8746-5090fb766854)

