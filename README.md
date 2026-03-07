# StayVerse

**Vacation Rental Management System**

StayVerse is a scalable web application designed for managing vacation rental property listings. The platform enables users to create, browse, update, and manage property listings with location-based visualization, following clean software architecture principles.

---

## 🚀 Features

* **User Authentication**: Secure signup and login using Passport.js and express-session.
* **Listing Management**: Complete CRUD operations for property listings (Create, Read, Update, Delete).
* **Interactive Maps**: Real-time property location visualization using MapLibre GL and geocoding.
* **Review System**: Users can leave and manage reviews for listings.
* **Responsive UI**: Built with EJS-mate templates and custom CSS for a seamless experience across devices.
* **Cloud Integration**: Image uploads handled via Cloudinary.

---

## 🧱 Architecture

The application is built using the **MVC (Model–View–Controller)** design pattern:

* **Model**: Data schemas defined with Mongoose (MongoDB).
* **View**: Dynamic server-side rendering using EJS and ejs-mate.
* **Controller**: Business logic and request management separated into dedicated controllers.

This separation of concerns ensures scalability, maintainability, and clean code organization.

---

## 🛠 Tech Stack

* **Backend**: Node.js, Express.js
* **Database**: MongoDB (Atlas) with Mongoose ODM
* **Authentication**: Passport.js, passport-local, passport-local-mongoose
* **Templating**: EJS, EJS-Mate
* **Maps**: MapLibre GL, Geocoding API
* **Middleware**: express-session, connect-mongo, connect-flash, method-override, cookie-parser
* **Utilities**: Joi (for schema validation), Multer & Cloudinary (for file uploads)

---

## 📂 Project Structure

```text
Major_Project/
├── controllers/    # Request handlers for listings, reviews, and users
├── models/         # Mongoose schemas for listings, reviews, and users
├── routes/         # Express routers for modular path handling
├── views/          # EJS templates for front-end rendering
├── public/         # Static assets (CSS, client-side JS, images)
├── utils/          # Utility functions and custom error handling
├── app.js          # Core application configuration and middleware
├── cloudConfig.js  # Cloudinary configuration for media storage
├── server.js       # Entry point to start the server
└── package.json    # Project dependencies and metadata
```

---

## 📌 Getting Started

### Prerequisites

* Node.js (v22.16.0 recommended)
* MongoDB (Local or Atlas)
* Cloudinary Account (for image uploads)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HarshaVardhan31012007/Major_Project.git
   cd Major_Project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Environment Variables:
   Create a `.env` file in the root directory and add the following:
   ```env
   CLOUD_NAME=your_cloudinary_name
   CLOUD_API_KEY=your_cloudinary_key
   CLOUD_API_SECRET=your_cloudinary_secret
   ATLASDB_URL=your_mongodb_connection_string
   SECRET=your_session_secret
   ```

4. Start the application:
   ```bash
   npm start
   ```

---

## 📈 Use Case

StayVerse can be used as a foundation for building property listing, rental discovery, and hospitality management platforms, with support for future enhancements like booking systems, reviews, and payments.

---

## 📄 License

This project is for educational and portfolio purposes.

## 👤 Author

**Harsha Vardhan**

GitHub: [https://github.com/Harsha](https://github.com/Harsha)
