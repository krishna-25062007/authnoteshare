# NoteShare 📚

A MERN-stack web application for sharing study notes, interacting with other users, and communicating through real-time chat.

## ✨ Features

- 🔐 **Authentication:** User registration and login.
- 📝 **Note Sharing:** Share notes with titles, descriptions, and resource links.
- ❤️ **Likes & Comments:** Interact with notes shared by the community.
- 👤 **User Profiles:** Manage personal notes and view activity.
- 🔎 **Search Notes:** Find relevant study materials.
- 💬 **Real-Time Chat:** Communicate with other users through one-to-one messaging.
- ✏️ **Note Management:** Edit and delete your own notes.

## 🛠️ Tech Stack

- **Frontend:** React.js, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Real-Time Communication:** WebSockets

## 📸 Screenshots

### Home Page
![Home Page](https://github.com/ankitkr437/NoteSharing/blob/main/frontend/public/image/home.png)

### User Profile
![User Profile](https://github.com/ankitkr437/NoteSharing/blob/main/frontend/public/image/userprofile.png)

### Upload Notes
![Upload Notes](https://github.com/ankitkr437/NoteSharing/blob/main/frontend/public/image/uploadform.png)

### Chat
![Chat](https://github.com/ankitkr437/NoteSharing/blob/main/frontend/public/image/chat.png)

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- MongoDB local instance or MongoDB Atlas
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/krishna-25062007/authnoteshare.git
cd authnoteshare
```

### 2. Install Dependencies

Install dependencies separately for the frontend, backend, and socket server.

```bash
cd frontend
npm install

cd ../backend
npm install

cd ../socket
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the backend directory and configure your MongoDB connection string and other required environment variables.

Update the frontend API URL in `frontend/src/requestMethods.js` to point to your local backend.

Update the socket endpoint in `frontend/src/pages/messenger/messenger.jsx` to point to your local socket server.

**Important:** Never upload `.env` files, database credentials, or secret keys to GitHub.

### 4. Run the Application

Open three separate terminals from the project root.

**Terminal 1 — Backend**

```bash
cd backend
npm start
```

**Terminal 2 — Socket Server**

```bash
cd socket
npm start
```

**Terminal 3 — Frontend**

```bash
cd frontend
npm start
```

Open the application in your browser:

[http://localhost:3000](http://localhost:3000)
