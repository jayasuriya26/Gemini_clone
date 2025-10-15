## 🧠 Gemini Clone (React + Vite)

A modern **AI chat interface** inspired by Google Gemini, built using **React**, **Vite**, and the **Google Generative AI API**.
This project allows users to interact with Gemini-style prompts and get intelligent responses instantly.

---

### 🚀 Features

* ✨ Chat interface with Gemini-like UI
* 💬 Dynamic AI responses powered by Google Generative AI
* 🧭 Sidebar navigation with options like “New Chat,” “Activity,” and “Settings”
* 🎨 Clean and responsive design with CSS
* ⚡ Built with **Vite** for ultra-fast development

---

### 🛠️ Tech Stack

* **Frontend:** React (Vite)
* **API:** Google Generative AI (`@google/generative-ai`)
* **Styling:** CSS
* **Version Control:** Git + GitHub

---

### 📁 Folder Structure

```
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
```

---

### 🔑 Environment Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/jayasuriya26/Gemini_clone.git
   cd Gemini_clone
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Add your Google AI API key**
   Open `src/gemini.js` and paste your key:

   ```js
   const apiKey = "YOUR_API_KEY_HERE";
   ```

   > ⚠️ Never share your API key publicly.
   > Instead, use an environment file (`.env`) in production.

4. **Run the development server**

   ```bash
   npm run dev
   ```

5. Open in browser:

   ```
   http://localhost:5173
   ```

---

### 🧩 How It Works

* `gemini.js` handles the **Google Generative AI API** calls.
* `Main.jsx` displays chat messages and the input field.
* `Sidebar.jsx` provides navigation (New Chat, Help, Settings, etc.).
* Responses are dynamically rendered to mimic Gemini’s style.

---

### 🖼️ Preview
<img width="1909" height="907" alt="Screenshot 2025-10-15 141001" src="https://github.com/user-attachments/assets/16fea6de-1955-4f8a-b106-6db918819eea" />

---

### 📦 Deployment

You can deploy this app easily using:

* **Vercel**
* **Netlify**
* **GitHub Pages** (via `gh-pages`)

Example:

```bash
npm run build
npm run deploy
```

---

### 👨‍💻 Author

**Jaya Surya P**
🔗 [GitHub](https://github.com/jayasuriya26)

---

### 📜 License

This project is licensed under the **MIT License** — feel free to use and modify.
