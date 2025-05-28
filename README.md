git clone https://github.com/bhuvankattur16/todo-task-manager
cd todo-app
Backend Setup (/backend)
cd backend
npm install
touch .env
Add to .env:
PORT=5000
MONGO_URI=your-mongo-uri
Run the backend:
npm run dev
Frontend Setup (/frontend)
cd frontend
npm install
touch .env
Add to .env:
VITE_API_BASE_URL=https://your-backend-url.onrender.com/api
VITE_FIREBASE_API_KEY=your-key
VITE_FIREBASE_AUTH_DOMAIN=your-project.firebaseapp.com
Run the frontend:
npm run dev
