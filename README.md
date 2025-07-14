# 📧 Email Spam Classifier

A machine learning project to classify emails as **spam** or **not spam** using natural language processing (NLP) and traditional ML algorithms. The project includes data cleaning, feature extraction using TF-IDF, model training, and an interactive web interface built with Streamlit.

---

## 🚀 Features

- Preprocessing and cleaning of raw email text
- Feature extraction using CountVectorizer and TF-IDF
- Training and evaluation using Multinomial Naive Bayes
- Web interface to test custom email inputs
- Visualizations: Pie charts and WordClouds for insights

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - pandas, numpy
  - sklearn (model training and evaluation)
  - nltk (text preprocessing)
  - matplotlib, seaborn, WordCloud (visualization)
  - Streamlit (web interface)

---

## 📦 Installation

1. **Clone the repository**  
   
   git clone https://github.com/rohansamant1/Email-spam-classifier.git
   cd Email-spam-classifier
  
2. Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install the required packages

pip install -r requirements.txt

4. ▶️ Running the App
To launch the Streamlit app:

streamlit run app.py
This will open the spam classifier in your browser where you can input your own email text and get predictions.

5. 🧪 Sample Dataset
The dataset used is a labeled collection of ham (non-spam) and spam messages. It’s included in the repository as spam.csv.

📊 Output Visuals
Pie chart showing spam vs ham distribution

WordCloud for spam and ham emails

Model accuracy display and confusion matrix

📁 Project Structure
bash
Copy
Edit
Email-spam-classifier/
│
├── app.py                 # Streamlit app
├── spam.csv              # Dataset
├── spam_classifier.pkl   # Saved ML model
├── vectorizer.pkl        # Saved TF-IDF vectorizer
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
👨‍💻 Author
Rohan Samant
GitHub

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.


---

Let me know if you’d like to include things like screenshots, model evaluation metrics, or deployment instructions (e.g. Heroku, Hugging Face Spaces, etc.). I can also format this `README.md` with emojis or badges if you want it to look more GitHub-friendly.








Ask ChatGPT


