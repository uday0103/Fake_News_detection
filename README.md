# 📰 Fake News Detection System 🔍

A web-based **Fake News Detection System** built using **HTML, CSS, JavaScript** (frontend) and **Python Flask with Machine Learning** (backend). This project helps identify whether a news article is **Real** or **Fake**, using Natural Language Processing (NLP) and a trained ML model.

Developed for **Project Expo 2025**, this system demonstrates how AI can combat misinformation by verifying news content in real time.

---

## 🎯 Objective

To provide a lightweight and easy-to-use platform where users can input news content and receive an instant classification of whether the news is **fake or real**, using a trained ML model.

---

## 🚀 Live Demo

🎯 Try out the Fake News Detection System in real time!

🔗 **Frontend** (User Interface):  
[🌐 Open Live Site](https://fake-news-detector-x7re.onrender.com)

🔗 **API Backend** (Hosted on Render):  
[🧠 Fake News Detection API](https://fake-news-api.onrender.com)

### 💬 How It Works

1. Enter a news headline or paragraph into the input field.
2. Click **"Check News"**.
3. The system sends the content to our **ML-powered Flask API**.
4. You'll instantly see a result: ✅ **Real** or ❌ **Fake**.

> Powered by a trained Machine Learning model using real-world datasets and enhanced with NLP for news verification.

---

📢 **Note:** It may take a few seconds to load if the Render backend is waking from sleep (Render Free Tier auto-sleeps inactive services).



---

## 🏆 Achievements
- 🥇 Showcased at College Project Expo 2025

- 🧠 Demonstrated practical use of NLP and ML

- 💬 Received positive feedback for solving real-world misinformation problems

# 📸 Screenshots
<img width="1920" height="1080" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/7df65434-08fc-46ab-bb38-c79e27a21f2b" />
<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/fc147963-dca0-4194-9a2f-57f37078621e" />



## 🛠️ Technologies Used

## 💻 Frontend:
- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5

## 🔬 Backend:
- Python 3
- Flask
- Pandas, NumPy
- Scikit-learn
- NLTK
- TF-IDF Vectorizer

## 🧠 Machine Learning:
- Logistic Regression or Multinomial Naive Bayes
- Trained on a dataset of real & fake news articles

---

## 📡 API Details

**POST** `/predict`  
Sends news text to the backend for classification.

## 🙋‍♂️ Developed By

**Uday Kumar Botlagunta**  
Founder @ WebTides | B.Tech CSE, PACE Institute of Technology and Sciences  
📧 [udayckumar@gmail.com](mailto:udayckumar@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/uday-kumar-0b5564348/)  
💻 [GitHub](https://github.com/uday0103)

[![GitHub](https://img.shields.io/badge/GitHub-@uday0103-black?style=flat&logo=github)](https://github.com/uday0103)


## 📁 Project Structure

```bash
fake-news-detection/
├── backend/
│   ├── app.py               # Flask app with /predict route
│   ├── model.pkl            # Trained ML model
│   ├── vectorizer.pkl       # TF-IDF vectorizer
│   ├── requirements.txt     # Python dependencies
│   └── render.yaml          # Render deployment config (optional)
│
├── frontend/
│   ├── index.html           # UI structure
│   ├── style.css            # Page styling
│   └── script.js            # API call logic
│
├── dataset/
│   └── news.csv             # Dataset for training (optional)
│
├── README.md                # This file

### Request:
```json
{
  "text": "The government has announced free electricity for all citizens."
}

