## Full-Stack CRUD Notes Application (MERN) (Lab 17.2 - Full-Stack Deployment)

## Author

**Dewan Mahmud**  
Full-Stack Software Engineer | MERN Stack

- Website: https://dewantech.com
- GitHub: https://github.com/DewanTechUS
- LinkedIn: https://www.linkedin.com/in/dewan-mahmud-a579a0265/

## Note

For this project, I separated the frontend and backend into two repositories to mirror real-world full-stack deployment.

Each application is deployed independently on Render.
Both live links together represent the complete full-stack project.

## Links

**Frontend**

- GitHub: https://github.com/DewanTechUS/Lab_17.2_Frontend_Full-Stack_CRUD_Notes_API
- Live: https://lab-17-2-frontend-full-stack-crud-notes.onrender.com

**Backend**

- GitHub: https://github.com/DewanTechUS/Lab_17.2_Backend_Full-Stack_CRUD_Notes_API
- Live: https://lab-17-2-backend-full-stack-crud-notes.onrender.com

# Project Overview

This is a full-stack CRUD Notes application built with the MERN stack.
The project is split into two separate repositories (frontend & backend) to follow real-world production practices and improve maintainability.
The frontend is a modern React application, while the backend is a RESTful API built with Node.js, Express, and MongoDB.

## Architecture

- Frontend: React + Vite
- Backend: Node.js + Express + MongoDB
- Communication: REST API (/api/notes)
- Deployment: Render (frontend & backend deployed separately)

# Backend - Full-Stack CRUD Notes API

### Features

- Full CRUD operations (Create, Read, Update, Delete)
- MongoDB database integration using Mongoose
- Express routers and controllers
- Environment-based configuration
- CORS enabled for frontend communication
- Clean RESTful API design

### Technology Used (Backend)

- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- cors

### API Endpoints

- GET /api/notes - Get all notes
- POST /api/notes - Create a note
- GET /api/notes/:id - Get a single note
- PUT /api/notes/:id - Update a note
- DELETE /api/notes/:id - Delete a note

### Environment Variables (Backend)

## Create a .env file in the backend root:

PORT=3000
MONGO_URI=your_mongodb_connection_string
CLIENT_ORIGIN=http://localhost:3001

## Running the Backend Locally

- npm install express mongoose cors dotenv
- npm install -D nodemon
- npm run dev

## Backend runs at:

- http://localhost:3000

# Frontend - Full-Stack CRUD Notes Application

### Features

- View all notes from the backend
- Create, edit, and delete notes
- Clean and responsive UI
- Dark mode and light mode toggle
- Background video with sound control
- Graceful API error handling
- Clear separation of UI and data logic

### Technology Used (Frontend)

- React
- Vite
- JavaScript (ES6+)
- HTML5
- CSS3

### Environment Variables (Frontend)

- Create a .env file in the frontend root:
- VITE_API_URL=http://localhost:3000

# Running the Frontend Locally

- npm install react react-dom react-router-dom
- npm install -D vite @vitejs/plugin-react-swc
- npm run dev

# Frontend runs at:

http://localhost:3001

## Reflection

I built this project while actively working to strengthen my resume and improve my full-stack development skills.
One of the biggest challenges was correctly connecting the frontend and backend—especially handling CORS, environment variables, and API responses across local and deployed environments. Debugging these issues helped me clearly understand how data flows between a React frontend and an Express backend.
Separating the frontend and backend into two repositories made debugging significantly easier and mirrored real-world production workflows. React’s component-based structure allowed me to isolate UI issues quickly, while Express controllers kept backend logic clean and maintainable.
Overall, this project helped solidify my understanding of full-stack architecture, deployment, and debugging in a real environment.

## Special Thanks

Special thanks to my instructors, mentors, and learning community for their guidance, feedback, and support throughout this project. Their help played a major role in improving both my technical skills and confidence as a full-stack developer.
