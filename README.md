# 🚗 AutoRentHub – Car Rental Web Application

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/Apache%20Tomcat-F8DC75?style=for-the-badge&logo=apache-tomcat&logoColor=black)

**AutoRentHub** is a full-stack car rental management system developed as an academic IT project. The system facilitates a seamless experience for customers to browse and rent vehicles while providing administrators with robust tools to manage fleet inventory, bookings, and user data.

---

## 📂 Project Structure

```text
IT-Projects/
 ├── AutoRentHub-Backend/      # Java backend (JSP/Servlets/Model/DAO)
 └── autorenthub-frontend/     # Static Frontend assets (HTML, CSS, JS)
````

---

## 🛠 Technology Stack

### 🔹 Backend
- Java  
- JSP & Servlets  
- JDBC  
- Apache Tomcat  
- MySQL  

### 🔹 Frontend
- HTML  
- CSS  
- JavaScript  
- Bootstrap (for responsive UI)

---

## ✨ Features

### 🚗 Customer Features
- User registration and login  
- Browse available vehicles  
- View car details (model, price, availability)  
- Book / rent vehicles  
- View booking history  

### 🧑‍💼 Admin Features
- Admin login dashboard  
- Add, update, and delete vehicles  
- Manage vehicle availability  
- View and manage customer bookings  
- Manage registered users  

### 🔐 System Features
- Secure authentication & session handling  
- Full CRUD operations with database  
- Form validation  
- MVC-based architecture (JSP + Servlets + DAO)

---

## ⚙️ How to Run the Project Locally

### 🧩 Prerequisites

Make sure you have the following installed:

- JDK 8 or higher  
- Apache Tomcat 9  
- MySQL Server  
- Eclipse or VS Code  
- Git  

---

### ▶️ Backend Setup (AutoRentHub-Backend)

1. Open the project in **Eclipse** (recommended)  
2. Import as a **Dynamic Web Project**  
3. Configure **Apache Tomcat Server**  
4. Update database credentials inside:

DBConnection.java


5. Create a MySQL database (example name: `autorenthub`)  
6. Run the SQL scripts to create required tables  
7. Deploy and run the project on Tomcat  

Backend will run at:

http://localhost:8080/AutoRentHub


---

### 🌐 Frontend Setup (autorenthub-frontend)

You can run the frontend in two ways:

**Option 1 — Using Live Server (VS Code)**  
1. Open the `autorenthub-frontend` folder in VS Code  
2. Install the **Live Server** extension  
3. Right-click `index.html` → **Open with Live Server**

**Option 2 — Through JSP Pages**  
Frontend pages are also served through backend JSP views when running the Tomcat server.

---

## 🗄 Database

MySQL is used to store:

- Users  
- Vehicles  
- Bookings  
- Admin data  

⚠️ Make sure the database server is running before starting the backend.

---

## 📷 Future Improvements

- Online payment integration  
- Email notifications  
- Admin analytics dashboard  
- REST API conversion  

---

## 👨‍💻 Author

**Dinith Tharusha**  
IT Undergraduate – SLIIT  

---

## 📄 License

This project was developed for academic purposes.
IT Undergraduate – SLIIT

📄 License
This project was developed for academic purposes.
