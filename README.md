#Introduction
This is a full-stack e-commerce website built to demonstrate a modern web development stack. The website includes functionalities for user authentication, product listings, shopping cart, and order management.
#Features
User authentication (signup, login, logout)
Product listings with search and filter functionality
Product detail pages
Shopping cart management
Order placement and order history
Admin panel for product and order management
Responsive design
#Technologies Used
#Frontend
HTML, CSS, JavaScript
React.js
Redux for state management
Axios for HTTP requests
#Backend
Node.js
Express.js
MongoDB with Mongoose for database
JWT for authentication
Stripe for payment processing (optional)
#Deployment
Frontend: Vercel or Netlify
Backend: Heroku
Database: MongoDB Atlas
#Installation
#Prerequisites
Node.js and npm installed
MongoDB instance (local or MongoDB Atlas)
Stripe account (for payment processing)
#Steps
1.Clone the repository:
git clone https://github.com/yourusername/e-commerce-website.git
cd e-commerce-website
2.Install dependencies:
# Install backend dependencies
cd backend
npm install
# Install frontend dependencies
cd ../frontend
npm install
3.Set up environment variables:
Create a .env file in the backend directory with the following content:
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key (optional)
Node.js and npm installed
MongoDB instance (local or MongoDB Atlas)
4.Run the development server:
# Start backend server
cd backend
npm run dev
# Start frontend server
cd ../frontend
npm start
The frontend should be running on http://localhost:3000 and the backend on http://localhost:5000.
#Usage
#User
1.Sign up for an account.
2.Browse products and add them to the cart.
3.Proceed to checkout and place an order.
4.View order history in the user profile.
#Admin
1.Sign in as an admin.
2.Access the admin panel.
3.Manage products and orders.
#Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.
0 commit comments
Comments
