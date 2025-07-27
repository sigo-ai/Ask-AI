# Ask-AI 🤖✨ (Powered by Google Gemini)
([Ask-AI](https://ask-ai-eight-red.vercel.app/))


An AI chatbot clone using Google's Gemini API to simulate intelligent, human-like conversations. Built with Next.js 14, Tailwind CSS, and App Router, Ask-AI is a minimal, clean, and fast chatbot UI ready for deployment.

## 🌟 Features

* Google Gemini model integration via `@ai-sdk/google`
* Streaming text output with `ai` package
* Chat history support (with message context)
* Fast and responsive UI using Tailwind CSS
* Light and dark mode toggle
* Clean file-based routing with Next.js App Router

## 🧰 Tech Stack

* Framework: Next.js 14 (App Router)
* AI SDK: @ai-sdk/google
* UI: Tailwind CSS
* Streaming: ai SDK

## 🛠️ Setup Instructions

1. Clone the Repo:

   git clone [https://github.com/sigo-ai/Ask-AI.git](https://github.com/sigo-ai/Ask-AI.git)
   cd Ask-AI/ask-ai

2. Install Dependencies:

   npm install

3. Configure Environment Variables:

   Create a `.env.local` file in the root and add:

   GOOGLE\_API\_KEY=your-google-api-key

   Get your Gemini API key here: [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)

4. Run the Development Server:

   npm run dev

   Visit [http://localhost:3000](http://localhost:3000) to use your chatbot.

---

## 🧪 File Overview

ask-ai/
├── app/                      → App router pages and routes
│   ├── api/                  → Serverless API route (Gemini integration)
│   └── page.tsx              → Main chat page
├── components/               → Reusable UI components
├── lib/                      → AI utilities using @ai-sdk/google
├── public/                   → Static assets
├── styles/                   → Tailwind and global styles
├── .env.local                → Your Gemini API Key
└── package.json              → Project config and dependencies

---

## 🚀 Deployment (Vercel)

1. Push the repo to GitHub
2. Connect your GitHub repo to Vercel
3. Add `GOOGLE_API_KEY` in Environment Variables
4. Deploy!

---

## 📌 To-Do List

* [ ] Add multi-turn conversation memory
* [ ] Add file/image input for multimodal Gemini support
* [ ] Add authentication (NextAuth or Clerk)
* [ ] Add speech-to-text and text-to-speech

---

## 🤝 Contributing

Pull requests are welcome. Please open an issue first to discuss any major changes.

---

## 📄 License

MIT License

---

Built with ❤️ using Google Gemini by @sigo-ai

