AI-Financial-SAAS-Platform
 

An advanced AI-powered Financial SaaS platform built with the MERN stack (MongoDB, Express, React, Node.js).  
This project demonstrates a scalable fintech SaaS application with modern technologies, real-time analytics, subscription billing, and intelligent insights.  


-> Features  
   Authentication & Authorization – Secure login with JWT & OAuth  
   AI-driven Analytics – Smart financial insights & predictions   
   User Dashboard – Personalized account management  
   Real-Time Reports – Live transaction and portfolio tracking  
   SaaS Ready – Multi-tenant and scalable architecture  
   MERN Performance – Optimized backend and frontend workflow  


-> Tech Stack  
   Frontend: React, Redux, TailwindCSS  
   Backend: Node.js, Express.js  
   Database: MongoDB (Mongoose ODM)  
   Authentication: JWT, OAuth   
   AI/ML: TensorFlow.js / OpenAI API (for insights & predictions)  
   Deployment: Vercel  



-> Installation & Setup  

Clone the repository:  
git clone https://github.com/dhanrajsingh16/ai-financial-saas

-> Backend Setup
   Copy code
   cd backend
   npm install
   npm run dev

-> Frontend Setup
   Copy code
   cd frontend
   npm install
   npm start
   Environment Variables
   Create a .env file in both backend and frontend with the following:

Backend (/backend/.env)

  ini
  Copy code
  
  PORT=5000
  
  MONGO_URI=your_mongodb_connection
  
  JWT_SECRET=your_jwt_secret
  
  STRIPE_SECRET_KEY=your_stripe_key
  
  OPENAI_API_KEY=your_openai_key   # if using AI API
  
  Frontend (/frontend/.env)

  ini
  Copy code
  REACT_APP_API_URL=http://localhost:5000


  Author

  Dhanraj Singh
