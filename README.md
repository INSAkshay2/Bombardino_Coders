# Bombardino_Coders

# 🌿 Serene Mind — Your Mental Health Companion

Serene Mind is a mental health web application designed to help users reflect on their day, improve their mood, and build healthy habits. The platform leverages AI to provide personalized affirmations and habit recommendations, creating a space that promotes self-awareness and emotional well-being.

---

## ✨ Features

### 📓 Daily Journaling with Mood Analysis
- Journal about your day and let AI understand how it went.
- AI model predicts your mood based on the entry.
- Get personalized affirmations to uplift your mood and help you reflect positively.

### 🌈 Mood Tracker
- Log your mood daily and watch your emotional trends over time.
- Simple and intuitive mood-setting feature.

### ✅ Habit Tracker
- Create and track daily habits to build consistency.
- Check off tasks and maintain streaks for motivation.

### 💡 Habit Recommender
- AI-driven habit suggestions based on your journal patterns and mood logs.
- Encourages healthy and personalized lifestyle improvements.

---

## 🛠️ Tech Stack

### Frontend
- **Next.js** — React framework for server-side rendering and routing.
- **TypeScript** — Strong typing for safer development.
- **React.js** — Core UI library.
- **Radix UI** — Accessible UI primitives for a consistent design system.

### Backend
- **PostgreSQL** — Relational database for storing journal entries, moods, and habits.
- **Supabase** — Backend as a service for authentication and database.
- **Grokai API** — Powers journal sentiment analysis and habit suggestions.
- **Guardrailing System** — Ensures safe, respectful, and positive AI outputs.

---

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/serene-mind.git
   cd serene-mind
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file and add:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key
   GROKAI_API_KEY=your_grokai_api_key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Folder Structure

```
serene-mind/
├── components/        # Reusable React components
├── pages/             # Route files (Next.js)
├── styles/            # Styling files (CSS/Tailwind)
├── utils/             # Utility functions
├── lib/               # Supabase and API logic
├── public/            # Static assets
└── ...
```

---

## 🧠 AI & Safety

- Journal entries are analyzed using **Grokai** to detect emotions and overall sentiment.
- Affirmation generation is handled via a **guardrailed** AI system to ensure outputs are safe, positive, and non-harmful.

---

## 🤝 Contributing

We welcome contributions! Feel free to:
- Report issues
- Suggest new features
- Submit pull requests

1. Fork the repo
2. Create a feature branch
3. Make your changes
4. Submit a PR 🚀

---

## 📄 License

This project is licensed under the MIT License.

---

## 🌐 Live Demo

[🔗 Try Serene Mind](https://your-deployment-link.com)

---

## 📬 Contact

Have questions, feedback, or just want to say hi?  
Reach out at [sharma.akshay2782629@gmail.com]

---
