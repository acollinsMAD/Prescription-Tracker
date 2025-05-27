# Prescription Tracker

This workspace contains:

- `frontend/`: React Native app (Expo) with Auth0 authentication and Expo push notifications.
- `backend/`: Node.js NestJS API with MongoDB and Auth0 authentication.

## Getting Started

### Frontend
1. `cd frontend`
2. `npm start` (or `npx expo start`)

### Backend
1. `cd backend`
2. `npm run start:dev`

## Authentication
- Both frontend and backend use Auth0. Configure your Auth0 credentials in the respective `.env` files.

## Database
- Backend uses MongoDB. Set your MongoDB URI in `backend/.env`.

## Push Notifications
- The frontend uses Expo Notifications. See Expo docs for setup.

---

For more details, see the README files in each subfolder.
