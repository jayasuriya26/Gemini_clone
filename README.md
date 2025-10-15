🧠 Gemini Clone (React + Vite)

A modern AI chat interface inspired by Google Gemini, built using React, Vite, and the Google Generative AI API.
This project allows users to interact with Gemini-style prompts and get intelligent responses instantly.

🚀 Features

✨ Chat interface with Gemini-like UI

💬 Dynamic AI responses powered by Google Generative AI

🧭 Sidebar navigation with options like “New Chat,” “Activity,” and “Settings”

🎨 Clean and responsive design with CSS

⚡ Built with Vite for ultra-fast development

🛠️ Tech Stack

Frontend: React (Vite)

API: Google Generative AI (@google/generative-ai)

Styling: CSS / Tailwind (if used)

Version Control: Git + GitHub

📁 Folder Structure
Gemini_App/
│
├── public/
├── src/
│   ├── components/
│   │   ├── Sidebar.jsx
│   │   └── Main.jsx
│   ├── gemini.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md

🔑 Environment Setup

Clone the repository

git clone https://github.com/jayasuriya26/Gemini_clone.git
cd Gemini_clone


Install dependencies

npm install


Add your Google AI API key
Open src/gemini.js and paste your key:

const apiKey = "YOUR_API_KEY_HERE";


⚠️ Never share your API key publicly.
Instead, use an environment file (.env) in production.

Run the development server

npm run dev


Open in browser:

http://localhost:5173

🧩 How It Works

gemini.js handles the Google Generative AI API calls.

Main.jsx displays chat messages and the input field.

Sidebar.jsx provides navigation (New Chat, Help, Settings, etc.).

Responses are dynamically rendered to mimic Gemini’s style.

🖼️ Preview

📦 Deployment

You can deploy this app easily using:

Vercel

Netlify

GitHub Pages (via gh-pages)

Example:

npm run build
npm run deploy

👨‍💻 Author

Jaya Surya P
🔗 GitHub

📜 License

This project is licensed under the MIT License — feel free to use and modify.
