# 🎓 B.Tech PYQ Analyzer — Smart Exam Prep Tool

An AI-powered smart exam preparation dashboard designed specifically for B.Tech & Engineering university exams (like AKTU, Mumbai University, UPTU, etc.). It analyzes 4 years of Past Year Question (PYQ) papers to rank topics, predict exam importance, map questions to standard B.Tech syllabus units, and generate personalized study roadmaps.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![AI](https://img.shields.io/badge/AI-Gemini%20%2F%20Llama3-orange?style=for-the-badge)

---

## ✨ Features

*   **📦 5-Unit B.Tech Syllabus Breakdown**: Engineering syllabuses are structured into exactly 5 units. The AI automatically parses, categorizes, and labels each topic to its corresponding unit (1-5) so you don't miss anything.
*   **🔥 Must-Study (HOT) Topic Identification**: Automatically identifies questions appeared in 3-4 years and lists them as top priority.
*   **📊 Interactive Chart & Analytics**: Beautiful modern bar chart (via Chart.js) mapping topic frequencies.
*   **💡 Hinglish Study Strategy**: Provides a custom, conversational strategy summary and action items in clean Hinglish.
*   **📥 Multi-Format Reports**: Download current subject reports or combined multi-subject reports in premium styled **PDF** or clean **TXT** formats.
*   **📚 Multi-Subject Manager**: Configure, switch between, and analyze multiple subjects simultaneously.
*   **🔑 Local Storage API Configuration**: Pushed code contains **NO hardcoded API keys**, complying with GitHub safety standards. Paste your Groq (`gsk_...`) or Gemini API key directly into the UI; it gets securely saved in your browser's `localStorage` and never leaves your machine.
*   **📱 Seamless Mobile UI**: Premium glowing dark mode theme, interactive animations, and responsive styling.

---

## 🛠️ Tech Stack & Dependencies

*   **Core**: HTML5, Vanilla CSS3 (Custom Glassmorphic Glow variables)
*   **Logic**: ES6+ JavaScript
*   **PDF.js**: For offline PDF text extraction
*   **Chart.js**: For topic frequency visualization
*   **Html2Pdf.js**: For premium styled PDF report downloads
*   **APIs Supported**: Groq Cloud (Llama 3.3 70B), Google Gemini (Gemini 2.0 Flash)

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/dipanshuprajapti/pyq_analyzer.git
cd pyq_analyzer
```

### 2. Run the Application
You can run it directly by opening `index.html` in your browser, or using a local server extension like **Live Server** in VS Code:
```bash
# Using live-server (if installed)
live-server
```

### 3. API Key Setup
1. Open the application.
2. Under the **API Configuration** card, paste your **Groq API Key** (`gsk_...`) or **Gemini API Key**.
3. Click **💾 Save Key**.
4. Load the **Demo Data** or type your exam questions and click **🔍 Analyze Karo**!

---

## 🛡️ Security & Privacy First

This application runs **entirely in your browser**. 
*   Your API keys are stored in `window.localStorage` and never sent to any third-party backend servers.
*   Direct fetch requests are sent securely to Groq/Google endpoints.

---

## 📈 Demo Preview

You can load pre-configured Computer Networks demo papers directly inside the UI with the **"Demo Data Load Karo"** button to check the full output instantly!

---

*Made with ❤️ to help engineering students score outstanding grades in B.Tech exams!*
