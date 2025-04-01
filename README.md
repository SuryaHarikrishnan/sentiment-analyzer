# README.md

# 🧠 Sentiment Analyzer (Web App)

A beginner-friendly NLP project that analyzes the **sentiment** of user input text (Positive, Negative, or Neutral) using Python, Flask, and TextBlob.

---

## 🚀 Features
- Web interface using **Flask**
- Sentiment analysis with **TextBlob**
- Emoji-based feedback
- Clean and modern UI with HTML/CSS

---

## 🧩 How It Works
1. User types a sentence in the text box.
2. App uses **TextBlob** to calculate the polarity of the text.
3. Polarity score is interpreted as:
   - `> 0` → Positive 😊
   - `< 0` → Negative 😞
   - `= 0` → Neutral 😐
4. Result is displayed instantly on the page.

---

## 🛠️ Tech Stack
- **Python 3.13**
- **Flask** (Backend web framework)
- **TextBlob** (NLP sentiment analysis)
- **HTML/CSS** (Frontend UI)

---

## 📦 Installation
```bash
# Clone the repo (or download as ZIP)
git clone https://github.com/YOUR_USERNAME/sentiment-analyzer.git
cd sentiment-analyzer

# Install dependencies
pip install flask textblob
python -m textblob.download_corpora

# Run the web app
python app.py
```
Visit `http://127.0.0.1:5000/` in your browser.

---

## 📁 Project Structure
```
sentiment-analyzer/
├── app.py              # Flask web server
├── analyzer.py         # Sentiment logic using TextBlob
├── templates/
│   └── index.html      # Frontend UI
└── README.md
```

---

## 🔮 Future Improvements
- Add confidence score or polarity bar
- Save sentiment history for each user
- Add support for analyzing tweets or articles
- Deploy online via Render or Replit

---

## ✨ Author
Surya Narayanan Harikrishnan

---

Feel free to fork, star, or improve this repo. Let’s build cool things with AI! 🤖
