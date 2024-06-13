# Clipboard Sharing App

## Project Description
This project allows users to copy text on their phone and send it to their PC clipboard. It demonstrates skills in full-stack development, real-time communication, and cross-platform integration.

## Tech Stack
- **Frontend**: React, hosted on Netlify or GitHub Pages.
- **Backend**: Node.js with Express, hosted on Heroku.
- **Database**: MongoDB Atlas (free tier).

## Development Steps

### 1. Develop Locally
- **Frontend**: Create a React application.
  - Use create-react-app to bootstrap your project.
  - Implement a simple UI with a form to submit text and a display area for received text.
- **Backend**: Create a Node.js server with Express.
  - Set up basic routes for receiving and sending clipboard data.
  - Implement WebSocket or HTTP for real-time communication.

### 2. Use MongoDB Atlas
- Set up a free-tier MongoDB Atlas cluster.
- Connect your Express server to the MongoDB database.

### 3. Deploy
- **Frontend**: Deploy the React application to Netlify or GitHub Pages.
- **Backend**: Deploy the Node.js server to Heroku.
  - Ensure environment variables for MongoDB connection are set in Heroku.

### Notes
- Utilize free tiers of services to avoid costs.
- Ensure secure handling of clipboard data and user authentication if needed.
