# -NEXUS-Business-Command-Center-Job-Platform
NEXUS is an all-in-one web application that serves two roles: Business Owners who need to manage their company operations, and Job Seekers who are looking for real employment opportunities — all within a single, unified dashboard.
What It Does

For Business Owners:

Client Management — Track contacts, companies, status, and deal values
Invoicing — Create, edit, and preview professional invoices with line items
Task Board — Kanban-style task management (To Do, In Progress, Done)
Finance Tracker — Log income and expenses, view net balance
Notes — Quick categorized notes for meetings, ideas, and general reference
Job Posting — Post open positions with title, description, requirements, type, and location
Applicant Tracking — Review applicants, view their full profile and resume, and update hiring status (Applied → Reviewing → Interview → Hired / Rejected)

For Job Seekers:

Real Job Search — Browse live, real job listings fetched from Remotive and Jobicy APIs. Search by keyword and click through to apply on the actual job platform
Local NEXUS Jobs — Apply to jobs posted by NEXUS business owners directly within the platform using your saved profile and resume
Profile & Resume Builder — Build a professional profile with contact info, summary, skills, work experience, education, and upload or paste your full resume
Application Tracker — Monitor the status of every application you've submitted (Applied, Reviewing, Interview, Hired, Rejected)

How the Hiring Flow Works

1.A business owner posts a job on NEXUS
2.A job seeker fills out their profile and uploads/pastes their resume
3.The seeker clicks "Apply with My Resume" on a job listing
4.A snapshot of their entire profile and resume is attached to the application
5.The employer sees the applicant in their Applicants panel with full access to the profile, skills, resume text, and experience
6.The employer updates the status — the seeker sees the update in real time

Technical Details

Single HTML file — No build tools, no dependencies, no server required
Pure vanilla JavaScript — Zero frameworks, zero libraries
localStorage-based — All data persists in the browser
Real API integration — Fetches live job data from Remotive and Jobicy REST APIs
Hashed passwords — Double-hashed with email-based salting
Account lockout — 5 failed attempts triggers a 15-minute cooldown
Data export/import — Full JSON backup and restore capability
Responsive design — Works on desktop and mobile with a collapsible sidebar
Dark theme — Gold-accented UI with smooth animations and transitions

Aesthetic Direction

NEXUS uses a refined dark editorial aesthetic — deep charcoal backgrounds, gold accent (#c9a54a), Syne for headings and UI elements, Crimson Pro for body text. The design features subtle radial gradients, staggered fade-in animations, hover micro-interactions, and a clean information hierarchy inspired by high-end financial dashboards.
