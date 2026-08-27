# 🎓 AI Study Buddy

> A single-file, AI-powered study assistant that explains concepts, generates quizzes, builds revision plans, and answers your doubts — all from your own notes.

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Click%20Here-6c63ff?style=for-the-badge)](https://harshitcortex.github.io/AI-Study-Buddy/)
&nbsp;
[![GitHub Repo](https://img.shields.io/badge/GitHub-harshitCorteX-181717?style=for-the-badge&logo=github)](https://github.com/harshitCorteX/AI-Study-Buddy)

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Groq](https://img.shields.io/badge/Powered%20by-Groq%20LLM-6c63ff?style=flat)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)

---

## 🔗 Live Demo

👉 **[https://harshitcortex.github.io/AI-Study-Buddy/](https://harshitcortex.github.io/AI-Study-Buddy/)**

> Open the link, paste your notes, add your free Groq API key — and start studying smarter!

---

## ✨ Features

| Feature | Description |
|---|---|
| 📝 **My Notes** | Paste text or drag-and-drop `.txt` / `.md` files as your study material |
| 🧠 **Explain It** | Get plain-English explanations at ELI5, Teen, or College level |
| ✏️ **Quiz Me** | Auto-generate MCQ quizzes from your notes with instant scoring |
| 📅 **Study Plan** | Get a structured week-by-week revision schedule tailored to your exam |
| 💬 **Doubt Chat** | Ask anything — the AI answers strictly from your uploaded notes |

---

## 🚀 Getting Started

### Option 1 — Use the Live App (Recommended)

Just open the live demo link and start using it instantly — no installation needed:

**➡️ [https://harshitcortex.github.io/AI-Study-Buddy/](https://harshitcortex.github.io/AI-Study-Buddy/)**

### Option 2 — Run Locally

```bash
# Clone the repository
git clone https://github.com/harshitCorteX/AI-Study-Buddy.git

# Navigate into the project
cd AI-Study-Buddy

# Open directly in your browser — no build step needed!
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

> **That's it.** There are zero dependencies, no `npm install`, no server required.

---

## 🔑 API Key Setup

1. Go to [console.groq.com](https://console.groq.com/) and sign in
2. Navigate to **API Keys** → **Create API Key**
3. Copy the key and paste it into the **Groq API Key** field in the app header

> Your key is never stored or sent anywhere except directly to the Groq API from your browser.

---

## 🖥️ Usage Guide

### 1 · Add Your Notes
Head to **My Notes** and either paste your syllabus/lecture notes into the text area, or upload a `.txt` or `.md` file via click or drag-and-drop. Hit **💾 Save Notes** — all features draw from this content.

### 2 · Explain a Topic
Go to **Explain It**, type any topic (e.g. *Photosynthesis*, *Newton's Laws*), pick your level and click **✨ Explain**:

| Level | Audience |
|---|---|
| 🧒 ELI5 | 5-year-old — simple words, fun analogies |
| 🧑 Teen | 14-year-old — relatable examples, light jargon |
| 🎓 College | Undergraduate — thorough, technical but clear |

### 3 · Take a Quiz
Go to **Quiz Me**, choose how many questions (3 / 5 / 10) and optionally specify a topic. Click **🎯 Generate Quiz** — select your answers, then hit **🏆 Submit & See Score** to get instant feedback with explanations.

### 4 · Build a Study Plan
Go to **Study Plan**, set the number of weeks, daily study hours, and your exam/goal name. Click **📋 Generate Plan** to get a structured week-by-week schedule built around your notes.

### 5 · Chat With Your Notes
Go to **Doubt Chat** and ask any question. The AI responds strictly from your uploaded notes, so answers stay relevant to your syllabus.

---

## 🗂️ Project Structure

```
AI-Study-Buddy/
├── index.html      # The entire app — HTML + CSS + JS in one file
└── README.md       # This file
```

This is intentionally a **zero-dependency, single-file** project — easy to share, host, or embed anywhere.

---

## ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 — custom properties, CSS Grid, Flexbox |
| Logic | Vanilla JavaScript (ES2020+) — async/await, Streams API |
| AI Model | `llama-3.3-70b-versatile` via **Groq API** |
| Persistence | Browser `localStorage` |
| File Reading | `FileReader` API |

---

## 🌐 Deployment (GitHub Pages)

This project is hosted via **GitHub Pages**. To deploy your own fork:

1. Push `index.html` to the `main` branch of your repo
2. Go to your repo → **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save** — your app will be live at `https://<your-username>.github.io/<repo-name>/`

---

## 🔒 Privacy

- Notes are stored **only in your browser's `localStorage`** — nothing is sent to any server other than the Groq API.
- The Groq API call is made **directly from your browser** using your own API key.
- No analytics, no tracking, no backend.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for:

- New study features (flashcards, mind maps, etc.)
- UI/UX improvements
- Support for additional file formats (`.pdf`, `.docx`)
- Mobile layout enhancements

---

## 📄 License

This project is licensed under the **MIT License**.

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/harshitCorteX">harshitCorteX</a> · Powered by Groq LLM</sub>
</div>
