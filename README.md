# 🎟️ BookMyShow Clone – MERN Stack Movie Ticket Booking System

This is a full-stack clone of the **BookMyShow** platform. It allows users to browse movies, book tickets, and view upcoming shows, while also providing admin features like adding movies, shows, and theatres.

---

## 🚀 Project Features

### 👥 User Side
- Browse movies and view details
- View available shows and theatres
- Book tickets for upcoming shows
- Login/Register functionality

### 🔐 Admin Side
- Add new movies, theatres, and show timings
- Manage content via admin panel
- Protected routes using `PrivateRoute`

---

## 🛠️ Tech Stack

| Layer     | Technology                     |
|-----------|--------------------------------|
| Frontend  | React.js, CSS Modules          |
| Backend   | Node.js, Express.js            |
| Database  | MongoDB (via Mongoose)         |
| Auth      | JWT for authentication         |
| API Comm. | Axios                          |

---

## 📁 Project Structure

### 🌐 Frontend (`client/`)
```bash
client/
├── public/
├── src/
│   ├── component/
│   │   ├── MovieCard.js
│   │   ├── Navbar.js
│   │   └── PrivateRoute.js
│   ├── pages/
│   │   ├── admin/
│   │   │   ├── AddMovie.js
│   │   │   ├── AddShow.js
│   │   │   └── AddTheatre.js
│   │   └── user/
│   ├── services/
│   │   └── api.js
│   ├── styles/
│   │   ├── Admin.css
│   │   ├── Cards.css
│   │   ├── Forms.css
│   │   ├── Global.css
│   │   └── Navbar.css
│   ├── utils/
│   │   └── auth.js
│   ├── App.js
│   ├── index.js
│   └── ...
