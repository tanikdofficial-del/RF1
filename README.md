# Royal Feast - Premium Food Brand Website

This is a high-performance, premium food brand website built with Next.js 14, React, TypeScript, and TailwindCSS.

## 🚀 How to Run and Preview

To see the website in action, follow these steps:

### 1. Install Node.js
If you don't have Node.js installed, download and install the **LTS version** from [nodejs.org](https://nodejs.org/). This will also install `npm`.

### 2. Install Dependencies
Open your terminal (Command Prompt, PowerShell, or VS Code Terminal) in the project folder and run:
```bash
npm install
```

### 3. Set Up Environment Variables
Rename the `.env.local.example` file to `.env.local`:
```bash
cp .env.local.example .env.local
```
*(Optional: Add your own Firebase credentials and Stripe keys if you want to test the full auth and checkout flow)*

### 4. Run Development Server
Start the project locally by running:
```bash
npm run dev
```

### 5. Preview the Site
Once the server starts, open your browser and go to:
**[http://localhost:3000](http://localhost:3000)**

---

## ✨ Features
- **Next.js 14 App Router** for optimized performance.
- **GSAP ScrollTrigger** for smooth horizontal scrolling in the Food Showcase.
- **Three.js** for the interactive particle background in the Hero section.
- **Framer Motion** for premium micro-animations.
- **Firebase Auth & Firestore** for user accounts and contact messaging.
- **Responsive Design**: Mobile-first and fully optimized for all screens.
- **Luxury Aesthetic**: Curated gold-on-black theme with high-end typography.

## 🛠 Tech Stack
- **Framework**: Next.js 14
- **Styling**: TailwindCSS
- **Animations**: GSAP, Framer Motion
- **3D Effects**: Three.js
- **Backend**: Firebase
- **Language**: TypeScript

---

## 🏗 Deployment
To deploy this for production (to get a live URL):
1. Push this code to a **GitHub** repository.
2. Connect your repository to **[Vercel](https://vercel.com/)**.
3. Vercel will automatically detect Next.js and deploy your site to a public URL.
