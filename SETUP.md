# Todo App Setup Guide

## Backend Setup

1. **Install Backend Dependencies:**
   ```bash
   cd Backend
   npm install
   ```

2. **Create Environment File:**
   Create a `.env` file in the Backend directory with:
   ```
   MONGO_URI=mongodb://localhost:27017/todoapp
   ```

3. **Start MongoDB:**
   - Make sure MongoDB is installed and running
   - Or use MongoDB Atlas (cloud) and update the MONGO_URI

4. **Start Backend Server:**
   ```bash
   npm start
   ```

## Frontend Setup

The frontend is already running on http://localhost:5175/



## Current Status

- Frontend: ✅ Running on port 5175
- Backend: ⚠️ Needs to be started
- Database: ⚠️ Needs MongoDB connection

## Next Steps

1. Install backend dependencies
2. Set up MongoDB connection
3. Start the backend server
4. Test the full application

