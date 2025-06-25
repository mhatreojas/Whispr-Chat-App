# Whispr 💬

A modern, real-time chat application built with the MERN stack that enables seamless communication between users with secure authentication and responsive design.

![Whispr Banner](https://via.placeholder.com/800x200/4F46E5/FFFFFF?text=Whispr+Chat+App)

## 🚀 Features

- **User Authentication**: Secure sign up and sign in with JWT-based authentication
- **Real-time Messaging**: Instant messaging powered by Socket.IO
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Modern UI**: Clean and intuitive interface built with Tailwind CSS and Daisy UI
- **Secure**: Protected routes and encrypted user sessions
- **Fast Development**: Built with Vite for lightning-fast development experience

## 🛠️ Tech Stack

**Frontend:**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![DaisyUI](https://img.shields.io/badge/daisyui-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)

**Backend:**
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

**Deployment:**
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local installation or MongoDB Atlas account)
- Git

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mhatreojas/Whispr.git
   cd Whispr
   ```

2. **Install client dependencies:**
   ```bash
   cd client
   npm install
   ```

3. **Install server dependencies:**
   ```bash
   cd ../server
   npm install
   ```

4. **Environment Setup:**
   
   Create a `.env` file in the server directory with the following variables:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   NODE_ENV=development
   ```

## 🚀 Usage

1. **Start the server:**
   ```bash
   cd server
   npm run dev
   ```

2. **Start the client (in a new terminal):**
   ```bash
   cd client
   npm run dev
   ```

3. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`



## 🌟 Key Features Explained

### Authentication
- Secure user registration and login
- JWT-based session management
- Protected routes for authenticated users only

### Real-time Communication
- Instant message delivery using Socket.IO
- Live user status indicators
- Seamless connection handling

### User Interface
- Modern, clean design with Daisy UI components
- Fully responsive layout
- Dark/light mode support (if implemented)

## 🚀 Deployment

The application is deployed on Render. To deploy your own instance:

1. Fork this repository
2. Connect your Render account to your GitHub
3. Create a new web service for both client and server
4. Set up environment variables in Render dashboard
5. Deploy!

## 🔮 Future Enhancements

- **User Profiles**: Customizable avatars and status messages
- **Group Chats**: Multi-user chat rooms and channels
- **File Sharing**: Image and document sharing capabilities
- **Push Notifications**: Real-time notifications for new messages
- **Message Features**: 
  - Emoji reactions and custom emojis
  - Message editing and deletion
  - Read receipts
  - Message search functionality
- **Advanced Features**:
  - Voice messages
  - Video calling integration
  - Message encryption
  - Typing indicators

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Ojas Mhatre**
- GitHub: [@mhatreojas](https://github.com/mhatreojas)

## 🙏 Acknowledgments

- Thanks to the open-source community for the amazing tools and libraries
- Inspired by modern chat applications like Discord and Slack
- Built with love and lots of coffee ☕

## 📞 Support

If you have any questions or run into issues, please open an issue on GitHub or reach out to the maintainer.

---

⭐ **Star this repository if you found it helpful!**