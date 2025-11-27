📊 Project Management Dashboard

A modern, minimal, and scalable project management dashboard built with Next.js 14, TypeScript, and Tailwind CSS, designed to manage tasks, priorities, and projects efficiently.
Backend (PostgreSQL + Prisma) integration is currently in progress.


🚀 Features (Completed)
	✔️ Responsive Navbar
	✔️ Sidebar with:
	✔️ Project list
	✔️ Priority levels section
	✔️ Clean UI built with Tailwind CSS
	✔️ Optimized folder structure
	✔️ Client-side routing setup
	✔️ Next.js app directory structure


🛠️ Features In Progress
	🔄 Setting up PostgreSQL + Prisma backend
	🔄 API Routes for Projects & Tasks
	🔄 Database schema design
	🔄 Task CRUD operations
	🔄 Project overview dashboard
	🔄 Role-based access (future)


📌 Upcoming Roadmap
	1.	Prisma schema for projects, tasks, and users
	2.	Connect to PostgreSQL (local → hosted)
	3.	Build CRUD APIs using Next.js Route Handlers
	4.	Create full Dashboard UI:
	   • Task board
	   • Filter/sort
	   • Priority labels
	   • Project activity logs
	5.	Add authentication (NextAuth)
	6.	Add analytics section (charts)
	7.	Deploy project

🧰 Technology Stack 

Frontend
	•	Next.js 14 (App Router) – Modern React framework with server components
	•	TypeScript – Strongly typed, scalable development
	•	Tailwind CSS – Utility-first, responsive UI styling
	•	Redux Toolkit + RTK Query – Predictable state management and optimized API caching
	•	Material UI Data Grid – High-performance table and data visualization components


Backend
	•	Node.js + Express – Scalable REST API backend
	•	Prisma ORM (PostgreSQL) – Type-safe database access and schema management
	•	PostgreSQL – Reliable relational database
	•	PgAdmin – GUI for database monitoring and management


Cloud & DevOps (AWS)
	•	AWS EC2 – Backend hosting with secure VM environment
	•	AWS RDS (PostgreSQL) – Managed database with automated backups and scaling
	•	AWS S3 – Object storage for static assets & uploads
	•	AWS Amplify – Frontend deployment and CI/CD
	•	AWS API Gateway – Routing and managing backend API endpoints
	•	AWS Lambda – Serverless functions for event-driven features
	•	AWS Cognito – User authentication and secure identity management


▶️ Getting Started
1. Clone Repository
git clone https://github.com/kannanpathania11/Project-Management-Dashboard.git
cd Project-Management-Dashboard/client

2. Install Dependencies
npm install

3. Run Dev Server
npm run dev

Open:
http://localhost:3000

🏗️ Backend Setup (Work in Progress)
1. Run Prisma Init
npx prisma init

2. Environment Variables
Create .env:
DATABASE_URL="postgresql://user:password@localhost:5432/dashboard"

Generate Prisma Client:
npx prisma generate

📌 Status

This project is actively under development.
Core UI features like the navbar + sidebar are complete.
Backend (PostgreSQL + Prisma) integration is being built module-by-module.

