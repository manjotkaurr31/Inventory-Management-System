# Inventory Management System - FullStack

A robust full-stack inventory lifecycle tracker engineered with the PERN stack (PostgreSQL, Express, React, Node.js). This platform streamlines product procurement, supplier relations, and real-time stock movements. The system's core innovation is an AI-powered natural language interface leveraging the LLaMA 3 (Groq API) which allows users to perform complex data analysis via natural English inputs dynamically translated into optimized SQL using Natural Language Processing.

---

## Tech Stack

- **Frontend:** React, Axios, Bootstrap/CSS Modules
- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **Auth:** JWT
- **Testing** Postman
- **AI Integration:** GROQ LLaMA 3 API to auto-generate SQL queries
---

## Features

- AI-powered query interface
- Product, Category & Supplier management
- Stock movement tracking (IN / OUT)
- Analytics dashboard
- Secure login/signup with JWT
- Export reports as PDF
- Custom UI with pink theme

---

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/manjotkxur/InventoryManagementSystem.git
```

### 2. Environment Setup
Create a `.env` file in `backend/`:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/db_name
JWT_SECRET=your_jwt_secret
NODE_ENV=development
DATABASE_URL=your_postgreSQL_URL
PORT=xxxx
```

### 3. Install Dependencies
```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 4. Setup Database
```bash
# From the root of the repo (refer attachment - schema.sql)
psql -U postgres -d inventory < schema.sql
```

### 5. Run Development Servers
```bash
# Terminal 1
cd backend
npm run dev

# Terminal 2
cd frontend
npm run dev
```
---
