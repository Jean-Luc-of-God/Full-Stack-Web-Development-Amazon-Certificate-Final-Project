```markdown
# To-Do List Web Application

## Overview
This project is a full-stack To-Do List web application that allows users to manage their daily tasks. It combines front-end, back-end, and security features to create a complete working system.

Each user can register, log in securely, and manage their own tasks. Users can add, edit, delete, and mark tasks as completed. Tasks due today are highlighted and color-coded by priority for better visibility.

## Main Features
- User registration and login with Spring Boot Security
- Password change functionality for logged-in users
- Add, edit, delete, and complete tasks
- Dashboard showing pending and completed tasks
- Tasks due today appear at the top
- Color-coded priorities:
  - Red = High
  - Yellow = Medium
  - Green = Low
- CSS color scheme for better visual appeal
- Secure access (users see only their own tasks)

## Technologies Used
- **Front-End:** HTML, CSS, JavaScript, Thymeleaf  
- **Back-End:** Spring Boot  
- **Security:** Spring Boot Security  
- **Build Tool:** Maven  
- **Database:** H2 or MySQL  

## Project Structure
```

to-do-app/
│
├── src/
│   ├── main/
│   │   ├── java/com/example/todo/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   └── service/
│   │   ├── resources/
│   │   │   ├── templates/
│   │   │   ├── static/
│   │   │   └── application.properties
│   └── test/
├── pom.xml
└── README.md

````

## Application Flow
1. **Homepage:** User chooses to log in or register
2. **Registration:** Create an account
   - Successful → Redirect to login page
   - Failed → Show error (e.g., username already exists)
3. **Login:** Enter credentials
   - Successful → Go to dashboard
   - Failed → Show error
4. **Dashboard:**
   - Add, edit, delete, and complete tasks
   - View color-coded and date-highlighted tasks
5. **Logout:** Ends session securely

## How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/todo-list-app.git

# Navigate to the project folder
cd todo-list-app

# Build with Maven
mvn clean install

# Run the Spring Boot application
mvn spring-boot:run

# Open in your browser
http://localhost:8080
````

## Future Improvements

* Add email verification for new users
* Add task reminders or notifications
* Implement dark/light mode
* Support sharing tasks with others

## Author

**MANISHIMWE KWIZERA Jean Luc**
Full-Stack Developer in Training

```
```
