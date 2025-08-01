# 🔐 JWT Authentication API with Node.js, Express & MongoDB

A production-ready boilerplate for building secure REST APIs using **JWT authentication**, **bcrypt password hashing**, and **MongoDB** with **Mongoose**. Built using **Node.js** and **Express.js** — ideal for login systems, user dashboards, and backend auth management.

> 💡 Built by [Owais Zakir](https://github.com/owaisZakir)

---

## 📦 Features

- ✅ Secure user **registration** & **login**
- ✅ Password hashing with **bcryptjs**
- ✅ **JWT token-based** authentication with expiry
- ✅ **Middleware-protected** routes
- ✅ Clean and modular folder structure
- ✅ Ready to deploy, customize, and extend

---

## 🛠 Tech Stack

- **Node.js** + **Express.js**
- **MongoDB** + **Mongoose**
- **bcryptjs**
- **jsonwebtoken**
- **dotenv**
- Tested using **Postman**

---

## 🚀 Getting Started

### 📥 Clone the repository

```bash
git clone https://github.com/OwaisZakir/auth-system-boilerplate.git
````
```bash
cd auth-system-boilerplate
````

### 📦 Install dependencies

```bash
npm install
```

### ⚙️ Setup environment variables

Create a `.env` file in root:

```env
MONGO_URI=mongodb://localhost:27017/authDemo
JWT_SECRET=your_jwt_secret_key
```

> Or copy `.env.example`:

```bash
cp .env.example .env
```

### ▶️ Start the development server

```bash
npm start
```

The server will start at: [http://localhost:5000](http://localhost:5000)

---

## 📬 API Endpoints

| Method | Endpoint             | Description            |
| ------ | -------------------- | ---------------------- |
| POST   | `/api/auth/register` | Register a new user    |
| POST   | `/api/auth/login`    | Login user + get token |
| GET    | `/api/dashboard`     | Protected route        |

### 🛡 Auth Header for Protected Route:

```http
Authorization: Bearer <your_token>
```

---

## 🧪 Test with Postman

Use the provided **Postman collection** to test endpoints.

📁 **File:** [`postman_collection.json`](./postman_collection.json)

### Steps:

1. Open Postman
2. Click `Import` > Select `postman_collection.json`
3. Register a new user
4. Login and copy the token
5. Add token in Authorization tab (Bearer)
6. Access `/api/dashboard`

---

## 📁 Folder Structure

```
jwt-auth-nodejs/
│
├── models/                # Mongoose schema
├── routes/                # Auth route handlers
├── middleware/            # JWT auth middleware
├── postman_collection.json
├── .env.example
├── .gitignore
├── server.js
└── package.json
```

---

## 📄 Example .env

```env
MONGO_URI=mongodb://localhost:27017/authDemo
JWT_SECRET=your_jwt_secret_key
```

---

## 📌 SEO Keywords

> `JWT Auth Node.js`, `Node.js Login API`, `Express Auth Boilerplate`, `Secure API with JWT`, `MongoDB JWT Authentication`, `User Auth System`, `JWT Backend`, `Node Auth Starter`, `Express Login System`, `MERN Auth Backend`

---

## 👨‍💻 Author

Made with ❤️ by **Owais Zakir**
GitHub: [@yOwaisZakir](https://github.com/owaisZakir)

