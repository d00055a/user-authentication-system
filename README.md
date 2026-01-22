# User Authentication System (Frontend)


## Overview

This project is a full-stack User Authentication System developed independently as part of a remote Web Development Internship at Codveda Technologies.

The frontend is built with React and demonstrates real-world authentication flows, including user registration, login, logout and access to protected routes. The application communicates with a REST API backend and handles authentication using JWT stored in httpOnly cookies.

## Project Scope

This project was designed and implemented entirely by me, from frontend user interfaces to backend API integration and deployment.

## Features

- User registration with form validation
- User login with JWT-based authentication
- Secure session handling via httpOnly cookies
- Logout functionality
- Protected frontend routes accessible only to authenticated users
- Authenticated user data retrieval
- Integration with a REST API backend

## Frontend Implementation

- React-based authentication forms
- Client-side state management for authentication status
- Protected routes based on user authentication
- API communication using the Fetch API
- Responsive UI built with custom CSS


## Architecture

- Frontend: React + Vite
- Backend: Node.js + Express (separate repository)
- Authentication: JWT stored in httpOnly cookies
- Communication: REST API
- Database: MongoDB (handled by backend)
  
## Tech Stack

### Frontend

- React
- Vite
- JavaScript (ES Modules)
- CSS (custom styling and responsiveness)
- gh-pages (deployment)


## Live Demo
Frontend:  
https://d00055a.github.io/user-authentication-system

Backend API:  
https://user-authentication-backend-3dvc.onrender.com


> Note: The backend is hosted on Render (free tier), so the first request may take up to one minute to respond.


### Frontend Setup

```bash
git clone https://github.com/d00055a/user-authentication-system.git
cd user-authentication-system
npm install
```
 
**Install dependencies**

   ```bash
   npm install
   ```

- Create a **.env** file in the root directory:

   ```Env
   VITE_API_URL=http://localhost:4000
   ```
- Run the development server:

   ```bash
   npm run dev
   ```
   
- Open in browser:
  
  ```arduino
  http://localhost:5173
  ```


## Deploy to GitHub Pages

- Update **.env** with the production backend URL:
   
   ```Env
   VITE_API_URL=https://user-authentication-backend-3dvc.onrender.com
   ```

- Build and deploy:

   ```bash
   npm run deploy
   ```   


## Purpose

This project was built to demonstrate:

- Frontend authentication flows in React

- Secure handling of user sessions

- Integration between frontend and backend services

- Real-world deployment and environment configuration


   



