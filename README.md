<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">


<div class="container">
  <h1>🎬 Movie Booking System</h1>
  <p>A simple, clean preview of your README.md (Next.js + Node.js project).</p>

  <div class="section">
    <h2>📌 Project Summary</h2>
    <p>This app evolves from a basic booking MVP to a production-ready system with authentication, payments, real-time seat locking, analytics, and deployment.</p>
  </div>

  <div class="section">
    <h2>✅ Features by Evaluation</h2>

    <h3>Evaluation 1 — Core MVP</h3>
    <ul>
      <li>Movie list, movie details, showtimes</li>
      <li>Static seat map & basic booking</li>
      <li>Admin CRUD for movies & showtimes</li>
      <li>REST APIs + seed data</li>
    </ul>

    <h3>Evaluation 2 — Real Users & Payments</h3>
    <ul>
      <li>User Login / Register</li>
      <li>Stripe/Razorpay test payment</li>
      <li>Seat locking (5 min)</li>
      <li>Email + QR confirmation</li>
    </ul>

    <h3>Evaluation 3 — Production & Real-time</h3>
    <ul>
      <li>WebSocket real-time seat updates</li>
      <li>Promo codes + refunds</li>
      <li>Analytics dashboard</li>
      <li>Deployment (Vercel + Render)</li>
    </ul>
  </div>

  <div class="section">
    <h2>📁 Next.js Folder Structure</h2>
    <pre>
.
├─ app/
├─ components/
├─ hooks/
├─ lib/
├─ public/
├─ styles/
├─ .env.local
├─ next.config.js
├─ package.json
└─ README.md
    </pre>
  </div>

  <div class="section">
    <h2>⚡ Quick Start</h2>
    <pre>
# Frontend (Next.js)
pnpm install
pnpm dev

# Backend
pnpm install
pnpm run seed
pnpm dev
    </pre>
  </div>

  <div class="section">
    <h2>🔌 Sample API Routes</h2>
    <pre>
GET /api/movies
GET /api/showtimes?movieId=
POST /api/bookings
POST /api/showtimes/:id/lock
    </pre>
  </div>

</div>

</body>
</html>
