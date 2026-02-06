# 🌍 Wanderlust – Travel Listing Web Application

Wanderlust is a full-stack travel listing web application that allows users to explore, create, and manage unique travel destinations. It provides an interactive platform where travelers can discover places, view details, and share their own experiences.

Built with modern web technologies, Wanderlust focuses on clean UI, secure authentication, and seamless user experience.

# ✨ Features

🔐 User Authentication – Secure signup, login, and logout functionality.

🏡 Create & Manage Listings – Users can add, edit, and delete travel destinations.

🖼️ Image Upload – Upload destination images for better visualization.

📍 Interactive Maps – View listing locations with map integration.

💬 Reviews & Ratings – Users can share feedback and rate destinations.

# 🛠️ Tech Stack

## Frontend:

HTML

CSS

Bootstrap

JavaScript

EJS

## Backend:

Node.js

Express.js

Database:

MongoDB

## Other Tools & Services:

Cloudinary (image storage)

Map integration (Mapbox / Leaflet)

Passport.js (authentication)

# 📁 Folder Structure

```bash
wanderlust/
│
├── models/                # Database schemas (Mongoose models)
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── views/                 # EJS templates (Frontend)
│   ├── layouts/
│   │     └── boilerplate.ejs
│   │
│   ├── listings/
│   │     ├── index.ejs
│   │     ├── show.ejs
│   │     ├── new.ejs
│   │     └── edit.ejs
│   │
│   ├── users/
│   │     ├── signup.ejs
│   │     └── login.ejs
│   │
│   └── includes/
│         ├── navbar.ejs
│         └── footer.ejs
│
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── middleware/
│   ├── auth.js
│   └── validate.js
│
├── public/
│   ├── css/
│   ├── js/
│   │    └── map.js
│   └── images/
│
├── utils/
│   ├── ExpressError.js
│   └── wrapAsync.js
│
├── config/
│   ├── db.js
│   ├── cloudinary.js
│   └── passport.js
│
├── .env
├── .gitignore
├── package.json
├── app.js
└── README.md
```


# ✅ Why This Structure is Good

✔ Separation of Concerns
Each folder has one responsibility → easier debugging & scaling.

✔ MVC Architecture

Models → Data

Views → UI

Controllers → Logic

✔ Recruiter Friendly
Shows you understand real production project design, not beginner structure.

# 🌱 Future Enhancements

🔎 Smart search with filters

❤️ Wishlist functionality

💳 Online booking & payments

🧑‍💼 Admin dashboard

🌐 Google OAuth login

📊 Analytics

# ✅ Conclusion

Wanderlust is a production-inspired full-stack web application that demonstrates my ability to design and develop scalable, secure, and user-centric platforms. Through this project, I have applied industry best practices such as MVC architecture, RESTful routing, authentication, and cloud integrations to build a seamless digital experience.

This project reflects my continuous commitment to learning, problem-solving, and building real-world applications that create meaningful impact. As I grow as a developer, I look forward to enhancing Wanderlust with more advanced features and performance optimizations.
