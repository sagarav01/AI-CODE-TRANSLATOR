# AI Code Translator (Starter)

**Description**
A starter Next.js project that demonstrates an AI-powered code translation tool.  
It uses a Next.js frontend + API route to proxy requests to an AI model (e.g., Gemini). Firebase setup is included as a placeholder for auth/storage. Tailwind CSS is used for styling.

**What is included**
- Next.js pages (index and API route)
- Simple code editor UI component
- Placeholder Gemini API integration (utils/gemini.js)
- Firebase init (utils/firebase.js)
- Tailwind CSS config and global styles

**How to run locally**
1. Install dependencies:
```bash
npm install
```
2. Add environment variables to `.env.local`:
```
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_PROJECT_ID=your_project_id
GEMINI_API_KEY=your_gemini_api_key_or_placeholder
```
3. Run dev server:
```bash
npm run dev
```
4. Open http://localhost:3000

**Notes**
- The Gemini integration in `utils/gemini.js` contains an example fetch payload. Replace with your real model endpoint and API key.
- This project is a starter template; adjust and secure secrets before deploying.

