<div align="center">

# 🏨 Haven Chain of Hotels

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=4A90E2&center=true&vCenter=true&width=600&lines=Welcome+to+Haven+Hotels;Your+Perfect+Stay+Awaits;BEE+Project+2024-25" alt="Typing SVG" />

![Haven Hotels Banner](https://img.shields.io/badge/Haven-Chain%20of%20Hotels-4A90E2?style=for-the-badge&logo=building&logoColor=white&labelColor=2C3E50)

### 🌟 *A comprehensive hotel-chain website & backend for "Haven", implementing authentication, destinations, dashboard, and booking management.*

---

<div style="display: flex; justify-content: center; align-items: center; gap: 10px; flex-wrap: wrap; margin: 20px 0;">

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io/)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)](https://mongoosejs.com/)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

</div>

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎨 **Frontend Features**
- 🏨 **Multi-page Website** - Home, About, Destinations & More
- 📱 **Responsive Design** - Perfect on all devices
- 🎭 **Interactive UI** - Smooth animations & transitions
- 🌍 **Rich Media Gallery** - Stunning hotel showcases
- 🎨 **Modern Styling** - Contemporary CSS3 designs

</td>
<td width="50%">

### ⚙️ **Backend Features**
- 🔐 **JWT Authentication** - Secure token-based auth
- 🗄️ **MongoDB Integration** - Robust data persistence
- 📊 **User Dashboard** - Personalized booking management
- 🛡️ **Password Security** - bcrypt hashing protection
- 🔌 **RESTful APIs** - Clean and organized endpoints

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### 🎨 Frontend Technologies
<div style="display: flex; justify-content: center; gap: 20px; margin: 20px 0;">

| Technology | Description | Version |
|------------|-------------|---------|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Structure & Semantic Markup | HTML5 |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling & Responsive Design | CSS3 |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Interactive Client-Side Logic | ES6+ |

</div>

### ⚙️ Backend Technologies
<div style="display: flex; justify-content: center; gap: 20px; margin: 20px 0;">

| Technology | Description | Version |
|------------|-------------|---------|
| ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) | Server Runtime Environment | v16+ |
| ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) | Web Application Framework | v4.18+ |
| ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | NoSQL Database | v5.0+ |
| ![Mongoose](https://img.shields.io/badge/-Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white) | MongoDB Object Modeling | v6.0+ |

</div>

### 🔒 Security & Authentication
<div style="display: flex; justify-content: center; gap: 20px; margin: 20px 0;">

| Technology | Description | Purpose |
|------------|-------------|---------|
| ![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) | JSON Web Tokens | Secure Authentication |
| ![bcrypt](https://img.shields.io/badge/-bcrypt-338033?style=flat-square&logo=security&logoColor=white) | Password Hashing | Data Protection |

</div>

</div>

---

## 📂 Project Architecture

```
Haven-Chain-of-Hotels/
├── public/
│   ├── css/
│   │   ├── Homepage.css
│   │   ├── about_us.css
│   │   ├── loginpage.css
│   │   └── destinations.css
│   ├── images/
│   │   ├── hotel1.jpg
│   │   ├── hotel2.jpg
│   │   └── ...
│   └── videos/
│       └── video1.mp4
├── views/
│   ├── index.html
│   ├── about_us.html
│   ├── destinations.html
│   ├── login.html
│   ├── dashboard.html
│   └── comingsoon.html
├── routes/
│   ├── auth.js
│   ├── bookings.js
│   └── users.js
├── models/
│   ├── User.js
│   ├── Booking.js
│   └── Hotel.js
├── config/
│   └── database.js
├── server.js
├── package.json
├── .env
└── favicon.ico
```

---

## 🚀 Quick Start Guide

<div align="center">

### 📋 Prerequisites

<table>
<tr>
<td align="center" width="33%">
<img src="https://nodejs.org/static/images/logo.svg" width="60px" height="60px">
<br>
<strong>Node.js</strong>
<br>
<sub>v16+ Required</sub>
</td>
<td align="center" width="33%">
<img src="https://www.mongodb.com/assets/images/global/favicon.ico" width="60px" height="60px">
<br>
<strong>MongoDB</strong>
<br>
<sub>Local or Atlas</sub>
</td>
<td align="center" width="33%">
<svg width="60px" height="60px" viewBox="0 0 780 250" aria-hidden="true"><path fill="#231F20" stroke-width="5" stroke="#f7f7f7" d="M240,250h100v-50h100V0H240V250z M340,50h50v100h-50V50z M480,0v200h100V50h50v150h50V50h50v150h50V0H480z M0,200h100V50h50v150h50V0H0V200z"></path></svg>
<br>
<strong>npm</strong>
<br>
<sub>Package Manager</sub>
</td>
</tr>
</table>

</div>

### 📥 Installation Steps

<details>
<summary><strong>🔽 Click to expand installation guide</strong></summary>

<br>

**1. 📥 Clone the Repository**
```bash
git clone https://github.com/Spydiecy/Haven-Chain-of-Hotels.git
cd Haven-Chain-of-Hotels
```

**2. 📦 Install Dependencies**
```bash
npm install
# This will install all required packages including:
# express, mongoose, jsonwebtoken, bcrypt, etc.
```

**3. ⚙️ Environment Configuration**
Create a `.env` file in the root directory:
```env
# Server Configuration
PORT=3000
NODE_ENV=development

# Database Configuration
MONGODB_URI=mongodb://localhost:27017/haven_hotels
# Or use MongoDB Atlas:
# MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/haven_hotels

# Security
JWT_SECRET=your_super_secret_jwt_key_here
JWT_EXPIRES_IN=7d

# Optional: Email Configuration (for future features)
EMAIL_SERVICE=gmail
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
```

**4. 🗄️ Database Setup**
```bash
# Make sure MongoDB is running locally, or
# Configure MongoDB Atlas connection in .env file
```

**5. 🚀 Launch the Application**
```bash
# Development mode
npm run dev

# Production mode
npm start

# Or directly
node server.js
```

**6. 🌐 Access the Application**
Open your browser and navigate to:
```
http://localhost:3000
```

</details>

---

## 🎯 Usage Guide

<div align="center">

<table>
<tr>
<td width="50%">

### 👥 **For End Users**

🏠 **Home Page**
- Welcome interface with hotel overview
- Featured destinations showcase
- Quick navigation to all sections

🔑 **Authentication System**
- Secure user registration
- Login with email/password
- JWT-based session management

🌍 **Destinations Explorer**
- Browse premium hotel locations
- Rich media galleries
- Detailed location information

📊 **Personal Dashboard**
- View booking history
- Manage current reservations
- Update profile information

</td>
<td width="50%">

### 👨‍💻 **For Developers**

🗄️ **Database Operations**
- User data stored in MongoDB
- Booking management system
- Secure data relationships

🔐 **Authentication Flow**
- JWT token generation
- Protected route middleware
- Password hashing with bcrypt

🛣️ **API Endpoints**
- RESTful API design
- JSON response format
- Error handling middleware

🏗️ **Code Structure**
- Modular architecture
- Clean separation of concerns
- Easy to extend and maintain

</td>
</tr>
</table>

</div>



---

## 👥 Meet Our Team

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=4A90E2&center=true&vCenter=true&width=400&lines=The+Minds+Behind+Haven;Building+Dreams+Together" alt="Team Intro" />

<br><br>

<table>
<tr>
<td align="center" width="300px">
<img src="https://github.com/Spydiecy.png" width="120px" style="border-radius: 50%; border: 4px solid #4A90E2; box-shadow: 0 8px 16px rgba(0,0,0,0.2);">
<br><br>
<strong style="font-size: 20px; color: #2C3E50;">Spydiecy</strong>
<br><br>
<a href="https://github.com/Spydiecy">
<img src="https://img.shields.io/badge/-Follow%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<br><br>
<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 8px 16px; border-radius: 20px; color: white; font-weight: bold; display: inline-block;">
🚀 Lead Developer
</div>
</td>

<td align="center" width="300px">
<img src="https://github.com/KrishnaSaxena108.png" width="120px" style="border-radius: 50%; border: 4px solid #47A248; box-shadow: 0 8px 16px rgba(0,0,0,0.2);">
<br><br>
<strong style="font-size: 20px; color: #2C3E50;">Krishna Saxena</strong>
<br><br>
<a href="https://github.com/KrishnaSaxena108">
<img src="https://img.shields.io/badge/-Follow%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<br><br>
<div style="background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); padding: 8px 16px; border-radius: 20px; color: white; font-weight: bold; display: inline-block;">
💻 Full Stack Developer
</div>
</td>

<td align="center" width="300px">
<img src="https://github.com/JollyAnsh.png" width="120px" style="border-radius: 50%; border: 4px solid #F7931E; box-shadow: 0 8px 16px rgba(0,0,0,0.2);">
<br><br>
<strong style="font-size: 20px; color: #2C3E50;">Jolly Ansh</strong>
<br><br>
<a href="https://github.com/JollyAnsh">
<img src="https://img.shields.io/badge/-Follow%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>
<br><br>
<div style="background: linear-gradient(135deg, #ff6b6b 0%, #ffa726 100%); padding: 8px 16px; border-radius: 20px; color: white; font-weight: bold; display: inline-block;">
🎨 Frontend Developer
</div>
</td>
</tr>
</table>

<br><br>

### 🌟 Our Expertise

<div style="display: flex; justify-content: center; align-items: center; gap: 20px; margin: 30px 0;">

<table style="border: none;">
<tr>
<td align="center" style="border: none; padding: 20px;">
<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 20px; border-radius: 15px; color: white; width: 200px;">
<div style="font-size: 30px; margin-bottom: 10px;">🚀</div>
<strong>Spydiecy</strong>
<br>
<small>Backend Architecture<br>Database Design<br>API Development</small>
</div>
</td>

<td align="center" style="border: none; padding: 20px;">
<div style="background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); padding: 20px; border-radius: 15px; color: white; width: 200px;">
<div style="font-size: 30px; margin-bottom: 10px;">💻</div>
<strong>Krishna Saxena</strong>
<br>
<small>Full Stack Development<br>MongoDB Integration<br>Authentication Systems</small>
</div>
</td>

<td align="center" style="border: none; padding: 20px;">
<div style="background: linear-gradient(135deg, #ff6b6b 0%, #ffa726 100%); padding: 20px; border-radius: 15px; color: white; width: 200px;">
<div style="font-size: 30px; margin-bottom: 10px;">🎨</div>
<strong>Jolly Ansh</strong>
<br>
<small>UI/UX Design<br>Frontend Development<br>Responsive Design</small>
</div>
</td>
</tr>
</table>

</div>

<br>

### 🤝 Team Stats

<div align="center">

![Team Collaboration](https://img.shields.io/badge/Team-Collaboration-success?style=for-the-badge&logo=team&logoColor=white)
![Code Reviews](https://img.shields.io/badge/Code-Reviews-blue?style=for-the-badge&logo=github&logoColor=white)
![Commits](https://img.shields.io/badge/Total-Commits-orange?style=for-the-badge&logo=git&logoColor=white)

</div>

</div>

---

## 🤝 Contributing

<div align="center">

We welcome contributions from the community! 

<img src="https://contrib.rocks/image?repo=spydiecy/haven-chain-of-hotels" />

### 📝 How to Contribute

</div>

<details>
<summary><strong>🔽 Contributing Guidelines</strong></summary>

<br>

**1. 🍴 Fork the Repository**
```bash
# Click the Fork button on GitHub
```

**2. 🌿 Create Feature Branch**
```bash
git checkout -b feature/amazing-feature
```

**3. 💡 Make Your Changes**
- Follow the existing code style
- Add comments for complex logic
- Test your changes locally

**4. 📝 Commit Your Work**
```bash
git add .
git commit -m "✨ Add amazing feature"
```

**5. 🚀 Push and Create PR**
```bash
git push origin feature/amazing-feature
```

**6. 🎉 Submit Pull Request**
- Provide a clear description
- Link any related issues
- Wait for code review

</details>

<div align="center">

### 🏷️ Contribution Types

![Bug Fix](https://img.shields.io/badge/🐛-Bug%20Fix-red?style=flat-square)
![Feature](https://img.shields.io/badge/✨-New%20Feature-green?style=flat-square)
![Enhancement](https://img.shields.io/badge/⚡-Enhancement-yellow?style=flat-square)

</div>

---

<div align="center">

## 🎉 Thank You!

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=4A90E2&center=true&vCenter=true&width=500&lines=Thanks+for+visiting!;Star+⭐+if+you+like+it!;Happy+Coding!+🚀" alt="Typing SVG" />

### 💖 *Built with Love for BEE Project 2024-25*

<sub>© 2024 Haven Chain of Hotels Team. This project is part of an academic assignment.</sub>

</div>
