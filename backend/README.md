# Samarthanam Backend

This is the backend for the Samarthanam application, providing API endpoints for authentication, events management, user profiles, and event registration.

## Technologies Used

- Python 3.8+
- Flask - Web framework
- MongoDB - Database
- JWT - Authentication

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- MongoDB installed locally or a MongoDB Atlas account
- pip (Python package manager)

1. Set up MongoDB:
   - Make sure MongoDB is running locally on port 27017, or
   - Create a MongoDB Atlas cluster and update the `MONGO_URI` in `.env` file

2. Update the `.env` file:
   - Set a secure `JWT_SECRET_KEY`
   - Update `MONGO_URI` if needed

### Initialize Database

Run the following command to initialize the database with sample data:

```
python init_db.py
```

This will create:
- Admin user: admin@samarthanam.org / admin123
- Volunteer user: volunteer@example.com / volunteer123
- Participant user: participant@example.com / participant123
