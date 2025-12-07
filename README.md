# StudyFriendly ✨
*A gamified, AI-assisted flashcard app that makes learning languages & skills feel like playing a game — powered by a sleek cyberpunk/neon UI and IBM watsonx Orchestrate.*

---

## 🚀 Overview
StudyFriendly transforms traditional flashcards into an addictive learning experience:

> Flip cards → Earn XP → Level up → Unlock new categories → Master languages & skills

Fully open-source and designed for learners who want a modern, fast, and engaging study tool.

---

## 👥 Contributors
| Name | Role |
|------|------|
| **[Jack](https://github.com/jacklim-gif)** | Prototype Development, IBM watsonx Orchestrate |
| **[Xi Wen](https://github.com/xiwen1212)** | Repository Setup & Management |
| **[Jason](https://github.com/jyhtonix)** | LEAN Canvas, Presentation Slides, Dialogues |

PRs and contributions are welcome!

---

## ✨ Features

### 🎮 Gamified Learning
- +15 XP for mastering cards  
- +5 XP for practice  
- Level up every 100 XP

### 🌍 15+ Learning Categories
Travel, Interview, Daily Speaking, Workplace, Shopping, Food, Grammar, Slang, Academic English & more.

### 🇲🇾 Malaysian Manglish Deck
The first flashcard app with a full Manglish category. “Lah, meh, leh” — so shiok!

### 🧠 Smart Progression
Cards adjust difficulty automatically using **Spaced Repetition (lite)**.

### 🤖 AI Support Chat
- Powered by **GPT-4o-mini** via Vercel AI SDK  
- Get hints, explanations, and tutoring anytime

### 💾 Persistent Progress
All XP, levels, and mastered cards are saved in `localStorage` — **no login required**.

### 🎨 Cyberpunk/Neon Interface
- Obsidian black background  
- Glowing cyan accents  
- Smooth card animations  
- Custom scrollbars  

### 📱 Fully Responsive
Perfect on mobile, tablet, and desktop.

---

## 🛠️ Tech Stack
| Category | Technology |
|---------|-------------|
| Framework | Next.js 14 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS |
| UI Library | shadcn/ui + Radix UI |
| Icons | Lucide Icons |
| AI Integration | Vercel AI SDK |
| Automation | IBM watsonx Orchestrate |
| Storage | localStorage |

---

## 🔧 Installation

```bash
# 1. Clone the repository
git clone https://github.com/jacklim-gif/StudyFriendly.git
cd StudyFriendly

# 2. Install dependencies
npm install

# 3. Run development server
npm run dev
Open your browser:

arduino
Copy code
http://localhost:3000
📂 Project Structure
txt
Copy code
StudyFriendly/
│── app/              # Next.js pages
│── components/       # UI components
│── data/             # Flashcard decks & categories
│── public/           # Icons & assets
│── styles/           # Global styles
│── utils/            # XP system, AI helpers
│── ...
🧭 Future Improvements
Cloud sync (Supabase / Firebase)

User accounts & leaderboards

Multiplayer quiz mode

Export/import decks

More AI-assisted learning features

❤️ Support
If you like this project, please ⭐ the repo!
It helps others discover StudyFriendly and contribute.
