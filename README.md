# FoodDiscover - React Frontend

A full-stack food discovery application built with React, Node.js, Express, and MongoDB.

## 🚀 Tech Stack

### Frontend (React)
- **React 18** - Component-based UI library
- **TypeScript** - Type-safe JavaScript
- **React Router** - Client-side routing
- **Axios** - HTTP client for API calls
- **Tailwind CSS** - Utility-first CSS framework
- **Font Awesome** - Icons and UI elements

### Backend (Node.js/Express)
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **multer** - File upload handling

## 📁 Project Structure

```
FoodDiscover/
├── frontend/                 # React frontend
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── components/       # Reusable components
│   │   │   └── Navbar.tsx
│   │   ├── contexts/         # React contexts
│   │   │   └── AuthContext.tsx
│   │   ├── pages/            # Page components
│   │   │   ├── Home.tsx
│   │   │   ├── Login.tsx
│   │   │   ├── Register.tsx
│   │   │   ├── Upload.tsx
│   │   │   ├── Search.tsx
│   │   │   └── Dashboard.tsx
│   │   ├── App.tsx           # Main app component
│   │   ├── index.tsx        # Entry point
│   │   └── index.css        # Global styles
│   ├── package.json
│   └── tsconfig.json
├── backend/                  # Node.js backend
│   ├── routes/
│   ├── models/
│   ├── uploads/
│   └── server.js
└── README.md
```

## 🛠️ Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB Atlas account

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with your MongoDB connection string:
   ```
   MONGODB_URI=your_mongodb_atlas_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. Start the backend server:
   ```bash
   npm run dev
   ```
   The backend will run on `http://localhost:5000`

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```
   The frontend will run on `http://localhost:3000`

## 🎯 Features

### React Components
- **Home Page** - Landing page with hero section and features
- **Authentication** - Login and registration with form validation
- **Upload Page** - Food discovery upload with image handling
- **Search Page** - Advanced search and filtering
- **Dashboard** - User dashboard with statistics and food management
- **Navigation** - Responsive navbar with authentication state

### Key React Features
- **TypeScript** - Full type safety throughout the application
- **Context API** - Global state management for authentication
- **React Router** - Client-side routing with protected routes
- **Custom Hooks** - Reusable logic for API calls and state management
- **Responsive Design** - Mobile-first approach with Tailwind CSS
- **Error Handling** - Comprehensive error boundaries and user feedback

### API Integration
- **Axios Configuration** - Automatic token attachment for authenticated requests
- **Error Handling** - Centralized error handling for API responses
- **Loading States** - User-friendly loading indicators
- **Form Validation** - Client-side and server-side validation

## 🔧 Development

### Available Scripts

#### Frontend (React)
- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run tests
- `npm run eject` - Eject from Create React App

#### Backend (Node.js)
- `npm run dev` - Start with nodemon (development)
- `npm start` - Start production server

### Environment Variables
Create a `.env` file in the backend directory:
```
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/fooddiscover
JWT_SECRET=your_super_secret_jwt_key
PORT=5000
```

## 🚀 Deployment

### Frontend (React)
1. Build the production version:
   ```bash
   cd frontend
   npm run build
   ```

2. Deploy the `build` folder to your hosting service (Netlify, Vercel, etc.)

### Backend (Node.js)
1. Deploy to platforms like Heroku, Railway, or DigitalOcean
2. Set environment variables in your hosting platform
3. Ensure MongoDB Atlas is accessible from your deployment

## 📱 Features Overview

### User Authentication
- User registration with validation
- Secure login with JWT tokens
- Protected routes and authentication state management

### Food Discovery
- Upload food items with images
- Advanced search and filtering
- Vendor information and location details
- Dietary and nutrition information

### Dashboard
- Personal statistics and achievements
- Food discovery management
- User profile information
- Goal tracking and progress

## 🎨 UI/UX Features
- **Responsive Design** - Works on all device sizes
- **Modern UI** - Clean, intuitive interface
- **Loading States** - Smooth user experience
- **Error Handling** - User-friendly error messages
- **Accessibility** - WCAG compliant components

## 🔒 Security Features
- JWT-based authentication
- Password hashing with bcrypt
- Input validation and sanitization
- CORS configuration
- File upload security

## 📊 Database Schema
- **Users** - User profiles and authentication
- **Foods** - Food discoveries with metadata
- **Indexes** - Optimized for search performance

This React application provides a modern, scalable frontend for the FoodDiscover platform with full TypeScript support, comprehensive state management, and seamless integration with the existing Node.js backend.

