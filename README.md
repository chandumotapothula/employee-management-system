Project Structure
Employee-Management-system
|
|
|----backend 
|        |
|        |---src/main/java
|        |            |	
|        |            |---com.ihub.www (base pkg)
|        |            |           |
|        |            |           |---BackendApplication.java 
|        |            |
|        |            |---com.ihub.www.model 
|        |            |           |
|        |            |           |---User.java
|        |            |           |---Employee.java
|        |            |           |---Department.java
|        |            |
|        |            |---com.ihub.www.repo 
|        |            |           |
|        |            |           |---UserRepository.java (interface)
|        |            |           |---EmployeeRepository.java (interface)
|        |            |           |---DepartmentRepository.java (interface)
|        |            |
|        |            |---com.ihub.www.exception 
|        |            |           |
|        |            |           |---ResourceNotFoundException.java
|        |            |
|        |            |---com.ihub.www.service
|        |            |           |
|        |            |           |---AuthService.java
|        |            |           |---EmployeeService.java
|        |            |
|        |            |---com.ihub.www.controller
|        |                        |
|        |                        |---AuthController.java
|        |                        |---EmployeeController.java
|        |
|        |---src/main/resources
|        |          |
|        |          |---application.properties 
|        |
|        |---src/test/java
|        |
|        |---pom.xml 
|
|
|----frontend
|
|---node_modules
|---public
|---src
|    |
|    |----assets
|    |----components
|    |        |
|    |        |----CreateEmployee.jsx
|    |        |----EmployeeList.jsx
|    |        |----Footer.jsx
|    |        |----Header.jsx
|    |        |----Login.jsx
|    |        |----UpdateEmployee.jsx
|    |
|    |----services
|    |        |----AuthService.jsx
|    |        |----EmployeeService.jsx
|    |
|    |----App.css
|    |----App.jsx
|    |----index.css
|    |----main.jsx
|    |----index.html
|    |
|    |----package-lock.json
|    |----package.json
|    |----README.md

A full-stack Employee Management System built using Spring Boot, React, MySQL, Java, and Bootstrap. This application allows users to add, view, update, and delete employees using a clean UI and REST APIs.

🚀 Features
-------------
Create new employee records *View all employees *Edit employee details *Delete employee *Responsive UI using Bootstrap *REST API using Spring Boot *Full CRUD functionality *MySQL database integration

🛠️ Tech Stack
--------------
Frontend *React *Axios *Bootstrap *JavaScript (ES6)

Backend *Java *Spring Boot *Spring Data JPA *Spring Web *MySQL Driver *Lombok

Database *MySQL

🤝 Contributing
-----------------
Contributions are welcome! Feel free to create a pull request or open an issue.

⭐ Support
-----------
If you found this project useful, consider giving it a star ⭐ on GitHub!
