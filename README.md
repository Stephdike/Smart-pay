# SmartPay - MERN FinTech Project
SmartPay is a minimal peer-to-peer payment web app built with the MERN stack (MongoDB, Express, React, Node.js).

## What is included
- `backend/` - Express server with user auth (JWT), wallet top-up (mock), peer-to-peer transfers, transaction history.
- `frontend/` - React app with basic pages: Register, Login, Dashboard.
- `PITCH_DECK.txt` - Slide-by-slide content you can copy into Google Slides or Canva.

## How to run (backend)
1. Create a `.env` in `backend/` with:
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
2. From `backend/`:
```
npm install
npm run dev
```
(Assumes you have Node.js and MongoDB available)

## How to run (frontend)
1. From `frontend/`:
```
npm install
npm start
```

## Notes
- The project uses environment variables for MongoDB and JWT secret.
- The payment top-up endpoint is a mocked endpoint for demo; integrate a real payment gateway for production.
- Add validations, rate-limiting, HTTPS, and further security for production use.
