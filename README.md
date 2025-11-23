# StudyFriendly ✨

**The gamified flashcard app that makes learning languages & skills feel like playing a game.**

A beautiful, modern, and completely open-source flashcard experience built for real learners who are tired of boring memorization tools.

StudyFriendly turns studying into an addictive game: flip cards → earn XP → level up → unlock new categories → watch your progress grow — all wrapped in a sleek dark cyberpunk/neon interface that looks incredible on any device.

![StudyFriendly Preview](https://imgur.com/a/8ZveilA) *(add your own screenshot later)*

### Features
- **Gamification that actually works** — +15 XP for mastering cards, +5 XP for practice. Level up every 100 XP.
- **15+ real-world categories** — Travel, Interview, Daily Speaking, Workplace, Shopping, Food, Grammar, Academic English, Phone Calls, Directions, Email Writing, Slang, School, Malaysian Manglish, and more.
- **Malaysian Manglish deck** — The first flashcard app with a full Manglish category. Lah, so shiok one!
- **Smart progression** — Cards move between Easy → Normal → Hard based on your performance (Spaced Repetition lite).
- **Persistent progress** — XP, levels, and mastered cards saved forever in localStorage (no login required).
- **Built-in AI Support Chat** — Stuck? Click the glowing cyan button and chat with your personal AI tutor (powered by GPT-4o-mini). It knows everything about the app and gives friendly, encouraging answers.
- **Stunning dark + neon design** — Obsidian black background, glowing cyan accents, smooth animations, custom scrollbars.
- **Fully responsive** — Perfect on mobile, tablet, and desktop.
- **Zero backend needed** (except optional AI chat via Vercel serverless).

### Tech Stack
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- shadcn/ui + Radix UI
- Vercel AI SDK (streaming chat)
- Lucide Icons
- localStorage persistence

### Live Demo
https://studyfriendly.vercel.app

### How to Run Locally (super easy)

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/StudyFriendly.git
cd StudyFriendly

# 2. Install dependencies
npm install
# or
yarn install
# or
pnpm install

# 3. Run the development server
npm run dev
# or
yarn dev
# or
pnpm dev

# Open http://localhost:3000 in your browser
