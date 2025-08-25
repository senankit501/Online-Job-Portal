# 💼 Online Job Portal

A complete **Job Portal Web Application** built with **Java (Servlets + JSP)**, **Oracle XE**, and deployed on **Apache Tomcat**.  

This system provides role-based access for **Job Seekers**, **Employers**, and **Admins**, making it easier to post jobs, apply for opportunities, and manage listings.  

---

## ✨ Features

### 👤 User Roles
- **Job Seeker**: Register & login, search/apply for jobs, track applications, receive email notifications.  
- **Employer**: Post job listings, view applicants, update application statuses, get notified on new applications.  
- **Admin**: Manage job listings and users from a centralized dashboard.  

### 🔔 Notifications (via JavaMail API)
- Job application confirmation (to applicants)  
- New applicant notification (to employers)  
- Application status updates  
- Job posting confirmations  

---

## 🎯 Core Modules
- Role-based **User Registration & Login**  
- **Job Search with Filters** (category, location, etc.)  
- **Job Posting & Management** (for Employers)  
- **Application Management** (apply, track, update status)  
- **Admin Dashboard** (manage jobs & users)  
- **Email Integration** using JavaMail API  

---

## 🧱 Tech Stack

| Layer      | Technology |
|------------|------------|
| Frontend   | HTML, CSS, JSP |
| Backend    | Java Servlets, JSP |
| Database   | Oracle XE (10g) |
| Server     | Apache Tomcat 9 |
| IDE        | Eclipse IDE for Enterprise Java |
| Email API  | JavaMail API |

---

## ⚙️ Setup Instructions

### 🔧 Prerequisites
- Java JDK 8+  
- Apache Tomcat 9  
- Oracle XE (10g or above)  
- Eclipse IDE for Enterprise Java  

### 📦 Required JARs
Place the following in **`WEB-INF/lib/`**:  
- `ojdbc8.jar` (Oracle JDBC Driver)  
- `mail.jar` (JavaMail API)  
- `activation.jar` (JavaMail dependency)  

### 🧪 Database Configuration
1. Create an Oracle XE user (e.g., `system/admin`).  
2. Import the required tables:  
   - `user`  
   - `job`  
   - `application`  
   - `notification`  
3. Update DB credentials in DAO files.  

### 📩 Email Setup
- Enable **2-Step Verification** in Gmail.  
- Generate an **App Password** and use it in `EmailUtil.java`.  
- (If required) Allow access to less secure apps.  

---

## 🚀 Run the Project
1. Import the project in **Eclipse** as a *Dynamic Web Project*.  
2. Deploy to **Apache Tomcat**.  
3. Start the server and open localhost  

---

## 🙌 Acknowledgements
- [JavaMail API Documentation](https://javaee.github.io/javamail/)  
- Oracle XE Tutorials  
- Open Source Community & Stack Overflow ❤️  

---
