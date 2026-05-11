🚀 AI Interview Preparation System

An AI-powered interview preparation platform that helps students and job seekers improve their technical and HR interview skills through intelligent question generation, resume analysis, analytics, and personalized feedback.

📌 Features
👤 Authentication
User Signup & Login
JWT Authentication
Secure Password Hashing
Protected Routes
📄 Resume Analyzer
Upload Resume (PDF/DOCX)
Automatic Skill Extraction
ATS Score Analysis
Resume Evaluation
🤖 AI Interview Generator
HR Questions
Technical Questions
Aptitude Questions
Skill-Based Interview Generation
📊 Analytics Dashboard
Performance Tracking
Interview History
Score Visualization
Progress Monitoring
🧠 AI Feedback System
Answer Evaluation
Confidence Analysis
Communication Scoring
Improvement Suggestions
📥 PDF Report Generation
Download Interview Reports
AI Feedback Summary
Performance Analytics
🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
Framer Motion
Axios
React Router DOM
Backend
Node.js
Express.js
MongoDB
JWT Authentication
Multer
AI Integration
OpenAI API
Deployment
Vercel
Render
MongoDB Atlas
📂 Folder Structure
ai-interview-prep-system/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── context/
│   │   ├── App.jsx
│   │   └── main.jsx
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── README.md
├── package.json
└── .env
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/yourusername/ai-interview-prep-system.git
cd ai-interview-prep-system
2️⃣ Frontend Setup
cd client
npm install
npm run dev
3️⃣ Backend Setup
cd server
npm install
npm run server
🔑 Environment Variables

Create a .env file inside the server folder and add the following:

PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_openai_api_key
📡 API Routes
Authentication Routes
Method	Endpoint	Description
POST	/api/auth/register	Register User
POST	/api/auth/login	Login User
Resume Routes
Method	Endpoint	Description
POST	/api/resume/upload	Upload Resume
Interview Routes
Method	Endpoint	Description
POST	/api/interview/generate	Generate Interview Questions
POST	/api/interview/submit	Submit Interview Answers
GET	/api/interview/history	Get Interview History
🖥️ Screenshots
🏠 Home Page

Add Screenshot Here

📊 Dashboard

Add Screenshot Here

📄 Resume Upload

Add Screenshot Here

🤖 AI Interview

Add Screenshot Here

🌟 Future Enhancements
🎤 Voice-Based Interviews
🤖 AI Avatar Interviewer
📹 Video Interview Analysis
🌍 Multi-Language Support
📱 Mobile App Version
📈 Project Highlights
✅ Full Stack MERN Application
✅ AI-Powered Features
✅ Resume Parsing System
✅ Analytics Dashboard
✅ Secure Authentication
✅ Professional UI Design
👨‍💻 Author
SANJAY

B.Tech Artificial Intelligence and Data Science Student
Frontend Developer | AI Enthusiast | MERN Stack Developer

📜 License

This project is licensed under the MIT License.

⭐ Support

If you like this project, give it a ⭐ on GitHub!
