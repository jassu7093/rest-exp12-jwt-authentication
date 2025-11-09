# 🧪 REST API Experiment 12 — Secure Routes using JWT Authentication

## 📘 Objective
To secure API endpoints using **JSON Web Token (JWT)** authentication, allowing only logged-in users to access protected routes.

---

## 🧠 Learning Outcomes
- Generate JWT tokens during login.  
- Protect routes using middleware.  
- Verify tokens and restrict access to authorized users.  
- Understand stateless authentication in REST APIs.

---

## ⚙️ Tools & Technologies
- **Node.js**
- **Express.js**
- **MongoDB / Mongoose**
- **bcrypt**
- **jsonwebtoken**
- **dotenv**
- **Postman**

---

## 🏗️ Folder Structure
rest-exp12-jwt-authentication/
│
├── server.js
├── models/
│ └── User.js
├── routes/
│ ├── authRoutes.js
│ └── protectedRoutes.js
├── middleware/
│ └── authMiddleware.js
├── .env
├── .env.example
├── package.json
└── README.md


---

## 🚀 Setup Instructions
```bash
# Step 1: Initialize project
npm init -y

# Step 2: Install dependencies
npm install express mongoose bcrypt jsonwebtoken dotenv

# Step 3: Create folders
mkdir models routes middleware
touch server.js models/User.js routes/authRoutes.js routes/protectedRoutes.js middleware/authMiddleware.js .env .env.example

# Step 4: Run the server
node server.js
```
## output
<img width="1067" height="638" alt="rest_12 (1)" src="https://github.com/user-attachments/assets/647b3e47-40e6-4b99-9ed4-b392cea93f19" />
<img width="1070" height="787" alt="rest_12 (3)" src="https://github.com/user-attachments/assets/ca822585-2ce0-41c6-82c1-aec00a153ec9" />
#<img width="1067" height="764" alt="rest_12 (2)" src="https://github.com/user-attachments/assets/d4664d65-01fb-4a86-ab90-c4fb40f5e946" />



