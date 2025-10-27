[![Node.js](https://img.shields.io/badge/Node.js-18.x-green?logo=node.js)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-Backend-black?logo=express)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas%20or%20Local-green?logo=mongodb)](https://mongodb.com/)
[![Mongoose](https://img.shields.io/badge/Mongoose-ODM-red?logo=mongoose)](https://mongoosejs.com/)
[![JWT](https://img.shields.io/badge/JWT-Authentication-orange?logo=jsonwebtokens)](https://jwt.io/)
[![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman)](https://www.postman.com/)
[![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)](https://www.docker.com/)
[![DockerHub](https://img.shields.io/badge/DockerHub-Images-blue?logo=docker&logoColor=white)](https://hub.docker.com/u/aryansinha1818)
[![Git](https://img.shields.io/badge/Git-Version%20Control-black?logo=git)](https://git-scm.com/)

# 🚀 ContestApp | Node.js + Express + React + MongoDB + Docker

ContestApp is a full-stack platform designed to manage and conduct online coding or quiz contests efficiently.
It offers separate modules for Admins and Users, a real-time leaderboard, and a resume-later system, ensuring a complete end-to-end contest experience.

🌟 Core Features
* 👑 Admin-Level Controls

Admins have a dedicated panel with full control over the contest system:

- 🧩 Create, Edit & Delete Contests – Define contest title, description, duration, and difficulty.
- ✍️ Add or Modify Questions – Create multiple-choice or descriptive questions.
- 📊 View Leaderboards in Real-Time – Instantly see how users are performing.
- 🧠 Manage Users – Approve participants, view submissions, and track scores.

🧑‍💻 User Functionality

For participants, ContestApp offers a smooth and fair experience:

* 🔐 JWT Authentication – Secure signup/login system.
* 🧠 Attempt Contests – Join active contests and answer questions.
* 💾 Save Progress – Automatically saves answers as you go; resume anytime.
* 📈 View Score & Rank – Users can view their score instantly after submission.
* 🏅 Leaderboard – Displays rankings, top scorers, and average time taken.
* 📜 View Past Contests – Review previous performances and answers.

  
🧠 Question Management

The platform supports flexible and intelligent question handling:

+ ✅ Multiple-Choice Questions (MCQs) with single or multiple correct options.
+ 🕹️ Randomized Question Order for fairness.
+ 🧩 Auto-Grading System for objective questions.
+ 💾 Data Schema – Designed using Mongoose with efficient indexing for speed.
+ 📊 Score Calculation Logic

- All this happens in real-time, ensuring instant leaderboard updates.

⚙️ Run Using Docker

🏗️ Build & Run All Services
```
docker-compose up --build
```

🌐 Access
Service	              URL
- Frontend	      http://localhost:5173

- Backend	        http://localhost:5050/api

- Mongo Express	  http://localhost:8081


🧱 Tech Stack
* Layer	Technologies
* Frontend	React, Vite
* Backend	Node.js, Express.js
* Database	MongoDB, Mongoose
* Authentication	JWT
* Deployment	Docker, Docker Compose
* Testing	Postman
* Tools	Git, Mongo Express

🙋‍♂️ Author

Aryan Sinha
* [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryan-sinha-877698212/)

* [![gmail](https://img.shields.io/badge/gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryan.sinha1818@gmail.com)
