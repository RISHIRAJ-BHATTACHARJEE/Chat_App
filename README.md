
## 📋 <a name="table">Table of Contents</a>

  

1. 🤖 [Introduction](#introduction)

2. ⚙️ [Tech Stack](#tech-stack)

3. 🔋 [Features](#features)

4. 🤸 [Quick Start](#quick-start)

  

## <a name="introduction">🤖 Introduction</a>

  

Built with the latest MERN Stack, this project is a Real Time Chat Application. It enables users to securely register, log in, and chat in real time with the other users.

  

## <a name="tech-stack">⚙️ Tech Stack</a>

  

- React.js

- Node.js

- Socket.io

- JWT

- MongoDB

- Tailwind CSS

  

## <a name="features">🔋 Features</a>

  
  

👉 **Authentication**: Implements authentication and authorization features using JWT, allowing users to securely log in and chat in real time.

  

👉 **Messaging**: Real-time messaging with Socket.io

  

👉 **Online Status**: Online user status (Socket.io and React Context)

  

👉 **State Management**: Proper state management using Redux Toolkit.

  

👉 **Error Handling**: Error handling both on the server and on the client.

  
  

## <a name="quick-start">🤸 Quick Start</a>

  

Follow these steps to set up the project locally on your machine.

  

**Prerequisites**

  

Make sure you have the following installed on your machine:

  

- [Git](https://git-scm.com/)

- [Node.js](https://nodejs.org/en)

- [npm](https://www.npmjs.com/) (Node Package Manager)

  

**Cloning the Repository**

  

```bash
git  clone  https://github.com/RISHIRAJ-BHATTACHARJEE/Chat_App.git
cd  Chat_App
```

  

**Installation**

  

Install the project dependencies using npm:

  

```bash
cd  backend
npm  install
```

  

```bash
cd  frontend
npm  install
```

  

**Set Up Environment Variables**

  

Create a new file named `.env` in the root of your project and add the following content:

  

```env
PORT =

MONGO_URI =

JWT_SECRET_KEY =
```

  

Replace the placeholder values with your actual MongoDB URL & JWT Secret.

  

**Running the Project**

  

```bash
cd  frontend
npm  run  start
```

  

```bash
cd  backend
npm  run  dev
```

  

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.