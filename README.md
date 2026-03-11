✨ Full Stack Realtime Chat App ✨

A modern real-time chat application built with the MERN stack, Socket.io, and TailwindCSS.
This app supports authentication, real-time messaging, online status, and demonstrates professional full-stack deployment.


🌐 Demo & Tutorial
<a href="https://chat-app-kjtt.onrender.com/" target="_blank">
  <img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/b21d0d67-ceb8-4705-922c-4afaad7f3088" />

</a>

🔥 Highlights

- MERN stack full-stack development

- Real-time communication with Socket.io

- JWT authentication & secure routes

- Global state management with Zustand

- Error handling & logging

- Full-stack deployment with Render



🧪 Environment Variables (.env)
- Backend (/backend/.env)
| Variable              | Description                                      |
| --------------------- | ------------------------------------------------ |
| MONGODB_URI           | MongoDB connection string                        |
| PORT                  | Server port (default: 5001)                      |
| JWT_SECRET            | Secret key for JWT authentication                |
| CLOUDINARY_CLOUD_NAME | Cloudinary account name for file uploads         |
| CLOUDINARY_API_KEY    | Cloudinary API key                               |
| CLOUDINARY_API_SECRET | Cloudinary API secret                            |
| NODE_ENV              | Environment mode (`development` or `production`) |

- MONGODB_URI=your_mongodb_uri
- PORT=5001
- JWT_SECRET=your_jwt_secret

- CLOUDINARY_CLOUD_NAME=your_cloud_name
- CLOUDINARY_API_KEY=your_api_key
- CLOUDINARY_API_SECRET=your_api_secret

- NODE_ENV=development

📂 Project Structure
| Folder / File              | Description                         |
| -------------------------- | ----------------------------------- |
| **frontend/**              | React frontend                      |
| `frontend/src/`            | Source files                        |
| `frontend/src/components/` | React components                    |
| `frontend/src/pages/`      | Application pages                   |
| `frontend/src/styles/`     | TailwindCSS styles                  |
| `frontend/public/`         | Public assets (images, icons)       |
| `frontend/package.json`    | Frontend dependencies & scripts     |
| **backend/**               | Express backend                     |
| `backend/config/`          | DB, JWT, and other configuration    |
| `backend/controllers/`     | API controllers / logic             |
| `backend/middleware/`      | Auth, error handling, rate limiting |
| `backend/models/`          | Mongoose models / schemas           |
| `backend/routes/`          | API routes                          |
| `backend/server.js`        | Backend entry point                 |
| `package.json`             | Root scripts for build & start      |
| **README.md**              | Project documentation               |


⚙️ Build & Run
Install Dependencies
- npm install --prefix backend
- npm install --prefix frontend

- Build the App (Frontend & Backend)
- npm run build
- ("scripts": {
  "build": "npm install --prefix backend && npm install --prefix frontend && npm run build --prefix frontend",
  "start": "npm run start --prefix backend"

}
- npm start


🚀 Deployment

- Frontend & Backend: Deployed on Render

- Database: MongoDB Atlas

- File Storage: Cloudinary ( images )





