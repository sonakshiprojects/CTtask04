## Twitter Sentiment Analysis using NLP

### 📌 Objective
To perform sentiment analysis on tweets using natural language processing techniques.

---

### 🔄 Steps Performed

1. **Data Cleaning & Preprocessing**
   - Removed noise (URLs, punctuation, stopwords).
   - Tokenized and lemmatized text using NLTK.
   - Created a cleaned `processed_text` column.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed sentiment distribution.
   - Visualized most common words per sentiment using WordClouds.
   - Explored tweet length distributions.

3. **Model Building**
   - Vectorized text using TF-IDF (top 5000 features).
   - Built a Logistic Regression model.

4. **Evaluation**
   - Achieved an accuracy of approximately `88%`.
   - Reviewed performance using classification report and confusion matrix.

---

### ✅ Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- NLTK (Stopwords, Lemmatization)
- Scikit-learn (TF-IDF, Logistic Regression, Evaluation)

---

### 📈 Key Insights

- Most common words by sentiment were well-aligned with expected emotion.
- Logistic Regression was effective with simple preprocessing and TF-IDF features.
- WordClouds highlighted strong linguistic patterns across tweet sentiments.

---

### 📁 Deliverable
A Jupyter notebook containing all code for:
- Preprocessing
- EDA
- Model building
- Evaluation
- Visualizations and insights
