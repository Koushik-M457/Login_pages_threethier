# Login Pages - Three Tier Web Application

A simple **three-tier web application** demonstrating a login and authentication flow.  
The app follows the **Presentation → Application → Data** architecture:

1. **Frontend (Presentation Layer)** – User Interface built with HTML/CSS/JavaScript or a frontend framework.
2. **Backend (Application Layer)** – Node.js/Express API handling authentication and business logic.
3. **Database (Data Layer)** – PostgreSQL database storing user credentials and related data.

---

## 🚀 Features
- User registration and login
- Password hashing for secure storage
- Session or JWT-based authentication
- Three-tier separation of concerns
- Dockerized environment for easy setup

---

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript (or React, if applicable)
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Containerization:** Docker & Docker Compose

---

## 📂 Project Structure
 3-tier_web_application/
│── backend/ # Node.js/Express server
│── database/ # PostgreSQL setup
│── frontend/ # UI files
│── docker-compose.yml
│── README.md


---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone git@github.com:Koushik-M457/Login_pages_threethier.git
cd Login_pages_threethier
```
Start with Docker Compose

  docker compose up --build
Access the application

Frontend: http://localhost:3000

Backend API: http://localhost:5000

Database: Accessible on port 5432

UI Interface :

<img width="1912" height="1003" alt="image" src="https://github.com/user-attachments/assets/f460312b-090a-4376-91aa-9a173ba78c99" />
