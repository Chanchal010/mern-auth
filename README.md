
# MERN Authentication

A full-stack MERN (MongoDB, Express, React, Node.js) application with authentication features.

## Features

- User registration and login
- JWT-based authentication
- Protected routes
- Password hashing with bcryptjs
- Persistent login with refresh tokens

## Prerequisites

Ensure you have the following installed on your local development machine:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- npm (Node Package Manager) or yarn

## Installation

1. Clone the repository:
```
git clone https://github.com/Chanchal010/mern-auth.git
```
3. Navigate to the project directory:
```
cd mern-auth
```
3. Install server dependencies:
```
cd mern-auth
```
```
npm install
```
```
yarn install
```
4. Install client dependencies:
```
cd client
```
```
npm install
```
```
yarn install
```
## Configuration

1. Create a `.env` file in the `root` directory named `mern-auth` and add the following environment variables:

```env
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
PORT=<your-listening-server-port>
```

## Running the Application

1. Start the backend server:

```
cd mern-auth
npm run dev
```

2. Start the frontend development server:

```
cd client
npm run dev
```

The application running on `https://mern-authentication-qk7b.onrender.com`.

## Project Structure

```
mern-auth
│──  api/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── App.js
│   │   ├── firebase.js
│   │   └── index.css
│   │   ├── main.jsx
│   └── package.json
│
├── README.md
├── index.html
└── .gitignore
└── package.json
```

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature-name`)
5. Create a new Pull Request


## Contact
Chanchal Bag - [Chanchal010](https://github.com/Chanchal010)

E-mail - [chanchalbag112@gmail.com](chanchalbag112@gmail.com)

LinkedIn - [https://www.linkedin.com/in/chanchal-bag-010c](https://www.linkedin.com/in/chanchal-bag-010c)

Project Link - [https://github.com/Chanchal010/mern-auth](https://github.com/Chanchal010/mern-auth)

visit App - [Auth App](https://mern-authentication-qk7b.onrender.com)

## License

This project is licensed under the MIT License.

---
