# 🍱 DabbaBites  
_A Smart Platform for Cloud Kitchen-Based Tiffin Services_  

DabbaBites is a web-based food delivery platform that connects users with local cloud kitchens and home-based tiffin providers. It promotes eco-friendly packaging and supports small food businesses by offering them a digital storefront.

---

## 🌟 Key Features
- 🔍 Search and browse local cloud kitchens  
- 🛒 Add items to cart and place orders  
- 👤 User login/register with **JWT authentication**  
- 📦 Track orders in real-time  
- 📝 Leave reviews with text, rating, and image  
- 🧑‍🍳 **Admin Panel** for managing kitchens and orders  
- 🌱 Supports eco-friendly packaging initiatives  

---

## 🛠 Tech Stack
Frontend: React.js +  CSS  
Backend: Node.js + Express.js  
Database: MongoDB Atlas (Cloud)  
Authentication: JWT + bcrypt  
Payment Gateway: Stripe API  


---

## 🚀 Installation

### 1️⃣ Prerequisites
- [Node.js](https://nodejs.org/) (v14 or later)  
- [MongoDB Atlas](https://www.mongodb.com/atlas) account  
- [Git](https://git-scm.com/)  
- Stripe API keys (for payment integration)  

---

### 2️⃣ Clone the Repository
git clone https://github.com/rudrakkhighosh/dabbabites.git


## Environment Variables
Create a .env file inside the backend folder and add:
PORT=5000
MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key

📌 Notes
Ensure MongoDB Atlas cluster is active before running the backend.

Stripe payments work only with valid test or live API keys.
