# 🚀 BridgeUP AI
# Dual-Portal AI-Powered Career Platform for Students & Recruiters

# BridgeUP AI is a full-stack career ecosystem where:
# - Students build verified skill-based profiles
# - Recruiters discover top candidates using AI & credit-based ranking
# - Both sides meet on a real-time, data-driven talent marketplace

# 🌐 Live Experience
# Glassmorphic Dual-Login → Student Portal → Recruiter Portal
# Built for universities, bootcamps, and modern hiring teams

# 🧠 Core Philosophy
# "Stop hiring based on resumes. Start hiring based on proof."

# 🏗️ System Architecture
# Frontend:
#   - Next.js 14 (App Router)
#   - TailwindCSS + Glassmorphism UI
#   - Drag & Drop (Kanban, Gallery)
#   - Bento Grid Layouts
#
# Backend:
#   - Supabase (Postgres + Auth + Storage)
#   - Edge Functions (AI Scheduler)
#   - Role-based Access Control
#
# AI Layer:
#   - 7-Day Interview Prep Generator
#   - Resume → Skill → Schedule Engine
#   - Fallback logic for API safety

# 🔐 Authentication System
# Dual-Portal Glassmorphic Login
# - Student / Recruiter Toggle
# - Email or Phone login
# - Google OAuth
# - GitHub OAuth
# Users table is role-aware:
#   users.role = "student" | "recruiter"

# 🎓 Student Portal
# Sidebar Modules
# - Internship Tracker (Kanban Board)
# - Skill Library (15 University-Aligned Courses)
# - Unified Calendar
# - Proof Gallery
# - Certificate Vault
# - Mentor Connect
# - Profile Editor (with Recruiter Preview)

# Internship Tracker
# Kanban Columns:
#   Applied → Interview → Offer → Rejected
# Drag & Drop powered by database sync

# Skill Library
# - 15 curated courses
# - University aligned
# - Tracks skill acquisition in student_courses

# Unified Calendar
# Stores:
#   - Exams
#   - Hackathons
#   - Internship deadlines
#   - Mentor sessions

# Proof Gallery
# Upload:
#   - Project images
#   - Contribution summary
# Stored in:
#   projects
#   project_images

# Certificate Vault
# - Upload PDFs / Images
# - Full-screen preview
# - Stored in Supabase Storage

# Mentor Connect
# - Book real mentors
# - 200-character agenda required
# - Stored in mentor_bookings

# Profile Editor
# Features:
# - Avatar upload (max 5MB)
# - Name / University / Bio (500 chars)
# - Social Links:
#     GitHub
#     LinkedIn
#     LeetCode
#     GeeksForGeeks
# - Real-time Recruiter Preview
# - Edit / Preview toggle
# - Save confirmation feedback

# 🧑‍💼 Recruiter Portal
# Recruiters use credits to:
# - Search candidates
# - Unlock profiles
# - Rank top talent

# Candidate Search
# Filters:
#   - Skills
#   - Courses
#   - Project tags
#   - Certificates

# Bento Grid Profiles
# Each candidate shows:
#   - Avatar
#   - Skills
#   - GitHub / LinkedIn / LeetCode
#   - Certificates
#   - Projects
#   - Tags:
#       Paid
#       Unpaid
#       Collaborative

# Locked profiles require credits

# 🧠 AI Interview Prep Engine
# Edge Function:
# - Generates a 7-day interview prep plan
# - Based on:
#     Skills
#     Courses
#     Target role
# - Includes fallback logic if AI fails

# 🗃 Database Schema
# Tables:
# - users
# - courses
# - student_courses
# - applications
# - projects
# - project_images
# - certificates
# - calendar_events
# - mentors
# - mentor_bookings

# 🧪 Seed Data
# Preloaded:
# - 15 courses
# - 6 mentors
# - 8 students
# - Projects + certificates

# 🧰 Setup Instructions
git clone https://github.com/your-org/bridgeup-ai.git
cd bridgeup-ai
npm install

# Create .env.local
# Add:
# NEXT_PUBLIC_SUPABASE_URL=
# NEXT_PUBLIC_SUPABASE_ANON_KEY=
# OPENAI_API_KEY=

npm run dev

# 🚀 Deployment
# Frontend:
# - Vercel
# Backend:
# - Supabase
# AI:
# - Supabase Edge Functions

# 🏆 Why BridgeUP AI Wins
# Students:
# - Build proof-based career profiles
# - Prepare with AI
# - Show real skills
#
# Recruiters:
# - No resume spam
# - Filter by verified data
# - Pay only for high-quality leads

# 🔥 BridgeUP AI
# Where Talent Meets Truth
