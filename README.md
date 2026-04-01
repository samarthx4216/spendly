# 💸 Spendly

A lightweight AI-powered personal expense tracking web application built with Python and Flask — developed using **Claude Code** and powered locally by **Ollama**.

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## About

Spendly is a simple and intuitive web app that helps you track your daily expenses, monitor spending habits, and stay on top of your budget — all from your browser. The app was built entirely using **Claude Code** (Anthropic's AI coding assistant) and leverages **Ollama** for running local AI models to power intelligent features.

---

## ✨ Features

- Add, view, and manage expenses
- Categorize your spending
- AI-powered insights via Ollama (runs locally — no internet required)
- Clean and responsive web interface
- Lightweight local database storage

---

## 📁 Project Structure

```
spendly/
├── database/          # Database files and schema
├── static/            # CSS, JavaScript, and image assets
├── templates/         # HTML Jinja2 templates
├── app.py             # Main Flask application entry point
├── requirements.txt   # Python dependencies
└── .gitignore         # Git ignore rules
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip
- [Ollama](https://ollama.com) installed and running locally

---

## 🛠 Installation

1. **Clone the repository**

```bash
git clone https://github.com/samarthx4216/spendly.git
cd spendly
```

2. **Create a virtual environment** (recommended)

```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Pull and run your Ollama model**

```bash
ollama pull llama3
ollama serve
```

> You can swap `llama3` for any model supported by Ollama (e.g. `mistral`, `gemma`, `phi3`).

---

## ▶️ Usage

Run the Flask development server:

```bash
python app.py
```

Then open your browser and navigate to:

```
http://127.0.0.1:5000
```

Make sure Ollama is running in the background before starting the app.

---

## 🧰 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Backend logic |
| Flask | Web framework |
| HTML/CSS/JS | Frontend UI |
| SQLite | Local database storage |
| Jinja2 | HTML templating |
| Ollama | Local AI model runner |
| Claude Code | AI-assisted development |

---

## 🤖 Built with Claude Code

This project was built using [Claude Code](https://claude.ai/code) — Anthropic's agentic AI coding tool — which helped scaffold, debug, and iterate on the entire codebase directly from the terminal.

---

## 🦙 Powered by Ollama

[Ollama](https://ollama.com) enables Spendly to run AI features **completely offline and locally** on your machine — no API keys, no cloud calls, full privacy.

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ by [samarthx4216](https://github.com/samarthx4216) using Claude Code & Ollama
