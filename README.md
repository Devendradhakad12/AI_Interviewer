# 🖱️ NeuraView: The AI Interviewer

This is the high-performance Next.js 14 frontend for **NeuraView**, an AI-powered mock interview and career preparation platform. It uses React's modern patterns, cinematic animations (Framer Motion), and sophisticated integrations (Sarvam AI, Face Mesh) to provide a premium user experience.

---

## ✨ Features Spotlight

- **🎙️ Real-time Voice Interaction**: Optimized Gemini Live AI streaming STT/TTS with ultra-low latency (<1.2s lag).
- **👁️ Face Mesh Analysis**: On-device facial expression analysis using mediapipe face mesh for behavioral cues.
- **📄 Document Intelligence UI**: Sleek interfaces for uploading, processing, and interacting with AI-parsed resumes.
- **📊 Interactive Analytics**: High-quality data visualization for interview reports using Recharts.

---

## 🛠 Frontend Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion + Motion One
- **UI Components**: Shadcn/UI (Radix UI)
- **AI Clients**: Sarvam AI SDK, Gemini Live LLM
- **Auth**: NextAuth.js
- **Icons**: Lucide-React + Tabler Icons

---

## 🚦 Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Environment Setup
Create a `.env.local` file in this directory and populate it with your API keys:

```env
# Databse URI
MONGODB_URI=mongodb+srv://dhakaddhakad1742_db_user:Jab2WCl6S8qSR4On@aiinterviewer.yaasror.mongodb.net/?appName=AiInterviewer

# AI API Keys
NEXT_PUBLIC_GEMINI_API_KEY=
GEMINI_API_KEY=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
NEXT_PUBLIC_SARVAM_API_KEY= 
SARVAM_API_KEY=

# Auth
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000
SITE_BASE_URL=https://localhost:3000
NEXT_PUBLIC_SITE_URL=https://localhost:3000
```

### 3. Run Development Server
```bash
npm run dev
```

---

## 🏗 Key Components Architecture

- **`components/Orb.tsx`**: High-performance AI interaction visualizer.
- **`components/video-preview.tsx`**: Real-time camera capture + Face Mesh analytics processing.
- **`app/interview/[id]/useSarvamStreamingTTS.ts`**: Custom hook for low-latency audio streaming logic.
- **`app/api/interview/report/route.ts`**: Server-side report orchestration using Pollinations AI.

---

## 🛣 Roadmap & Extensions
Check out `EXTENSIONS.md` for ideas on how to extend the technical features of the NeuraView frontend.

---

Created with ❤️ by **Team Limitless**.

