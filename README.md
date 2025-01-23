# Realtime ChatApp

A modern real-time chat application built using the MERN stack with a sleek and intuitive user interface. This application enables instant messaging with real-time updates, beautiful themes, and responsive design.

## Features

- **Real-time Messaging**: Powered by Socket.IO for seamless communication.
- **Theming**: Integrated with DaisyUI for dynamic and customizable themes.
- **Responsive Design**: Styled with TailwindCSS for a consistent experience across devices.
- **MERN Stack**: Built with MongoDB, Express.js, React, and Node.js.
- **Deployment**: Fully deployed on Render for production-ready access.

---

## File and Folder Structure

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

## Technologies Used

### Frontend:
- **React**: For building the user interface.
- **TailwindCSS**: For styling.
- **DaisyUI**: For pre-designed themes and UI components.

### Backend:
- **Node.js**: For server-side scripting.
- **Express.js**: For building RESTful APIs.
- **MongoDB**: For database management.
- **Socket.IO**: For real-time, bidirectional communication.

### Deployment:
- **Render**: For deploying the application in a production environment.

---

## Getting Started

Follow these steps to run the project locally.

### Prerequisites
- Node.js installed
- MongoDB installed and running locally or on a cloud service

### Clone the Repository
```bash
git clone https://github.com/your-username/realtime-chatapp.git
cd realtime-chatapp
```

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Backend Setup
```bash
cd backend
npm install
npm run dev
```

### Environment Variables
Create a `.env` file in the `backend` folder with the following variables:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SOCKET_PORT=your_socket_port
```

---

## Screenshots

### Application Screens
<div style="display: flex; flex-direction: column; gap: 20px;">

#### 1. Login Page
![Login Page](![Screenshot (248)](https://github.com/user-attachments/assets/02bea703-b2c2-419d-a18b-6276913401b3)
)

#### 2. Home Page
![Home Page](![Screenshot (249)](https://github.com/user-attachments/assets/523440d0-52bb-4454-99cb-8d0879a27a17)
)

#### 3. Theme Page
![Theme Page](![Screenshot (250)](https://github.com/user-attachments/assets/53b2bbcd-0dc8-4be7-9225-15763651d53e)
)

#### 4. Chat in Real-time
![Chat in Real-time](![Screenshot (244)](https://github.com/user-attachments/assets/bc2e398f-aa60-4629-a7c6-6c772e032345)
)

</div>

---

## Deployment
The application is deployed on Render and can be accessed at:
[Live Demo](https://your-app-url.render.com)

---

## Contributing
Feel free to submit issues or pull requests to improve the application. Contributions are always welcome!

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
