# Food-Delivery-Using-FSD
# 🍔 Food Delivery App — Full Stack Development (FSD)

A fully functional food delivery web application inspired by platforms like Swiggy and Zomato.  
Users can browse restaurants, add items to cart, and place orders — all from a clean and responsive interface.

---

## 🚀 Live Demo

🔗 Coming Soon  
📦 GitHub Repo: [https://github.com/gangadharthotakura/Food-Delivery-Using-FSD](https://github.com/gangadharthotakura/Food-Delivery-Using-FSD)

---

## 📸 Features

- 🧑‍🍳 Browse list of restaurants
- 🍕 View menu items with categories
- 🛒 Add to cart and adjust quantities
- 🧾 Checkout with order summary
- 🧑‍💻 User authentication (Login/Register)
- 🧾 Admin: Add/edit/remove items
- 💳 Stripe test payment integration (optional)

---

## ⚙️ Tech Stack

| Layer        | Technology |
|--------------|------------|
| Frontend     | React.js, Redux, Axios, Bootstrap / Tailwind CSS |
| Backend      | Node.js, Express.js |
| Database     | MongoDB (via Mongoose) |
| Auth         | JWT-based Login/Register |
| Hosting      | Netlify (Frontend), Render / Vercel / Railway (Backend) |

---

## 🔧 Installation

### 1. Clone the Repo

```bash
git clone https://github.com/gangadharthotakura/Food-Delivery-Using-FSD.git
cd Food-Delivery-Using-FSD
2. Install Dependencies
bash
Copy
Edit
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
3. Configure Environment Variables
Create a .env file in the backend:

env
Copy
Edit
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_test_key (optional)
4. Run the App
bash
Copy
Edit
# Backend
cd server
npm start

# Frontend (in a new terminal)
cd ../client
npm start
App runs at: http://localhost:3000

💳 Stripe Test Card
Use the following credentials for test payments:

yaml
Copy
Edit
Card Number: 4242 4242 4242 4242
Expiry: 12/26
CVV: 123
🙋 Developed By
Gangadhar Thotakura
🎓 B.Tech AIML | 📬 thotakuragangadhar@gmail.com
🌐 Portfolio | LinkedIn | GitHub

📌 License
This project is intended for learning and educational purposes only.
All product and company names are trademarks™ or registered® trademarks of their respective holders.

yaml
Copy
Edit

---

### ✅ To Use It:

1. Save it as `README.md` in the root of your project.
2. Run:

```bash
git add README.md
git commit -m "Added project README"
git push origin main
