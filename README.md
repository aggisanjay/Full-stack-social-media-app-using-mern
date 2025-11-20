# 📩 Real-Time Social Media Messaging App

A **MERN Stack** based real-time Socila Media application with authentication, messaging, and live updates using **SSE (Server-Sent Events)** and **Socket-like streaming**.  
Users can send/receive messages, view profiles, and see live message updates without refreshing.

---

## 🚀 Features
- 🔐 **JWT Authentication** (Login, Register)
- 💬 **Real-time Messaging** (SSE based)
- 📷 **Image/File Attachments** in messages
- 👥 **User Connections** (friends/followers)
- 📄 **Profile View** with bio and profile picture
- 📱 **Responsive UI** with TailwindCSS
- 🌐 **REST API + Redux Toolkit** for state management

---

## 🛠 Tech Stack

### **Frontend**
- React.js (Vite or CRA)
- Redux Toolkit
- Tailwind CSS
- Lucide Icons
- Axios

### **Backend**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (file uploads)
- JWT Authentication
- SSE (Server Sent Events)

⚙️ Environment Variables

Server (.env)

PORT=5000

MONGO_URL=your_mongodb_connection_string

CLERK_PUBLISHABLE_KEY=xxxx

CLERK_SECRET_KEY=xxxx

IMAGEKIT_PUBLIC_KEY=xxxx

IMAGEKIT_PRIVATE_KEY=xxxx

IMAGEKIT_URL_ENDPOINT=xxxx

EMAIL_HOST=smtp.gmail.com

EMAIL_PORT=465

EMAIL_USER=xxxx

EMAIL_PASS=xxxx

Client (.env)

VITE_CLERK_PUBLISHABLE_KEY=xxxx

VITE_API_URL=http://localhost:5000

🖥️ Running the Project Locally

1. Install dependencies

cd server

npm install

cd ../client

npm install

2. Start the server

cd server

npm run dev

3. Start the client

cd client

npm run dev


Both apps will run independently:

Client → http://localhost:5173

Server → http://localhost:5000

## screenshots

# Login

<img width="1306" height="612" alt="image" src="https://github.com/user-attachments/assets/09ece220-c7e6-47d7-8eee-d334a83b7f0b" />

# Dashboard story 

<img width="1347" height="645" alt="image" src="https://github.com/user-attachments/assets/754dc97e-3ff3-420e-865e-6fb9be78f5b2" />

# Sender

<img width="1344" height="645" alt="image" src="https://github.com/user-attachments/assets/80f972aa-1c07-4393-a9b6-e0889442e723" />


# Reciever

<img width="1344" height="641" alt="image" src="https://github.com/user-attachments/assets/80083e78-ff9e-4b7d-bcee-29730d94da95" />




