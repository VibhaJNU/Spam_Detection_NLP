
# 📧 Spam Mail Detection using NLP and Machine Learning

This project demonstrates how to build an **NLP-based spam classifier** that can detect whether a message/email is **spam** or **ham (not spam)**. The project includes **exploratory data analysis (EDA)**, **text preprocessing**, **feature engineering**, **model training**.

---

## 🔍 Project Workflow

### 1. **Exploratory Data Analysis (EDA)**

* Analyzed the distribution of spam and ham messages.
* Visualized the message lengths and their distributions.
* Identified key differences in text length and density between spam and ham messages, before and after preprocessing.

### 2. **Text Processing**

Step 1:Removal of Apostrophe
Step 2: Convert all words ino lowercase
Step 3: Remove Puncuation
Step 4: Remove stopwords (dont remove ok and not)
Step 5: Remove single words
Step 6: Apply lemmatization
Step 7: Remove numbers

### 3. **Feature Engineering**

1. Vectarization: Bag of Words
2. TF-IDF representation
   
### 4. **Model Building**

* Models trained:

  * **Multinomial Naive Bayes**
  * **Logistic Regression**
  * 
* Evaluated models using:

  * Accuracy
  * Confusion Matrix
  * Classification Report (Precision, Recall, F1-Score)

## 📦 Requirements

You can install the required libraries using:

```bash
pip install -r requirements.txt
```

### `requirements.txt`:

```txt
pandas
numpy
matplotlib
seaborn
nltk
scikit-learn
joblib
flask
```

Additionally, for `nltk`, ensure these corpora are downloaded:

```python
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
```

