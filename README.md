# 🎙️ VoiceCartAI - Smart Voice-Enabled Shopping Cart

VoiceCartAI is an intelligent, voice-driven shopping assistant built with React and Vite. It allows users to manage their grocery and shopping cart seamlessly using real-time speech recognition, natural language intent parsing, and smart product recommendations.

---

## ✨ Features

- **Voice Command Processing:** Add, update quantities, filter, and remove items using natural speech.
- **NLP Intent Engine:** Parses complex natural language instructions to perform accurate cart actions.
- **Text-to-Speech Feedback:** Audio confirmations and responses via browser speech synthesis.
- **Smart Recommendations:** Contextual item suggestions based on current cart contents.
- **Interactive Product Catalog:** Browse, search, and view available store items directly.
- **Real-Time Summary & Metrics:** Live computation of total cost, item count, and savings.

---

## 🛠️ Tech Stack

- **Framework:** [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Styling:** Modern CSS3
- **Voice / Audio:** Web Speech API (`webkitSpeechRecognition` & `speechSynthesis`)
- **Linter:** [Oxlint](https://oxc.rs/)

---

## 📁 Project Structure

```text
Unthinkable_VoiceCartAI/
├── public/                # Static assets and icons
├── src/
│   ├── assets/            # Images and UI graphics
│   ├── components/        # UI components (VoiceMicBar, ShoppingList, etc.)
│   ├── hooks/             # Custom React hooks (useShoppingList, useVoiceAssistant)
│   ├── services/          # Core engines (nlpEngine, recommendationEngine, speech APIs)
│   ├── App.jsx            # Main app shell
│   └── main.jsx           # Entry point
├── package.json
└── vite.config.js
