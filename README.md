# **E-Commerce Store 🛒**

![Demo App](/frontend/public/screenshot-for-readme.png)


## **Overview**

Welcome to the **E-Commerce Store**! This is a modern, full-featured e-commerce application designed to provide an intuitive shopping experience for users and robust management capabilities for administrators. It leverages a rich technology stack to ensure performance, scalability, and security.

### **Key Features**
- 🚀 **Project Setup**: Get started quickly with a well-organized project structure.
- 🗄️ **Database Integration**: MongoDB for scalable storage, Redis for caching and session management.
- 💳 **Payment Gateway**: Secure payments with Stripe.
- 🔐 **Authentication**: Secure signup and login using JWT with refresh and access tokens.
- 🛒 **Core E-Commerce Features**: Manage products, categories, shopping carts, and more.
- 🏷️ **Coupon Codes**: Easily implement discounts.
- 👑 **Admin Dashboard**: Comprehensive control over products, orders, and analytics.
- 📊 **Sales Analytics**: Visualize sales data with ease.
- 🎨 **Frontend Design**: Sleek, responsive design using Tailwind CSS.
- 🔒 **Security**: Protect user data and ensure a secure shopping environment.
- 🚀 **Caching**: Speed up operations with Redis caching.
- ⌛ **And much more...**

---

## **Technology Stack**

- **Frontend**: React with Tailwind CSS for styling.
- **Backend**: Node.js, Express.js.
- **Database**: MongoDB for data storage, Redis for caching.
- **Authentication**: JSON Web Tokens (JWT) for secure user sessions.
- **Payment Integration**: Stripe API for seamless checkout.
- **Media Management**: Cloudinary for storing and managing images.

---

## **Environment Variables**

Before running the application, set up your `.env` file with the following keys:

```env
PORT=5000
MONGO_URI=your_mongo_uri
UPSTASH_REDIS_URL=your_redis_url
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
