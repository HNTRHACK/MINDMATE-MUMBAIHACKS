MindMate – Mental Wellness Platform (Locally Hosted)

This project is a full-stack mental wellness platform that helps users take assessments, join community chats, talk to an AI assistant, and book counseling sessions.

The project is fully locally hosted, meaning it runs on your computer only and is not deployed online.

The frontend uses React, TypeScript, Vite, TailwindCSS, Motion animations, and Lucide icons.

The backend uses Node.js, Express.js, MongoDB Atlas, JWT authentication, Nodemailer for emails, and the Relevance API for AI chat.

Features include PHQ-9 and GAD-7 assessments, animated dashboard, community group chat, AI mental health assistant, online/offline counseling session booking, Google Meet link generation, and email confirmations.

To run the frontend:

Open terminal in the main project folder

Run: npm install

Run: npm run dev

The site opens at: http://localhost:5173

To run the backend:

Open terminal inside backend folder

Run: npm install

Run: npm run dev

Backend runs at: http://localhost:5000

Required .env file inside the backend folder must include:

PORT=5000

MONGO_URL=your_mongo_atlas_link

JWT_SECRET=your_secret

RELEVANCE_API_KEY=your_api_key

EMAIL_USER=your_email

EMAIL_PASS=your_app_password

All main features (community, booking, AI chat, assessments) work locally when both frontend and backend servers are running.

This project is intended for hackathons and demonstrations, not for real medical use.

Designed and developed by you for showcasing mental health support tools.
