🛒 Aryak E-Commerce - Full-Stack MERN Platform

Welcome to Aryak E-Commerce! This is a complete, feature-rich e-commerce website built using the MERN stack (MongoDB, Express, React, Node.js). It features a clean user interface, a powerful admin panel for site management, and secure payment processing through Stripe.

![alt text](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![alt text](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![alt text](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![alt text](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![alt text](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![alt text](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white)

✨ Features

This platform is divided into two main parts: the customer-facing storefront and the admin management panel.

🛍️ User & Customer Features

Authentication: Secure Sign Up, Login, and Logout functionality.

Product Discovery:

🏠 Homepage with featured products and categories.
🔍 Powerful search functionality to find products by name or category.
🎛️ Advanced filtering on category pages.
↕️ Sort products by price (Low to High & High to Low).
Product Details:
🖼️ Rich product detail page with multiple images and an image zoom-on-hover feature.
📝 Detailed product descriptions, brand, and pricing information.
👍 Recommended products section to encourage further browsing.

Shopping Cart:
➕ Add products to the cart with a single click.
🛒 A dedicated cart page to review items.
🔢 Increase, decrease, or remove items from the cart.
💰 Real-time calculation of total quantity and price.

Checkout & Orders:
💳 Secure payment processing handled by Stripe.
✅ Elegant success and cancellation pages post-payment.
📜 A dedicated "My Orders" page to view order history and payment details.
🛠️ Admin Panel Features
Secure Admin Dashboard: Protected routes accessible only to users with an ADMIN role.

Product Management:
➕ Upload New Products: A dedicated modal to add new products with name, brand, category, price, description, and multiple images.
✏️ Edit Products: Easily update details for any existing product.
🖼️ Manage Images: Add or delete product images.
📊 View All Products: A comprehensive list of all products in the inventory.

User Management:
👥 View All Users: See a complete list of all registered users.
👑 Update User Roles: Promote users from GENERAL to ADMIN for administrative access.
🚀 Tech Stack

This project is built with a modern and robust technology stack:
Category	Technology
Frontend	React, React Router, Redux Toolkit, Tailwind CSS, React Toastify, React Icons
Backend	Node.js, Express.js, CORS, Cookie-Parser
Database	MongoDB with Mongoose
Auth	JSON Web Tokens (JWT), bcryptjs for password hashing
Payments	Stripe for secure checkout
Image Store	Cloudinary for cloud-based image hosting and management
Testing	Selenium WebDriver for End-to-End testing
⚙️ Getting Started
To get a local copy up and running, follow these simple steps.
Prerequisites
Make sure you have the following installed on your machine:
Node.js (v14 or higher)
npm
MongoDB (or a MongoDB Atlas account)
Backend Setup
Clone the repository:
code
Sh
git clone https://your-repository-url.git
Navigate to the backend directory:
code
Sh
cd backend
Install dependencies:
code
Sh
npm install
Create a .env file in the backend root directory and add the following environment variables.
code
Env
PORT=8080
MONGODB_URI=your_mongodb_connection_string
TOKEN_SECRET_KEY=your_strong_jwt_secret_key
FRONTEND_URL=http://localhost:3000

# Stripe Keys
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_ENPOINT_WEBHOOK_SECRET_KEY=your_stripe_webhook_secret
Run the server:
code
Sh
npm run dev
The backend server will start on http://localhost:8080.
🎨 Frontend Setup
Navigate to the frontend directory:
code
Sh
cd frontend
Install dependencies:
code
Sh
npm install
Create a .env file in the frontend root directory and add your Cloudinary cloud name.
code
Env
REACT_APP_CLOUD_NAME_CLOUDINARY=your_cloudinary_cloud_name
Run the client:
code
Sh
npm start
The React development server will start, and your project will be accessible at http://localhost:3000.
🧪 Running Tests
This project includes End-to-End (E2E) tests written with Selenium WebDriver to simulate real user interactions.
Prerequisite: Download the msedgedriver.exe compatible with your version of Microsoft Edge and place it in the frontend directory.
Navigate to the frontend directory:
code
Sh
cd frontend
Run the tests:
code
Sh
npm test
This will launch the test runner and execute the Selenium test scripts for features like Signup, Login, Product Search, and Add to Cart.
Feel free to clone, fork, and contribute! If you have any questions or suggestions, don't hesitate to reach out. Happy coding! ✨
