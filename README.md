# Tongue & Type — Language Translation Tool

A simple, clean web app that translates text between 20+ languages in real time. Built as **Task 1** for the **CodeAlpha Artificial Intelligence Internship**.

🔗 **Live Demo:** _[add your GitHub Pages link here once enabled]_

## ✨ Features

- Enter any text and select a source and target language
- Real-time translation powered by the **MyMemory Translation API**
- Swap source ⇄ target languages with one click
- Listen to source or translated text (text-to-speech)
- Copy translated text to clipboard
- Character counter (500 character limit per request)
- Clean, responsive UI — works on desktop and mobile

## 🛠️ Built With

- HTML5
- CSS3 (custom styling, no frameworks)
- Vanilla JavaScript (no dependencies)
- [MyMemory Translation API](https://mymemory.translated.net/) — free, no API key required
- Web Speech API (browser-native text-to-speech)

## 🚀 How to Run

No build tools or installation required.

1. Clone or download this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
3. Start translating!

> **Note:** Since this app calls an external API, it needs to be opened in a real browser (not an embedded in-app preview/webview) for the network request to succeed.

## 📖 How It Works

1. User types text into the source text box and selects source/target languages
2. On clicking **Translate**, the app sends a request to the MyMemory API with the text and language pair
3. The API returns the translated text, which is displayed instantly
4. Optional tools (speak, copy, swap) enhance usability

## 📂 Project Structure

```
CodeAlpha_TranslationTool/
├── index.html      # Complete app (HTML + CSS + JS in one file)
└── README.md       # Project documentation
```

## 🎓 About This Project

This project was completed as part of the **CodeAlpha AI Internship Program**, which provides hands-on experience in AI model development and real-world application building.

- **Internship:** Artificial Intelligence
- **Task:** Task 1 — Language Translation Tool
- **Company:** [CodeAlpha](https://www.codealpha.tech)

## 📜 License

This project is open source and free to use for learning purposes.
****
