# Event-Finder-App

**Event Finder** is a full-stack web application that allows users to discover, create, and manage events.

---

## ✨ Features

- ✅ User authentication (register, login, logout)
- 🔍 Browse events by categories
- 🔎 Search and filter events
- 📄 View event details
- 📝 Create, edit, and delete events
- 📷 Image upload for events
- 📈 Trending and recommended events

---

## 🛠️ Technology Stack

### Frontend
- React
- React Router
- Axios for API requests
- Context API for state management
- Custom CSS for styling

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JSON Web Tokens (JWT) for authentication
- bcrypt for password hashing

---

<pre> ## 📁 Project Structure ``` event-finder/ # Frontend React application ├── public/ ├── src/ │ ├── components/ # Reusable UI components │ ├── context/ # Context providers │ ├── pages/ # Page components │ ├── services/ # API service functions │ ├── styles/ # CSS files │ ├── utils/ # Utility functions │ └── App.js # Main application component ├── package.json server-side/ # Backend Node.js application ├── controllers/ # Request handlers ├── middleware/ # Custom middleware ├── models/ # MongoDB schemas ├── routes/ # API route definitions └── server.js # Entry point ``` </pre>
---

## ⚙️ Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB

### Installation

```bash
# Clone the repository
git clone https://github.com/SimranS2857/Event-Finder-App.git
cd Event-Finder-App

# Install backend dependencies
cd server-side
npm install

# Install frontend dependencies
cd ../event-finder
npm install


