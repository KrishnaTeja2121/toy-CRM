# Tiny CRM

A minimal Customer Relationship Management (CRM) application for learning full-stack fundamentals.

## Features
- Node.js/Express backend (REST API, in-memory customer storage)
- React frontend (single page, customer management UI)
- Simple CRUD operations: list, add, edit, delete customers

## Project Structure
```
tinyCRM/
├── server/   # Node.js/Express backend
│   └── index.js
│   └── package.json
├── client/   # React frontend (manual setup)
│   └── App.js
│   └── index.js
│   └── index.html
│   └── package.json
```

## Getting Started

### Backend
1. `cd server`
2. `npm install`
3. `npm start` (runs on http://localhost:4000)

### Frontend
1. `cd client`
2. `npm install`
3. Use a static server (e.g. `npx serve .`) to serve `index.html`

> Note: The frontend is a minimal React setup (not using create-react-app). You may want to add a bundler (like Vite or Parcel) for a better developer experience.

## Next Steps
- Build out the customer management UI in React
- Connect frontend to backend API
- Add form validation and error handling

---

This project is a learning exercise and not intended for production use.
