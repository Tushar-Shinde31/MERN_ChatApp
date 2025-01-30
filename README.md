# 🔥 Realtime ChatApp

A modern real-time chat application built using the **MERN stack** with a sleek and intuitive user interface. This application enables instant messaging with real-time updates, beautiful themes, and responsive design.

## ✨ Features

- 💬 **Real-time Messaging**: Powered by Socket.IO for seamless communication.  
- 🎨 **Theming**: Integrated with DaisyUI for dynamic and customizable themes.  
- 📱 **Responsive Design**: Styled with TailwindCSS for a consistent experience across devices.  
- 🖥️ **MERN Stack**: Built with MongoDB, Express.js, React, and Node.js.  
- 🚀 **Deployment**: Fully deployed on Render for production-ready access.  

---

## 📸 Screenshots

### Application Screens
<div style="display: flex; flex-direction: column; gap: 20px;">

#### 1. 🔑 Login Page
![Screenshot (248)](https://github.com/user-attachments/assets/d00b061c-f40f-4d98-88ad-4f51da7d0dc1)

#### 2. 🏠 Home Page
![Screenshot (249)](https://github.com/user-attachments/assets/682e75ff-3145-4be7-99e4-d9d4ad64bb8d)

#### 3. 🎨 Theme Page
![Screenshot (250)](https://github.com/user-attachments/assets/7f2054eb-ca5f-44fd-a17f-12eeec39b61b)

#### 4. 💬 Chat in Real-time
![Screenshot (244)](https://github.com/user-attachments/assets/998b8369-e8b1-4b61-b253-afb32b2866e3)

</div>

---

## 🗂️ File and Folder Structure

```
.
├── frontend               # React application (client-side)
│   ├── public            # Static files
│   ├── src               # Source code
│       ├── components    # Reusable React components
│       ├── pages         # Application pages
│       ├── styles        # TailwindCSS and DaisyUI customizations
│       └── App.js        # Main React component
│   └── package.json      # Frontend dependencies
├── backend                # Node.js application (server-side)
│   ├── config            # Configuration files (e.g., database connection)
│   ├── controllers       # API endpoint logic
│   ├── models            # MongoDB schemas
│   ├── routes            # API routes
│   ├── server.js         # Main server file
│   └── package.json      # Backend dependencies
├── README.md              # Project documentation
└── .gitignore             # Ignored files and folders
```

---

## 🛠️ Technologies Used

### 🌐 Frontend:
- ⚛️ **React**: For building the user interface.  
- 🎨 **TailwindCSS**: For styling.  
- 🌈 **DaisyUI**: For pre-designed themes and UI components.  

### 🔧 Backend:
- 🟢 **Node.js**: For server-side scripting.  
- 🌐 **Express.js**: For building RESTful APIs.  
- 🍃 **MongoDB**: For database management.  
- 🔄 **Socket.IO**: For real-time, bidirectional communication.  

### 🚀 Deployment:
- 🌍 **Render**: For deploying the application in a production environment.  

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### ✅ Prerequisites
- 🛠️ Node.js installed
- 🍃 MongoDB installed and running locally or on a cloud service

### 📥 Clone the Repository
```bash
git clone https://github.com/your-username/realtime-chatapp.git
cd realtime-chatapp
```

### 🖥️ Frontend Setup
```bash
cd frontend
npm install
npm start
```

### 🔧 Backend Setup
```bash
cd backend
npm install
npm run dev
```

### 🛠️ Environment Variables
Create a `.env` file in the `backend` folder with the following variables:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SOCKET_PORT=your_socket_port
```

---

## 🌍 Deployment
The application is deployed on Render and can be accessed at:
[Live Demo](https://mern-chatapp-25j8.onrender.com/)

---

## 🤝 Contributing
Feel free to submit issues or pull requests to improve the application. Contributions are always welcome!

---

## Author 👨‍💻
Developed by **[Tushar Shinde](https://github.com/Tushar-Shinde31)**. Connect with me on [LinkedIn](https://www.linkedin.com/in/tushar-shinde-262335257/).

