# 💼 HireNest – Online Recruitment and Job Management System

HireNest is a full-stack Online Recruitment and Job Management System developed using Java and Spring Boot. The platform provides a centralized recruitment solution where job seekers can search and apply for jobs, recruiters can manage job postings and applicants, and administrators can monitor recruitment activities efficiently.

---

# 🚀 Features

## 👨‍💼 Job Seeker Module
- User Registration & Login
- OTP-based Email Verification
- Browse and Search Jobs
- Apply for Jobs Online
- Upload Resume & Profile Image
- Track Applied Jobs
- Password Reset via Email

---

## 🏢 Recruiter Module
- Recruiter Registration & Authentication
- Post and Manage Job Openings
- View Applicants
- Download Resumes
- Manage Recruitment Activities

---

## 🛡️ Admin Module
- Monitor Users and Recruiters
- Manage Job Listings
- Track Recruitment Activities
- Platform Management Dashboard

---

# 🛠️ Tech Stack

## Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate ORM

## Frontend
- Thymeleaf
- HTML5
- CSS3
- Bootstrap
- JavaScript

## Database
- MySQL

## Third-Party Integrations
- JavaMailSender (Gmail SMTP)
- Cloudinary

## Build Tool
- Maven

---

# 🏗️ System Architecture

The project follows the MVC (Model-View-Controller) Architecture:

```bash
Controller Layer → Handles HTTP Requests
Service Layer    → Business Logic
Repository Layer → Database Operations
View Layer       → Thymeleaf Frontend
Database         → MySQL
```

---

# 📂 Project Structure

```bash
HireNest/
│
├── src/main/java/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── entity/
│   ├── dto/
│   ├── config/
│   └── security/
│
├── src/main/resources/
│   ├── templates/
│   ├── static/
│   └── application.properties
│
├── pom.xml
└── README.md
```

---

# ⚙️ Installation & Setup

Follow the steps below to run the project locally.

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/HireNest.git
```

---

## 2️⃣ Navigate to the Project Directory

```bash
cd HireNest
```

---

## 3️⃣ Configure MySQL Database

Create a MySQL database:

```sql
CREATE DATABASE hirenest;
```

Update the `application.properties` file:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/hirenest
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## 4️⃣ Configure Email Service

Configure JavaMailSender for OTP verification and notifications:

```properties
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=YOUR_EMAIL@gmail.com
spring.mail.password=YOUR_APP_PASSWORD

spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
```

> ⚠️ Use Gmail App Password instead of your normal Gmail password.

---

## 5️⃣ Configure Cloudinary

Add your Cloudinary credentials:

```properties
cloudinary.cloud_name=YOUR_CLOUD_NAME
cloudinary.api_key=YOUR_API_KEY
cloudinary.api_secret=YOUR_API_SECRET
```

---

## 6️⃣ Install Dependencies

```bash
mvn clean install
```

---

## 7️⃣ Run the Application

```bash
mvn spring-boot:run
```

---

## 8️⃣ Open in Browser

```bash
http://localhost:8080
```

---

# 🔒 Security Features

- OTP-based Email Verification
- Secure Password Reset
- Session-based Authentication
- Form Validation
- Secure Resume Upload Handling

---

# ☁️ Cloud Features

- Resume Storage using Cloudinary
- Profile Image Storage
- Cloud-based Media Management

---

# 📸 Screenshots

> Add project screenshots here

- Home Page
- Job Listings
- Recruiter Dashboard
- Applicant Management
- Admin Dashboard
- User Profile Page

---

# 🎯 Future Enhancements

- AI-based Resume Screening
- Job Recommendation System
- Interview Scheduling
- Real-time Notifications
- Video Interview Integration
- Mobile Application Support

---

# 👨‍💻 Author

## Ramchandra Jalasangi

- Java Full Stack Developer
- Passionate about Scalable Web Applications & Backend Development

---

# 📜 License

This project is developed for educational and portfolio purposes.

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub!
