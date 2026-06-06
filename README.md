# Employee Management System

Advanced Java Web Application developed using:

- JSP
- Servlet
- JDBC
- MySQL
- Apache Tomcat
- JavaMail API

## Features

### Admin Module
- Admin Login
- Add Employee
- View Employee
- Update Employee
- Delete Employee
- Dashboard Statistics
- Employee Count
- Salary Summary

### Employee Module
- Employee Login
- Employee Dashboard
- Profile View

### Additional Features
- Pagination
- Sorting
- Email Notification
- Responsive UI

## Database Setup

1. Open MySQL Workbench
2. Create Database:

```sql
CREATE DATABASE employee_management;
```

3. Import:

```text
database/employee_management.sql
```

## Run Project

1. Maven Build

```bash
mvn clean package
```

2. Copy WAR file from:

```text
target/EmployeeManagementSystem.war
```

3. Paste into:

```text
Tomcat/webapps
```

4. Start Tomcat

```text
startup.bat
```

5. Open:

```text
http://localhost:8080/EmployeeManagementSystem
```

## Admin Credentials

Username:

```text
admin
```

Password:

```text
admin123
```
