# My-AI-Chatbot

A modern AI chatbot application built using React JS and Tailwind CSS, inspired by ChatGPT.
This project demonstrates API integration, clean UI development, component structuring, and state management in React.

## Features
⚡ Real-time AI responses using an API

🎨 Modern UI built with Tailwind CSS

💬 Smooth chat interface with auto-scroll

🧩 Reusable and clean React components

📱 Fully responsive design for all screens

🔄 Loading states + typing effect

🔐 Environment variable support for API keys

🗂 Organized folder structure for scalability

## Tech Stack
React JS

Tailwind CSS

JavaScript (ES6+)

AI API (Gemini API or other provider)

## Folder Structure
my-chatbot/
│── public/
│── src/
│   ├── components/
│   │   ├── ChatLogs.jsx
│   │   ├── QnA.jsx
│   │   ├── Replies.jsx
│   ├── pages/
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── index.js
│── .env
│── package.json
│── README.md


## Installation
1️⃣ Clone the repository
git clone https://github.com/your-username/myAIChatbot.git
cd my-chatbot

2️⃣ Install dependencies
npm install

3️⃣ Add your API key

Create a .env file in the project root:

YOUR_API_KEY=your_api_key_here

4️⃣ Start the app
npm run dev

Your AI chat tool will be running at:
👉 http://localhost:5173/

## How It Works
User enters a prompt

React sends request to AI API

API returns generated text

Message appears in chat interface

Chat scrolls automatically


