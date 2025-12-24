🛒 Urban-Cart — Modern React E-Commerce App

Urban-Cart is a fully responsive e-commerce web application built with React + Vite + Bootstrap.
It allows users to browse products, manage cart items, and place orders using a JSON-based backend.

🚀 Live Demo

Live: e-commerce-app-react-js-three.vercel.app

📸 Screenshots
Home Page

✨ Features

🛍 Product listing from JSON Server

🛒 Add to cart & cart modal

📦 Order history management

🔄 Loading & error handling UI

⚡ Fast performance using Vite

🎨 Clean & responsive UI with Bootstrap

🌐 Custom HTTP Hook (useHttp)


📁 Modular & scalable project structure

| Tech        | Purpose            |
| ----------- | ------------------ |
| React       | Frontend framework |
| Vite        | Build tool         |
| Bootstrap   | Styling            |
| JSON Server | Mock REST API      |
| JavaScript  | Logic              |
| CSS         | Styling            |


📂 Project Structure
src/
 ┣ assets/
 ┣ components/
 ┃ ┣ CartModal.jsx
 ┃ ┣ Navbar.jsx
 ┃ ┣ Orders.jsx
 ┃ ┣ Product.jsx
 ┃ ┣ Loading.jsx
 ┃ ┗ Error.jsx
 ┣ hooks/
 ┃ ┗ http.js
 ┣ App.jsx
 ┣ main.jsx
 ┣ index.css

⚙️ Installation

Clone Repository
git clone https://github.com/your-username/urban-cart.git
cd urban-cart

Install Dependencies
npm install

Run Backend
npx json-server --watch db.json --port 5000

Run Frontend
npm run dev


Open in browser:

http://localhost:5173

| Method | Endpoint  | Description        |
| ------ | --------- | ------------------ |
| GET    | /products | Fetch all products |
| POST   | /orders   | Save order data    |
| GET    | /orders   | View orders        |
