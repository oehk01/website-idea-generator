# Website Idea Generator

AI-first full-stack prototype that lets a user submit a website idea and returns generated section outlines.  
Tech: Next.js (frontend), NestJS (backend), MongoDB, with AI (mock or OpenAI) driving section generation.

## Demo
Short Loom walkthrough (3–4 min): <https://www.loom.com/share/bc77c6a59c4544d58bc2bddeeb3567bb?sid=9200acfb-c635-4912-8afd-105d1d7d424f>

## Features
- Prompt input form in Next.js
- AI-generated dummy sections (or real OpenAI if enabled)
- Persistence layer via MongoDB
- Client-side date formatting to avoid hydration mismatch
- Loading spinner & error handling for UX feedback
- Mock AI mode to avoid quota/billing issues during development

## Setup

### Prerequisites
- Node.js v18+
- MongoDB running locally (default URI: `mongodb://localhost:27017`)

### Backend

```bash
cd backend
npm install
