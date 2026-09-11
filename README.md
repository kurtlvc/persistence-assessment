# 📚 PersistenCe Course Reviewer

> A single HTML JSON-powered Multiple Choice Questions (MCQ) assessment app.

![Platform](https://img.shields.io/badge/platform-web-green.svg)

---

## 📖 About the Project

**PersistenCe Course Reviewer** is a lightweight, assessment-type application designed to help
students review through **Multiple Choice Questions (MCQs)** in JSON!

All question banks are stored as **simple JSON files** — no database, no backend setup required.
Just add a JSON file, launch the app, import and start reviewing. Perfect for exam preparation,
self-study, and quick knowledge checks.

---

## ✨ Features

- 📝 **MCQ-Based Assessment** — take quizzes with optional answer checking
- 📝 **Answer Sheet Assessment** — take quizzes with traditional shading style
- 📁 **JSON-Based Question Banks** — add/edit questions using JSON
- ✅ **Check Answer** — correct/wrong indicators with explanations
- 📊 **Score Summary** — results page with percentage and item-by-item review
- 🔀 **Shuffle Mode** — randomize question and choice order
- ⏱️ **Timed Mode** *(optional) — answer under exam-like pressure
- 🌓 **Dark / Light Mode** — easy on the eyes, day or night
- 📱 **Responsive Design** — works on desktop, tablet, and mobile
- 🖥️ **Works Offline** — is a single html file

---

## 🛠️ Built With

| Layer     | Technology                |
|-----------|---------------------------|
| Structure | HTML                      |
| Styling   | CSS                       |
| Logic     | JavaScript                |
| Data      | JSON (question banks)     |


---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- *(Optional)* [VS Code](https://code.visualstudio.com/) with the **Live Server** extension

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kurtlvc/persistence-assessment.git
   cd persistence-announcement
   ```

2. **Run the app** — choose any of the following:
   - Double-click `index.html`, **or**
   - Use VS Code Live Server → *Go Live*, **or**
   - Serve locally:
     ```bash
     npx serve .
     ```

3. **Start reviewing!** 🎉

---

## 🗂️ JSON Question Bank Format

Each question can be a single `.json` file:

```json
[
  {
    "id": 1,
    "question": "What does CPU stand for?",
    "options": {
      "A": "Central Process Unit",
      "B": "Central Processing Unit",
      "C": "Computer Processing Unit",
      "D": "Central Processor Utility"
    },
    "answer": "B",
    "insight": "CPU = Central Processing Unit, the primary component that executes instructions."
  }
]
```

---

## 🎮 How to Use

1. **Launch** the app then import a JSON Quiz
2. **Configure** your session (timer, shuffle questions)
3. **Answer** each question — pick one choice and submit
4. **Review** check answer for feedback and explanations
5. **View** your final score and revisit missed items

---

## 🗺️ Roadmap

- [ ] Export results as PDF
- [ ] PWA support (installable on mobile)
- [ ] Question bank editor UI

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 👤 Author

**GitHub** — [@kurtlvc](https://github.com/kurtlvc)
Project Link: [https://github.com/kurtlvc/persistence-assessment](https://github.com/kurtlvc/persistence-assessment)
