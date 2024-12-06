# Backend: Twitter-YouTube Backend API

Welcome to **Learning-Backend**, a **production-ready backend API** designed for a hybrid **Twitter-YouTube** platform. This backend allows users to upload videos, associate them with authors, and interact with data through optimized custom APIs. Built with **Node.js** and **Express.js**, the system leverages **MongoDB Atlas** for data storage and **Mongoose** for data modeling.

This project is fully optimized, rigorously tested with **Postman**, and ready for production. Note that the front-end for this project is yet to be developed.

---

## ⚡ Features

- **Video Uploads**: Seamlessly upload videos and link them to a perfect author.
- **Custom Error Handling**: Handles errors in a structured way with meaningful messages.
- **Custom API Responses**: Provides consistent and well-structured API responses.
- **Optimized Data Models**: Data schemas designed with **Mongoose** to ensure high performance.
- **MongoDB Atlas**: Data is securely stored and managed in **MongoDB Atlas** for scalability and reliability.
- **Tested and Production-Ready**: Thoroughly tested using **Postman** to ensure the API functions as expected in a production environment.

---

## 🛠️ Tech Stack

- **Node.js** – JavaScript runtime environment
- **Express.js** – Web framework for building RESTful APIs
- **MongoDB Atlas** – NoSQL database for data storage
- **Mongoose** – MongoDB object modeling tool for data schema definitions
- **Postman** – Used for API testing and documentation
- **Dotenv** – Environment variable management

---

## 🔧 Installation and Setup

Follow these steps to set up the backend API locally:

### 1. Clone the repository

```bash
git clone https://github.com/hemantyadav8006/learning-backend.git
cd learning-backend
```

### 2. Install Dependencies

Make sure you have Node.js installed. Then, install the project dependencies:

```bash
npm install
```

### 3. Configure Environment Variables

Create a **.env** file in the root directory and add the following:

```plaintext
MONGO_URI=<Your_MongoDB_Atlas_Connection_String>
PORT=5000
```

### 4. Start the Server

```bash
npm start
```

- The server will now be running on http://localhost:5000 (or whichever port you choose).

- Test the API with Postman