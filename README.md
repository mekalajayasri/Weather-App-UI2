
# 🌦️ Weather App with Authentication & Interactive Map

A full-stack web application that allows users to **sign up**, **log in**, and **fetch weather information** for any city or clicked location on a map. Built with **Node.js**, **Express**, **MongoDB**, and **Leaflet.js**.

---

## 📁 Project Structure

```
project-root/
│
├── backend/
│   ├── server.js
│   ├── .env
│   └── models/User.js
│
├── frontend/
│   ├── signup.html
│   ├── login.html
│   ├── app.html
│   ├── script.js
│   └── style.css
│
└── README.md
```

---

## 🚀 Features

- 🔐 **User Authentication** with JWT
- 🧾 **Registration & Login**
- 📍 **Weather Search by City or Map Click**
- 🗺️ **Interactive Map** using Leaflet.js
- ☀️ **Live Weather Data** from OpenWeatherMap API
- 🎨 Clean and responsive UI

---

## 🔧 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
```

### 2. Backend Setup

#### 📁 Navigate to Backend

```bash
cd backend
```

#### 📦 Install Dependencies

```bash
npm install
```

#### ⚙️ Create `.env` File

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017
JWT_SECRET=your-secret-key
WEATHER_API_KEY=your-openweathermap-api-key
```

> Replace the values with your credentials.

#### ▶️ Start the Server

```bash
node server.js
```

Your server should now run on `http://localhost:5000`.

---

### 3. Frontend Setup

Make sure your frontend files (`signup.html`, `login.html`, `app.html`, `script.js`, `style.css`) are located inside a folder named `frontend/` one level above `server.js`. The server statically serves this directory.

```
project-root/
├── backend/
│   └── server.js
└── frontend/
    ├── app.html
    ├── login.html
    ├── signup.html
    ├── script.js
    └── style.css
```

No need to run a separate server for the frontend — just open `http://localhost:5000` in your browser to access the app.

---

## 📸 Screenshots

- **Login Page**
- **Signup Page**
- **Weather Dashboard with Map**

*(Add screenshots here if needed)*

---

## 🛠️ Technologies Used

**Frontend:**
- HTML/CSS/JS
- Leaflet.js for Maps
- OpenWeatherMap API

**Backend:**
- Node.js + Express
- MongoDB + Mongoose
- bcrypt.js for password hashing
- jsonwebtoken (JWT) for authentication

---

## 📌 TODO / Enhancements

- 🌐 Add internationalization support
- 📲 Make it PWA for mobile use
- 📍 Use Geolocation API to fetch user's location on load
- 🔄 Add refresh token & persistent login

---

## 🤝 Contributing

Feel free to fork and submit PRs!

---

## 📝 License

MIT
