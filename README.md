# SMARTMAIL‑ASSIST‑REACT

*Craft Smart Email Replies in Seconds with AI-Powered Precision*

![GitHub last commit](https://img.shields.io/badge/last%20commit-today-blue)
![React](https://img.shields.io/badge/React-18.x-blue)
![MUI](https://img.shields.io/badge/MUI-v5-purple)
![Axios](https://img.shields.io/badge/Axios-HTTP%20Client-orange)
![Vite](https://img.shields.io/badge/Vite-Bundler-yellow)

## 📝 Overview

**SmartMail‑Assist React** is a modern, AI-integrated web app that helps users quickly generate professional, context-aware email replies. Built using React, Material UI (MUI), and Axios, the app interacts seamlessly with a Spring Boot + Gemini AI backend.

This project offers a streamlined UI for drafting smart replies from raw email input using OpenAI-style prompting (via Gemini) — ideal for enhancing productivity in communication-heavy workflows.

---

## 🚀 Built With

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MUI](https://img.shields.io/badge/Material%20UI-007FFF?style=flat-square&logo=mui&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)

---

## ✨ Features

* 🧠 **AI‑Powered Replies** — Integrates with Gemini AI via backend to produce polished responses.
* 📧 **Custom Tone Selection** — Choose from professional, casual, or friendly tones.
* 🎯 **Minimal UI, Maximum Productivity** — Simple layout with Material UI components.
* 🔁 **Clipboard Integration** — One‑click copy of generated replies.
* ⚡ **Vite Powered** — Super‑fast dev environment with HMR.
* 🌐 **API‑Driven** — Axios-based backend interaction (uses `.env` for endpoint configuration).

---

## 📂 Table of Contents

- [Overview](#-overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Live Demo](#live-demo)
- [Features](#-features)
- [Learnings](#learnings)
- [Author](#author)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

---

## 🛠 Getting Started

### Prerequisites

Ensure you have the following installed:

- **Node.js** v18+
- **npm** v9+

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/mohdziaulhaq/smartmail-assist-react
```

2. **Navigate to the project directory:**

```bash
cd smartmail-assist-react
```

3. **Install the dependencies:**

```bash
npm install
```

### Usage

1. Create a `.env` file in the root and add:

```env
VITE_API_URL=https://smartmail-assist.onrender.com
```

2. Start the development server:

```bash
npm run dev
```

3. Visit the app in your browser:

```
http://localhost:5173
```

---

## 🌐 Live Demo

| Environment       | URL                                                                 |
| ----------------- | ------------------------------------------------------------------- |
| **Frontend**      | [https://smartmail.netlify.app](https://smartmail.netlify.app)     |
| **Backend (API)** | [https://smartmail-assist.onrender.com](https://smartmail-assist.onrender.com) |
| **Swagger UI**    | [View Docs](https://smartmail-assist.onrender.com/swagger-ui/index.html) |

Use the React UI or call `/api/email/generate` from Postman to test the backend.

---

## 📘 Learnings

By building **SmartMail‑Assist React**, I learned to:

- Build clean and intuitive UIs with **Material UI (MUI)**.
- Connect a React frontend to a **Spring Boot AI backend** using **Axios**.
- Handle async API errors gracefully with **loading states**.
- Leverage environment variables via **Vite**’s config system.
- Deploy and integrate frontend + backend using **Render + Netlify**.

---

## 👤 Author

**Zia Ul Haq Mohammed**

- 🌐 [Portfolio](https://mohdziaulhaq.netlify.app)
- 💼 [LinkedIn](https://www.linkedin.com/in/mohdziaulhaq/)
- 🐙 [GitHub](https://github.com/mohdziaulhaq)
- 📧 [Email](mailto:mohdziaulhaq123@gmail.com)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo, submit pull requests, or open issues.

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).

---

## 💬 Support

For questions, issues, or feedback, please open a GitHub [issue](https://github.com/mohdziaulhaq/smartmail-assist-react/issues).

---

*Built with ❤️ using React, Vite, MUI, and Gemini AI*