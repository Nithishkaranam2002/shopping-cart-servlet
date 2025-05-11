# E-Commerce Shopping Cart

This is a basic Java-based e-commerce shopping cart web application that supports **user registration and login functionalities**. It is built using **Java Servlets, JSP/HTML, and MySQL** for the backend, and styled with **HTML/CSS** for the frontend.

---

## 🔧 Features

* User registration and login using Java Servlets
* MySQL database integration for storing user credentials
* Servlet-based backend with HTML frontend
* Form validation and session management
* Clean and responsive login/signup interface

---

## 🗂️ Project Structure

```
Shopping_Cart/
├── WEB-INF/
│   └── web.xml              # Web deployment descriptor (Servlet mappings)
├── Login.java               # Login Servlet (validates user credentials)
├── Registration.java        # Registration Servlet (adds new user to database)
├── index.html               # Login & Signup form
├── stylesheet.css           # CSS styling
├── MySQL DB: shopping
│   └── reg table: (userName, email, password)
```

---

## 🧪 How to Run

1. **Set up Apache Tomcat Server**

   * Use Tomcat 9+ (or any compatible version)
   * Place your project folder or compiled `.war` file in the `webapps/` directory

2. **Set up MySQL Database**

```sql
CREATE DATABASE shopping;
USE shopping;

CREATE TABLE reg (
    userName VARCHAR(50),
    email VARCHAR(100),
    password VARCHAR(50)
);
```

3. **Update DB Credentials**

   * In `Login.java` and `Registration.java`, modify the DB URL, username, and password if needed

4. **Run the App**

   * Start Apache Tomcat
   * Access the app at: [http://localhost:8080/Shopping\_Cart/index.html](http://localhost:8080/Shopping_Cart/index.html)

---

## 📦 Technologies Used

* Java Servlets (Jakarta EE)
* MySQL Database
* HTML / CSS
* Apache Tomcat
* JDBC

---

## 🙋‍♂️ Author

**Developed by Nithish Karanam**
GitHub: [https://github.com/Nithishkaranam2002](https://github.com/Nithishkaranam2002)
