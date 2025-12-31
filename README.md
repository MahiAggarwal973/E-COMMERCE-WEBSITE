PROJECT TITLE:
##E-Commerce Website (MERN Stack)
A full-stack E-Commerce Web Application built using the MERN stack that allows users to browse products, add items to cart, place orders, and manage accounts.
This project focuses on real-world e-commerce functionality, authentication, and admin management.

##Key Features:
1.User Features:
-User Registration & Login (JWT Authentication)
-Browse products by category
-Product search & filtering
-Add to cart & update quantities
-Secure checkout process
-Order history tracking
2.Admin Features:
-Admin authentication
-Add, update & delete products
-Manage orders
-Manage users
-Dashboard for store control

##Tech Stack:
1.Frontend:
-React.js
-Context API
-Axios
-React Router
-CSS / Tailwind CSS
2.Backend:
-Node.js
-Express.js
-REST APIs
4.Database:
-MongoDB
-Mongoose
5.Authentication & Security:
-JWT (JSON Web Tokens)
-bcrypt.js
6.Deployment:
Vercel 

##Project Structure:
E-COMMERCE-WEBSITE
│
├── frontend/         # User-facing React app
│
├── admin/            # Admin panel
│
├── backend/          # Node.js & Express server
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   └── middleware/
│
├── .env
├── package.json
└── README.md

##Installation & Setup:
1️.Clone the Repository:
-git clone https://github.com/MahiAggarwal973/E-COMMERCE-WEBSITE.git
-cd E-COMMERCE-WEBSITE
2.Backend Setup:
-cd backend
-npm install
--Run backend server: npm run dev
3.Frontend Setup:
-cd frontend
-npm install
-npm start
4.Admin Panel Setup:
-cd admin
-npm install
-npm start

##Application Flow:
1.User registers / logs in
2.JWT token is generated and stored securely
3.User browses products from MongoDB
4.Cart state is managed using Context API
5.Order is placed and stored in database
6.Admin manages products & orders from admin panel

##What I Learned From This Project:
1.Building a complete e-commerce system
2.Implementing JWT-based authentication
3.Designing RESTful APIs
4.Handling admin & user roles
5.Managing global state with Context API
6.Connecting frontend with backend efficiently
7.Structuring a scalable MERN application

##Future Enhancements:
-Product reviews & ratings
-Order tracking system
-Better mobile responsiveness
-Email notifications
-Invoice generation

##AUTHOR
Mahi Aggarwal
GitHub: @MahiAggarwal973
