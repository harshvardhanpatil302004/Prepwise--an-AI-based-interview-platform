<div align="center">
 <h1>Welcome to Prepwise</h1>
  
  <div>
    <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="next.js" />
    <img src="https://img.shields.io/badge/-Vapi-white?style=for-the-badge&color=5dfeca" alt="vapi" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=DD2C00" alt="firebase" />
  </div>

  <h3 align="center">Prepwise: A job interview preparation platform powered by Vapi AI Voice agents</h3>

   <div align="center">
    Prepwise is a modern web application that simulates job interviews using Vapi AI voice agents and Google Gemini. Built with Next.js, Firebase, and Tailwind CSS, it enables users to practice interviews, get real-time feedback, and track their progress—all in one sleek platform.
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)



## <a name="introduction">🤖 Introduction</a>

🛠️ How It Works

Here’s a simple breakdown of how Prepwise functions:

1. **User Sign Up/Login**
   - Users create an account or log in using email/password (via Firebase).

2. **Create an Interview**
   - Once logged in, users can initiate an interview session.
   - The system uses **Google Gemini** to generate tailored interview questions based on job roles.

3. **Interview Simulation**
   - A **Vapi AI voice agent** conducts the interview by asking the generated questions.
   - Users respond via voice, creating a conversational experience.

4. **Real-time Feedback**
   - The system captures responses and uses AI to analyze them.
   - Instant feedback is shown on a **Feedback Page**, along with transcripts and suggestions.

5. **Interview Dashboard**
   - Users can view past interviews, access transcripts, and monitor progress.




## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Firebase
- Tailwind CSS
- Vapi AI
- shadcn/ui
- Google Gemini
- Zod

## <a name="features">🔋 Features</a>

👉 **Authentication**: Sign Up and Sign In using password/email authentication handled by Firebase.

👉 **Create Interviews**: Easily generate job interviews with help of Vapi voice assistants and Google Gemini.

👉 **Get feedback from AI**: Take the interview with AI voice agent, and receive instant feedback based on your conversation.

👉 **Modern UI/UX**: A sleek and user-friendly interface designed for a great experience.

👉 **Interview Page**: Conduct AI-driven interviews with real-time feedback and detailed transcripts.

👉 **Dashboard**: Manage and track all your interviews with easy navigation.

👉 **Responsiveness**: Fully responsive design that works seamlessly across devices.

and many more, including code architecture and reusability

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)


**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Replace the placeholder values with your actual Firebase and Vapi credentials.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

🧠 Learnings & Goals
Through this project, I learned:

How to integrate real-time voice AI into web apps using Vapi

How to work with Google Gemini APIs for NLP feedback

How to manage auth and storage using Firebase

How to structure scalable Next.js projects with clean architecture

How to build responsive and sleek UIs with TailwindCSS and shadcn/ui

This project was a fun and impactful way to explore the intersection of AI and web development.