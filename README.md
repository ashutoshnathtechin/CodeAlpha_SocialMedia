
# Connect Gram 🌐

**Connect Gram** is a lightweight, fully functional social networking web application designed to bring people together. Built entirely from scratch without heavy frontend frameworks, this project demonstrates a deep understanding of core web technologies, RESTful API design, and relational database management.

## ✨ Features

* **Secure Authentication**: Complete user registration and login system with session management.
* **Interactive Feed**: A dynamic timeline where users can scroll through posts, drop a like, and leave comments in real-time.
* **Rich Media Sharing**: Seamlessly upload and share images directly from your device, handled securely on the backend.
* **Vertical Video Reels**: A dedicated Reels section featuring auto-playing, vertical-scrolling videos built using the native `Intersection Observer API` and CSS scroll-snapping.
* **Discover & Explore**: Search for other users and discover trending content on the Explore grid.
* **Real-time Notifications**: Get instantly notified when someone interacts with your content or follows your profile.

## 🛠️ Technology Stack

This application was engineered to be fast and lightweight, prioritizing vanilla web standards over bulky libraries.

* **Frontend**: HTML5, CSS3 (Modern Flexbox & CSS Grid), Vanilla JavaScript (ES6+)
* **Backend**: Node.js, Express.js
* **Database**: SQLite3 (with complex relational mapping for Users, Posts, Likes, Comments, and Notifications)
* **Storage**: Multer (for robust handling of `multipart/form-data` and media uploads)

## 🚀 How to Run Locally

To get a local copy up and running, follow these simple steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ashutoshnathtechin/CodeAlpha_SocialMedia.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd CodeAlpha_SocialMedia
   ```

3. **Install the dependencies:**
   ```bash
   npm install
   ```

4. **Start the application:**
   ```bash
   npm start
   ```

5. **Open your browser:**
   Navigate to `http://localhost:3001` to view the app.

## 💡 Technical Highlights

* **Custom SPA Routing**: Implemented custom Vanilla JS routing to create a seamless Single Page Application experience without page reloads.
* **Database Integrity**: The SQLite schema utilizes strict foreign key constraints (e.g., `ON DELETE CASCADE`) to ensure data remains consistent and orphaned records are prevented.

---
*Built with ❤️ by Ashutosh Nath*
```
