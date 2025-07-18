# Hotels Project

A modern hotel management system built with React, TypeScript, and Node.js.
![Proje Görseli](/frontend//public/hotels.gif)  

## 🚀 Features

- Modern and responsive user interface
- Hotel listing and search functionality
- Detailed hotel information pages
- User authentication and authorization
- Booking management system
- Real-time updates and notifications

## 🛠️ Tech Stack

### Frontend
- React 19
- TypeScript
- Vite
- React Query for state management
- React Router for navigation
- TailwindCSS for styling
- Formik & Yup for form handling
- React Toastify for notifications
- Axios for API requests

### Backend
- Node.js
- Express.js
- RESTful API architecture
- CORS enabled
- Nodemon for development

## 📦 Project Structure

```
hotels/
├── frontend/           # React frontend application
│   ├── src/           # Source files
│   ├── public/        # Static files
│   └── package.json   # Frontend dependencies
│
└── backend/           # Node.js backend server
    ├── controllers/   # Route controllers
    ├── routes/        # API routes
    ├── middleware/    # Custom middleware
    ├── utils/         # Utility functions
    └── server.js      # Main server file
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone [https://github.com/omerffae/hotels.git]
cd hotels
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm start
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:3000`.

## 🔧 Development

- Frontend development server with hot reload: `npm run dev`
- Build frontend for production: `npm run build`
- Lint frontend code: `npm run lint`
