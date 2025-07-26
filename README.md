# 📰 Fake News Detection System 🔍

A web-based **Fake News Detection System** that helps users identify whether a news article is **real** or **fake** using Machine Learning and Natural Language Processing (NLP). The project features a **HTML/CSS/JavaScript** frontend with a **Python Flask** backend.

This project was developed for a **Project Expo 2025**, showcasing the practical use of AI in combating misinformation.

---
## 🚀 Live Demo

🎯 Try out the Fake News Detection System in real time!

🔗 **Frontend** (User Interface):  
[🌐 Open Live Site](https://fake-news-detector-x7re.onrender.com/)

🔗 **API Backend** (Hosted on Render):  
[🧠 Fake News Detection API](https://fake-news-api.onrender.com)

### 💬 How It Works

1. Enter a news headline or paragraph into the input field.
2. Click **"Check News"**.
3. The system sends the content to our **ML-powered Flask API**.
4. You'll instantly see a result: ✅ **Real** or ❌ **Fake**.



---

📢 **Note:** It may take a few seconds to load if the Render backend is waking from sleep (Render Free Tier auto-sleeps inactive services).



## 🎯 Project Objective

To detect and classify news content as **Real** or **Fake** using an NLP-powered ML model, making it easy for users to verify news authenticity in a fast and simple interface.

---

## 🛠️ Technologies Used

### 🧩 Frontend:
- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5 (for responsive design)
- Fetch API (to send requests to backend)

### 🔬 Backend:
- Python 3
- Flask (REST API)
- Pandas, NumPy
- Scikit-learn
- NLTK / spaCy (for NLP)
- TfidfVectorizer

  

### 🧠 Machine Learning Model:
- Logistic Regression / Naive Bayes
- Dataset: [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

---

## 🚀 Features

- Simple UI for users to input news text
- Detects whether the news is **Fake** or **Real**
- Real-time prediction using trained ML model
- Clean and responsive frontend
- Educational value and real-world relevance

---

## 🔧 How to Run the Project

# Start Backend (Flask + ML)

cd backend
pip install -r requirements.txt
python app.py

# Open Frontend

cd frontend
Open index.html in browser

## 📂 Project Structure
- fake-news-detector/
- ├── backend/
- │   ├── app.py                 # Flask backend
- │   ├── model.pkl              # Trained ML model
- │   ├── vectorizer.pkl         # TF-IDF vectorizer
- │   └── requirements.txt       # Python dependencies
- ├── frontend/
- │   ├── index.html             # Main HTML file
- │   ├── style.css              # CSS styling
- │   └── script.js              # JavaScript logic (fetch API, DOM)
- ├── README.md


# 🏆 Achievements
- 🥇 Presented at Project Expo 2025
- 🧠 Live demo impressed faculty and visitors
- 🎓 Built using self-learned ML and web dev skills


---

## 🙋‍♂️ Developed By

**Uday Kumar Botlagunta**  
Founder @ WebTides | B.Tech CSE, PACE Institute of Technology and Sciences  
📧 [udayckumar@gmail.com](mailto:udayckumar@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/uday-kumar-0b5564348/)  
💻 [GitHub](https://github.com/uday0103)

[![GitHub](https://img.shields.io/badge/GitHub-View_Profile-black?logo=github)](https://github.com/uday0103)


# 📜 License
This project is for educational purposes. Contributions welcome!

## 📸 Screenshots
<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/c3bbe596-5ccf-4b6c-92cd-15c9b113b883" />
<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/0be2074a-25df-4186-ac67-218def899669" />
<img width="1920" height="1080" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/cd889adf-2035-4475-81d1-ac10076d80e8" />

# 🌐 External APIs Used for Verification

To enhance the accuracy and transparency of our **Fake News Detection System**, we integrated trusted external APIs to **cross-verify news content** and provide additional context.

# 1. 📡 Google News API / NewsData.io API (or similar)

We used a **News Aggregator API** to fetch and compare the input article with headlines from **reliable media outlets** like:

- Google News
- BBC
- The Hindu
- Reuters
- Times of India, etc.

# 🔍 Use Case:
- When a user submits an article for analysis, we query recent headlines with matching keywords or entities.
- If the submitted article strongly matches verified news sources, it's likely to be **real**.
- If there are no matching credible results, it may be flagged as **potentially fake**.

# 🛠 Example API Used:
- [NewsData.io](https://newsdata.io/)
- [NewsAPI.org](https://newsapi.org/)
- [ContextualWeb News API](https://rapidapi.com/contextualwebsearch/api/web-search)




