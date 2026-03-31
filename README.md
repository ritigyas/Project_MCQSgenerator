# 🧠 MCQ Generator from Text & PDF

An AI-powered web application that automatically generates Multiple Choice Questions (MCQs) from input text or uploaded PDF/TXT files using NLP techniques.

---

## 🚀 Features

- 📄 Upload PDF or TXT files
- ✍️ Manual text input support
- 🤖 Automatic MCQ generation using NLP (spaCy)
- 🎯 Custom number of questions selection
- 🔀 Randomized answer choices
- 🌐 Simple and clean web interface (Flask + Bootstrap)

---

## 🛠️ Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML, Bootstrap
- **NLP Library:** spaCy
- **PDF Processing:** PyPDF2

---


## 📂 Project Structure

Project_MCQSgenerator/
│

├── templates/ 

│ ├── index.html # Input page

│ ├── mcqs.html # Output MCQs page

│

├── app.py # Main Flask application

├── imp.ipynb # Experimental notebook

└── README.md


---

## ⚙️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/ritigyas/Project_MCQSgenerator.git
cd Project_MCQSgenerator
```
2. **Create virtual environment (optional but recommended)**
```bash
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # Mac/Linux
```
3. **Install dependencies**
```bash
pip install flask flask-bootstrap spacy PyPDF2
```
4. **Download spaCy model**
```bash
python -m spacy download en_core_web_sm
```
5. **Run the application**
```bash
python app.py
```
6. **Open in browser**
```bash
http://127.0.0.1:5000/
```

## 🧠 How It Works
Extracts text from PDF/TXT or manual input

Uses spaCy NLP to:

Tokenize sentences

Identify nouns

Selects key nouns as blanks

Generates MCQs with:

One correct answer

Three distractors

Randomizes options for each question

## 📌 Future Improvements
Improve question quality using advanced NLP/LLMs

Add difficulty levels (Easy/Medium/Hard)

Export MCQs to PDF/CSV

Add user authentication

Deploy on cloud (Render/Heroku)

## 🤝 Contributing

Feel free to fork the repository and contribute!

## 📄 License

This project is open-source and available under the MIT License.

## 👩‍💻 Author

Ritigya Singh
