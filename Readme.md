# 💪 Gym Management System Website

This is a responsive web-based Gym Management System developed using **HTML, CSS, JavaScript**, and **Firebase**. The system is designed to streamline gym operations with modules for **Admin**, **Members**, and **Users**, offering functionality like member registration, billing, supplement management, diet charts, notifications, and more.

## 🌐 Live Demo
> [Coming Soon – Deploy via GitHub Pages, Netlify, or Firebase Hosting]

---

## 📌 Features

### 🔐 Authentication
- Login and Signup functionality for Admin, Members, and Users.
- Firebase Authentication integration.

### 🧑‍💼 Admin Module
- Manage gym members (add, update, delete).
- View payments and generate digital receipts.
- Send notifications to members.
- Manage supplement inventory.
- Add/Update diet plans.
- Access reports (member reports, billing, etc.).

### 🧍 Member Module
- View assigned workouts.
- Track diet plans.
- Receive notifications.
- View and download billing history.
- Update profile.

### 👤 User Module (Visitors)
- View homepage with gym introduction.
- Explore exercise plans and diet details.
- Contact gym via “Contact Us” form.
- Sign up to join the gym.

---

## 🖼️ Pages Included

- `index.html` - Home page
- `login.html` - Login page
- `signup.html` - Registration page
- `about.html` - About the gym
- `contact.html` - Contact form
- `billing.html` - Billing and receipt page
- `exercise.html` - Workout plans with images
- `diet.html` - Diet charts and plans
- `admin.html` - Admin dashboard
- `member.html` - Member dashboard

---

## 🧰 Tech Stack

| Technology | Use |
|------------|-----|
| **HTML5**  | Structure and markup |
| **CSS3**   | Styling and responsiveness |
| **JavaScript** | Client-side interaction and logic |
| **Firebase** | Authentication, Real-time Database, Hosting |
| **Tailwind CSS** (optional) | Utility-first styling (if used) |

---

## 🔒 Firebase Configuration

Make sure to add your Firebase project configuration in a separate JS file or script block:

```javascript
// firebase-config.js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
firebase.initializeApp(firebaseConfig);



🚀 Deployment
You can deploy the project using:
    Firebase Hosting
    GitHub Pages
    Netlify


🙋‍♂️ Developer
    Name: [Dhanish kumar]
    Course: B.Tech (Computer Science)
    Institution: [Galgotias University]


📃 License
    This project is licensed for educational use only.