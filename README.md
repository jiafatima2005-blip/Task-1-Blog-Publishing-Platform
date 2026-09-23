# Blog Publishing Platform

Full-stack blog platform with:
- Node.js + Express REST API
- MongoDB + Mongoose
- JWT authentication
- React + Vite frontend
- Create, edit, delete your own posts
- Browse, read, search posts
- Comments

## Run locally

### 1. Start MongoDB
Use local MongoDB or MongoDB Atlas. Then copy `backend/.env.example` to `backend/.env` and set `MONGO_URI`.

### 2. Backend
```bash
cd backend
npm install
npm run dev
```
API runs on `http://localhost:5000`.

### 3. Frontend
```bash
cd frontend
npm install
npm run dev
```
Frontend runs on `http://localhost:5173`.

Set `VITE_API_URL` in `frontend/.env` if your backend URL differs.

## Deployment
- Frontend: Vercel/Netlify using `frontend` directory and `npm run build`.
- Backend: Render/Railway using `backend` directory and `npm start`.
- Add environment variables from the example files.
- Set frontend `VITE_API_URL` to the deployed backend URL.

A live URL cannot be created from this ZIP alone; deployment requires your hosting accounts and environment variables.
