# 🍓 Organic Market

A full-stack e-commerce web application that allows users to browse organic products, view product details, manage a shopping cart, and simulate a checkout process.

## 🔗 Live Demo

- Frontend: [https://store-frontend-three-flax.vercel.app](https://store-frontend-three-flax.vercel.app)
- Backend: [https://store-backend-36zr.onrender.com](https://store-backend-36zr.onrender.com)

## 🛠 Tech Stack

**Frontend:**
- React
- Tailwind CSS
- React Router
- Vite
- LocalStorage (session/cart)

**Backend:**
- FastAPI
- SQLite
- SQLAlchemy
- Render for deployment
- RESTful API with CORS and modular routing

## 📁 Project Structure

```
Organic-Market/
├── backend/
│   ├── main.py
│   ├── db/
│   ├── routers/
│   ├── models/
│   └── requirements.txt
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md
```

## 🚀 Features

- User login (local simulation)
- Product listing & detail pages
- Add to cart functionality (stored per user in localStorage)
- Responsive UI with Tailwind CSS
- Dynamic routing for products and cart pages
- Deployed with CI/CD using GitHub, Render, and Vercel

## 🧪 How to Run Locally

1. **Clone the repo:**

```bash
git clone https://github.com/your-username/organic-market.git
cd organic-market
```

2. **Run Backend:**

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

3. **Run Frontend:**

```bash
cd frontend
npm install
npm run dev
```

4. Visit `http://localhost:5173`

## ✍️ Author

Made with ❤️ by Misgana Kebede.