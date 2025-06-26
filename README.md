<!-- markdownlint-disable MD033 -->
<h1 align="center">✨ HireTalk - Video Calling Interview Platform ✨</h1>

<p align="center">
  A powerful video calling platform designed specifically for remote interviews, built using modern web technologies.
</p>

## 🚀 Tech Stack

- **Frontend:** Next.js (App Router), React, TypeScript
- **Authentication:** Clerk (JWT-based Auth & Role-based Access Control)
- **Backend:** Convex (Real-time Backend as a Service)
- **Video SDK:** Stream (Video Calling, Recording, Screen Sharing)
- **Styling:** Tailwind CSS & Shadcn UI
- **Others:** Server Components, Server Actions, Dynamic & Static Routing

---

## 🎯 Features

- 🎥 **1-on-1 & Group Video Calls**
- 🖥️ **Screen Sharing**
- 🎬 **Screen Recording**
- 🔐 **Secure Authentication & Authorization**
- 📂 **Role Management for Interviewers & Candidates**
- 💬 **Real-time Communication Integration** (planned)
- 🎨 **Responsive UI** with modern design using Tailwind & Shadcn

---

## 🛠️ Environment Variables

Create a `.env` file in the root directory and add the following keys:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```

🚀 Getting Started
1 .Install dependencies
 npm install

2. Start the development server

    npm run dev