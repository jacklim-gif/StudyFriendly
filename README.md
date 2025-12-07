StudyFriendly ✨

A gamified, AI-assisted flashcard app that makes learning feel like playing a game — powered by a sleek cyberpunk/neon UI and IBM watsonx Orchestrate.

🚀 Overview

StudyFriendly transforms traditional flashcards into an addictive learning experience:

Flip cards → Earn XP → Level up → Unlock new categories → Master languages & skills

A fully open-source project designed for real learners who want a modern, fast, and engaging study tool.

👥 Contributors
Name	Role
Jack	Prototype Development, IBM watsonx Orchestrate
Xi Wen	Repository Setup & Management
Jason	LEAN Canvas, Presentation Slides, Dialogues

Want to contribute? PRs welcome!

✨ Features
🎮 Gamified Learning

+15 XP for mastering cards

+5 XP for practice

Level up every 100 XP

🌍 15+ Learning Categories

Travel, Interview, Daily Speaking, Workplace, Shopping, Food, Grammar, Slang, Academic English & more.

🇲🇾 Malaysian Manglish Deck

The first flashcard app with a complete Manglish deck:
“lah”, “meh”, “leh”, “so shiok”, etc.

🧠 Smart Progression

Cards automatically adjust difficulty using Spaced Repetition (lite).

🤖 AI Support Chat

Powered by GPT-4o-mini with Vercel AI SDK.
Learners get hints, explanations, and coaching on demand.

💾 Persistent Progress

All XP, levels, and mastered cards are stored in localStorage.
No backend needed. No login required.

🎨 Cyberpunk/Neon Interface

Obsidian dark theme

Glowing cyan effects

Smooth card animations

Custom scrollbars

📱 Fully Responsive

Perfect on mobile, tablet, and desktop.

🛠️ Tech Stack
Category	Technology
Framework	Next.js 14 (App Router)
Language	TypeScript
Styling	Tailwind CSS
UI Library	shadcn/ui + Radix UI
Icons	Lucide Icons
AI	Vercel AI SDK
Storage	localStorage
Automation	IBM watsonx Orchestrate
🔧 Installation
# 1. Clone the repository
git clone https://github.com/jacklim-gif/StudyFriendly.git
cd StudyFriendly

# 2. Install dependencies
npm install

# 3. Run the development server
npm run dev


Now open:

http://localhost:3000

📂 Project Structure
StudyFriendly/
│── app/              # Next.js app router pages
│── components/       # UI components
│── data/             # Decks & flashcard categories
│── public/           # Icons & assets
│── styles/           # Global styles
│── utils/            # XP system, AI helpers
│── ...

🧭 Future Improvements

Cloud sync (Supabase / Firebase)

User accounts

Leaderboards + streak system

Multiplayer quiz mode

Export/import deck feature

❤️ Support

If you like this project, please ⭐ the repo.
It helps more people discover it!
