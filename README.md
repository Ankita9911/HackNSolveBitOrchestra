🧠 FinVerse - GenAI-Powered Financial Assistant
Empowering every investor with knowledge—one intelligent conversation at a time.

📌 Table of Contents
About the Project
Problem Statement
Solution Overview
Key Features
How It Works
Tech Stack
Architecture & Process Flow
Contributing
License
Contact
📖 About the Project
FinVerse is a GenAI-powered financial assistant designed to bridge the gap in financial literacy and empower retail investors in India. It integrates conversational AI, smart planning tools, and educational content into a unified platform to help users make better financial decisions.

❗ Problem Statement
Financial literacy in India is only 27%, yet retail investors have grown to over 10 crore in the past 4 years.

Most new investors lack access to quality education or financial advisors and depend on hearsay, leading to poor financial decisions. Manual education methods cannot scale. Only AI can meet this growing demand.

💡 Solution Overview
FinVerse Demo

FinVerse provides a personal AI assistant for finance that helps users:

Ask simple financial questions and receive understandable answers
Discover suitable investment opportunities
Plan their finances interactively
Stay informed and secure through alerts and real-time tips
It empowers users to take full control of their finances from one integrated platform.

🌟 Key Features
✅ AI-Powered Chatbot (Gemini Pro API)
📈 Personalized Investment Recommendations
📊 Expense & Budget Tracking
🧾 Receipt Scanning for Auto-Tracking
🎓 Integrated Financial Education (YouTube API)
🔒 Scam & Fraud Alert System
📉 Tax-Saving Insights and Budget Optimization
🗂️ Unified Dashboard for Financial Overview
⚙️ How It Works
User signs up using Clerk Authentication
Asks questions via the AI chatbot (Gemini Pro)
Scans receipts or enters transactions
Receives AI insights for investments, saving, and budgeting
Learns on the go through contextual educational content
Platform provides actionable suggestions via FAISS-powered search
🧪 Tech Stack
Frontend
React 19
Next.js 15
Tailwind CSS
ShadCN UI
Backend
Quart (Async Python)
Supabase (Realtime DB & Auth)
Prisma ORM
Clerk (User Auth)
Arcjet (API Security & Performance)
Inngest (Background Tasks)
AI & Data
Gemini Pro API
FAISS Vector Search
crawl4ai (Web Scraping)
Custom Data Pipelines
Media & Learning
YouTube API
Jinja2 Templating
🧭 Architecture & Process Flow
User → Auth (Clerk) → AI Chatbot → 
→ Gemini API → Financial Engine →
→ FAISS Vector Store → Supabase DB →
→ Recommendation + Education Layer →
→ UI Dashboard (React + Next.js)

 
 
