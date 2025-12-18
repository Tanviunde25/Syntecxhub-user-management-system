# Syntecxhub-user-management-system
A full-stack **User Management System** built with Node.js, Express, MongoDB, and EJS.  
This project allows you to **add, view, edit, and delete users** with a clean and aesthetic UI using Bootstrap 5.

---

## 🛠 Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB + Mongoose  
- **Frontend:** EJS Templates + Bootstrap 5  
- **Architecture:** MVC (Model-View-Controller)  
- **Authentication:** Basic authentication (admin/admin123)  

---

## 📂 Folder Structure

User-Management-System/
│
├── config/
│ └── db.js # MongoDB connection
│
├── controllers/
│ └── userController.js # CRUD logic
│
├── models/
│ └── User.js # Mongoose schema
│
├── routes/
│ └── userRoutes.js # Express routes
│
├── views/
│ ├── partials/
│ │ ├── header.ejs
│ │ └── footer.ejs
│ └── users/
│ ├── index.ejs
│ ├── add.ejs
│ └── edit.ejs
│ └── about.ejs
│ └── contact.ejs
│
├── public/
│ └── css/
│ └── style.css
│
├── app.js # Main server file
├── package.json # Node dependencies
└── README.md

yaml
Copy code

---

## 🚀 Installation & Running

1. Install Node.js and MongoDB on your machine.
2. Clone or download this project.
3. Open terminal in project folder.
4. Install dependencies:

```bash
npm install
Start MongoDB server:

bash
Copy code
mongod
Start Node.js server:

bash
Copy code
npm start
Open in browser:

arduino
Copy code
http://localhost:4000

🔐 Login Credentials
makefile
Copy code
Username: admin
Password: admin123

🎨 Features
Add, view, edit, and delete users

Clean, responsive UI using Bootstrap 5

Dashboard with multiple tabs (Users, Add User, About, Contact)

MVC folder structure for professional project

MongoDB + Mongoose database integration
