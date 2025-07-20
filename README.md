# VIBB - MERN Chat Application with Socket.io

VIBB is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and Socket.io. It allows users to communicate in real-time with features such as instant messaging, user authentication, and chat history persistence.

## Features

- 🔒 User Authentication (Register/Login)
- 💬 Real-time Messaging with Socket.io
- 📨 Private Messaging
- ✅ Online User Indicators
- 📜 Chat History Persistence
- ⚙️ Scalable Architecture for Future Additions

## Tech Stack

### Frontend

- React.js
- Tailwind CSS
- Axios
- Socket.io-client

### Backend

- Node.js
- Express.js
- MongoDB with Mongoose
- Socket.io
- JWT (JSON Web Token) for Authentication

## Getting Started

### Installation

```bash
# Clone the repository
$ git clone https://github.com/YashInTech/vibb.git
$ cd vibb

# Install server dependencies
$ cd server
$ npm install

# Install client dependencies
$ cd ../client
$ npm install
```

### Running the Application

```bash
# Start backend
$ cd server
$ npm run dev

# Start frontend
$ cd ../client
$ npm run dev
```

### Scripts

#### Server

- `npm run dev` - Start server in development mode

#### Client

- `npm run dev` - Start Vite-React development server

## Folder Structure

```
vibb/
├── client/              # React Frontend
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── context/
│       ├── lib/
│       ├── pages/
│       ├── App.jsx
│       ├── index.css
│       └── main.jsx
├── server/              # Node/Express Backend
│   ├── controllers/
│   ├── lib/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).

---

Created with ❤️ by Yash Choudhary
