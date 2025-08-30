# Eduprime Clone (MERN + Firebase)

This is a reference implementation of the mini project described in your documents: a simple education management system with Student, Teacher, and Admin roles.  
Features include attendance tracking, mid marks, feedback, leave requests, and holidays.

## Stack
- **Frontend**: React (Vite), Firebase Auth, Axios
- **Backend**: Node + Express, Firebase Admin token verification, MongoDB (Mongoose)
- **Database**: MongoDB for app data; Firebase used for Auth (and can be extended for Storage/FCM)

## Quick Start

### Backend
```bash
cd server
npm i
cp ../.env.example .env   # then fill values
npm run dev
```

### Frontend
```bash
cd client
npm i
cp .env.example .env      # then fill Firebase web config
npm run dev
```

Login via Firebase email/password; on first login, call `/api/auth/register` to set your app role (student/teacher/admin).
