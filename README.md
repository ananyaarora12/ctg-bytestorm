# Samarthanam Volunteer Management System

This is a full-stack application for managing volunteers, participants, and events for Samarthanam.

## Project Structure

The project is divided into two main parts:
- Frontend: Next.js application in the root directory
- Backend: Flask API and MongoDB in the `backend` directory

## Frontend Setup

1. Install dependencies:
```
npm install
```

2. Run the development server:
```
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Backend Setup

### Prerequisites
- Python 3.8 or higher
- MongoDB installed locally or a MongoDB Atlas account

### Installation

1. Navigate to the backend directory:
```
cd backend
```

2. Run the setup script:
   - On macOS/Linux:
   ```
   ./setup.sh
   ```
   - On Windows:
   ```
   setup.bat
   ```

   This will:
   - Create a virtual environment
   - Install dependencies
   - Initialize the database with sample data

3. Start the backend server:
   - On macOS/Linux:
   ```
   source venv/bin/activate
   python run.py
   ```
   - On Windows:
   ```
   venv\Scripts\activate
   python run.py
   ```

The backend server will run on [http://localhost:5000](http://localhost:5000).

## Sample Accounts

After initializing the database, the following accounts will be available:

- Admin: admin@samarthanam.org / admin123
- Volunteer: volunteer@example.com / volunteer123
- Participant: participant@example.com / participant123

## Features

- User authentication (login/register)
- Role-based access (Admin, Volunteer, Participant)
- Event management
- Event registration
- User profiles
- Dashboard for each user role

## Getting Started

First, run the development server:

```bash
npm run dev
```
