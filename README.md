# ThinkBoard

ThinkBoard is a full-stack note-taking application built with the MERN stack (MongoDB, Express, React, Node.js). It allows users to create, view, and manage notes efficiently.

## Features
- Create, view, and delete notes
- RESTful API backend with Express and MongoDB
- Modern React frontend
- Environment variable support with dotenv
- Tailwind CSS for styling (frontend)

## Project Structure
```
backend/
  src/
    server.js
    controllers/
    routes/
frontend/
  src/
    App.jsx
    pages/
```

## Getting Started

### Prerequisites
- Node.js (v16 or above recommended)
- npm or yarn
- MongoDB (local or Atlas)

### Backend Setup
1. Navigate to the backend folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the backend root with your MongoDB URI and any other environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5001
   ```
4. Start the backend server:
   ```sh
   npm run dev
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend development server:
   ```sh
   npm start
   ```

### Tailwind CSS
Make sure your `tailwind.config.js` content array includes all relevant source files, e.g.:
```js
content: [
  "./src/**/*.{js,jsx,ts,tsx}",
  "./public/index.html"
],
```

## .gitignore
Sensitive files like `.env` and `node_modules` are already ignored by default.

## License
This project is licensed under the ISC License.
