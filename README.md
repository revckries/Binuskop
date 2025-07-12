<h1 align="center">🎬 BinusKop</h1>
<p align="center"><em>A modern digital solution for movie lovers in Indonesia</em></p>

---

## 👥 Group 5 – *Software Engineering* IT Division Project 

### Group Members:
| Student ID   | Name                      | Role          |
|--------------|---------------------------|---------------|
| 2702339961   | Nafi Irfan Zidny          | Team Leader   |
| 2602106175   | Oktavianus                | Vice Leader   |
| 2702217043   | Stanic Dylan              | Member        |
| 2702217043   | Christine Kosasih         | Member        |
| 2702274495   | Kevin Gabriel Wiharja     | Member        |

---

## 📱 About the Application

**BinusKop** is a web-based application designed to provide a modern, fast, and convenient cinema experience. This project was developed as part of the **Software Engineering** at Advanced Bootcamp IT Division Binus University.

### ✨ Main Features:
- Digital movie ticket booking
- Intuitive and responsive user interface
- Easy and secure payment & verification process
- Integrated movie schedule and database management

---

## 🛠️ Tools & Technologies

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** PostgreSQL (via Sequelize ORM)  
- **Database Management:** DBeaver  
- **Environment Management:** `.env` files  
- **Migration & Seeder:** Sequelize CLI  
- **Dev Tools:** Nodemon  

---

## 🚀 How to Run the Server

```bash
cd server
npm i
touch .env
# Then fill in the .env file with:
# SECRETKEY=RAHASIA
npx sequelize-cli db:create
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all
npx nodemon app.js
```

✅ If the following message appears:
```
Example app listening on port 3000
```
the server is running successfully.

---

## 💻 How to Run the Client (Frontend)

```bash
cd Binuskop
npm i
npm start
```

🌐 The application will run on `http://localhost:3000` by default.

---

## 📌 Important Notes

- Make sure **PostgreSQL** is installed and running on your machine.
- Optionally, you can use **DBeaver** to visualize and manage the database.
- If migration/seed errors occur, check your `config/config.json` or database connection settings.
- Default server port: `3000`

---

## 💬 Contact & Feedback

Feel free to reach out to any of the team members if you have questions or would like to discuss this project.

---

<p align="center">Made by <strong>Group 5</strong></p>
