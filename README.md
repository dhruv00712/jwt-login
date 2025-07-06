#  JWT Auth API with Express

This is a simple Node.js API using Express that demonstrates **user login** and **JWT-based authentication**.
It features a login route that returns a JSON Web Token (JWT) and a protected route accessible only with a valid token.

---

##  Tech Stack

- Node.js
- Express
- JSON Web Token (JWT)
- Body Parser
- dotenv
- nodemon

---

##  Project Structure
.
├── server.js
├── .env
├── package.json
└── README.md



---

## ⚙️ Setup Instructions

###  Clone the repository

```
git clone https://github.com/dhruv00712/jwt-login.git
cd jwt-login

npm install
```

 Create a .env file
Create a .env file in the root of your project and add:
PORT=3000
JWT_SECRET=your_jwt_secret_key



Run the App---
  install npx nodemon server.js

bash-
nodemon server.js





