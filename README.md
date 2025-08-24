# SunSeat Backoffice

Vite + React web app for admin management.

## Features
- Auth: Firebase admin login.
- Dashboard: View bookings, analytics (occupancy for Galé/Comporta).
- Chairs Management: CRUD with map previews (@react-google-maps/api).
- Notifications: Manual send via Firebase.
- UX: Responsive design, better than BeachNow (dark mode, intuitive tables/charts).

## Setup
- `npm install`
- Add .env (VITE_API_URL, VITE_GOOGLE_MAPS_API_KEY, VITE_FIREBASE_CONFIG).
- Run `npm run dev`[](http://localhost:5173).

## Scaling: Add user management, reports export.