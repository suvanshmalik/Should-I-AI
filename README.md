# Should I? AI ⚖️

**Should I? AI** is a premium, AI-powered decision-support tool built to eliminate "analysis paralysis." It uses Google's advanced Gemini AI to objectively weigh two options against a user's unique constraints and priorities, providing a structured logical verdict.

![Project Status](https://img.shields.io/badge/Status-Hackathon--Ready-success)
![UI Style](https://img.shields.io/badge/UI-Glassmorphism-blue)
![AI Model](https://img.shields.io/badge/AI-Gemini--3--Flash-blueviolet)

---

## 🚀 The Mission
We've all been there: staring at two choices for hours. **Should I? AI** takes the heavy lifting out of overthinking. It isn't just a chatbot; it’s a logic engine that acts as a third-party mediator, highlighting risks and assigning quantitative scores to qualitative dilemmas.

---

## ✨ Key Features
- **Logic Score Engine:** Each option is assigned a score out of 100 based on your specific life constraints.
- **Glassmorphic UI:** A modern, semi-transparent interface with smooth transitions and deep-dark mode support.
- **Hidden Risk Detection:** The AI identifies subtle risks (financial, emotional, or time-based) that users typically overlook.
- **Privacy Centric:** API keys are processed client-side and stored only in your session—never sent to a secondary database.
- **Full-Screen Responsive:** Optimized to scale from mobile phones up to 4K ultra-wide monitors.

---

## 🛠️ Technical Showcase

### 🧠 Prompt Engineering & Schema Enforcement
This project utilizes **Structured JSON Output**. Instead of raw text, the Gemini model is forced into a strict JSON schema. This ensures the frontend receives clean data (scores, pros/cons arrays, and summaries) every single time, preventing UI crashes.

### 🎨 Design Philosophy
The app utilizes a **Glassmorphism** design system with:
- **Tailwind CSS** for rapid, utility-first styling.
- **Dynamic CSS Transitions** that move the form to the side when results are generated.
- **Responsive Grid Layout** that auto-adjusts from a centered "focus mode" to a dual-pane "analysis mode."

---

## 📦 Installation & Setup

1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/Suvansh-Malik/Should-I-AI.git](https://github.com/Suvansh-Malik/Should-I-AI.git)
   cd Should-I-AI
2. Launch:
   Open index.html in your browser. (No build steps or npm install required!)

3. Get an API Key:
   Get your free key at Google AI Studio and paste it into the secure input field in the app.
**Roadmap & Future Plans**
[ ] Support for comparing 3+ options simultaneously.

[ ] Export analysis as a PDF report.

[ ] Browser extension for quick "Should I buy this?" Amazon integration.

Author
Suvansh Malik
Full-Stack Developer & AI Product Designer
