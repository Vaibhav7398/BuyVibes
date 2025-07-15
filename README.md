BuyVibes - E-Commerce Platform (MERN Stack)
📌 Overview
BuyVibes is a comprehensive e-commerce web application developed with the MERN (MongoDB, Express.js, React, Node.js) technology stack. It offers a seamless shopping experience, complete with user authentication, a product catalog, shopping cart, order tracking, admin management, and integrated payment solutions.

🚀 Key Features
Frontend: Crafted using Vite + React for fast, responsive UI with pages including Home, Collections, Product Details, Cart, Orders, Login/Register, About, and Contact.

Backend: Powered by Node.js and Express, managing APIs, business logic, and database interactions.

Authentication: JWT-based secure authentication for both users and admins.

Product & Inventory Management: Admins can add, update, and remove products with ease.

Shopping Cart & Orders: Persistent cart functionality and streamlined order placement.

Admin Dashboard: Centralized panel for managing products, orders, and users.

Payment Gateway: Supports multiple payment options through Stripe and Razorpay.

Image Upload: Product images are managed via Cloudinary with Multer for server-side handling.

Deployment: Live deployments facilitated through Vercel.

📁 Project Structure
bash
Copy
Edit
/frontend  - Vite React app for the customer interface
/backend   - Node.js + Express REST API with MongoDB
/admin     - Admin panel for store management
🛠️ Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Vaibhav7398/BuyVibes.git
Navigate to the Project

bash
Copy
Edit
cd BuyVibes
Install Dependencies

bash
Copy
Edit
cd frontend
npm install

cd ../backend
npm install

cd ../admin
npm install
Run Development Servers

bash
Copy
Edit
cd frontend
npm run dev
bash
Copy
Edit
cd ../backend
npm run dev
bash
Copy
Edit
cd ../admin
npm start
Visit the App
Frontend: http://localhost:5174/
Backend: http://localhost:5000/
Admin Panel: Configured on a separate port if specified.

🛒 Tech Stack
Frontend: React, Redux, React Router, Vite

Backend: Node.js, Express

Database: MongoDB

Authentication: JWT

Payments: Stripe, Razorpay

File Storage: Cloudinary, Multer

Deployment: Vercel

🌐 Deployment Guide
Push your complete project to GitHub.

Deploy the frontend and admin panel on Vercel.

Deploy the backend to platforms like Render, Heroku, or Railway if needed.

Update your frontend environment variables to point to the hosted backend API.

🎯 BuyVibes offers an end-to-end e-commerce solution with modern tech, scalability, and a professional UI/UX for both customers and administrators
