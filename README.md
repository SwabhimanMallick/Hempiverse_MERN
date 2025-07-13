# MERN Stack E-Commerce Platform (Vite + Express)

A full-stack e-commerce app built using the MERN stack with **Vite** for the frontend. It includes user authentication, product filtering, cart management, order placement, and an admin dashboard.

## 🔧 Tech Stack
- Frontend: React + Vite, Tailwind CSS
- Backend: Node.js, Express.js, MongoDB, JWT
- Tools: Mongoose, bcrypt, PayPal SDK

## 📁 Project Structure
```
root/
├── client/      # React frontend (Vite)
├── server/      # Express backend
├── .env         # Environment variables
```

## ⚙️ Environment Variables

server/.env
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

client/.env
```
VITE_API_URL=http://localhost:5000/api
```

## 🚀 Running the Project Locally

```bash
# Start frontend
cd client
npm install
npm run dev

# Start backend
cd ../server
npm install
npm run dev
```

## 🏗️ Build Frontend for Production

```bash
cd client
npm run build
```

## 📄 License
MIT
