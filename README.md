# 📧📱 Email / SMS Spam Detector (Machine Learning Project)

This is a **basic end-to-end Machine Learning project** that detects whether a given **Email or SMS message is Spam or Not Spam** using Natural Language Processing (NLP) and a trained ML model.

The project includes **data preprocessing, model training, saving the model, and deploying it using a Flask web app**.

---

## 🚀 Project Overview

Spam messages are a common problem in emails and SMS.
This project uses **Machine Learning and NLP techniques** to automatically classify messages as:

* ✅ **Not Spam (Ham)**
* 🚫 **Spam**

The trained model is integrated into a **Flask web application** where users can enter a message and get instant predictions.

---

## 📂 Project Structure

```
├── templates/
│   └── index.html        # Frontend HTML file
├── app.py                # Flask application
├── model.ipynb           # Model training & experimentation
├── spam.csv              # Dataset used for training
├── finalized_model.sav   # Trained ML model
├── tfidf_vectorizer.pkl  # Saved TF-IDF vectorizer
├── README.md             # Project documentation
```

---

## 📊 Dataset Information

* **File:** `spam.csv`
* Contains labeled SMS/Email messages
* Labels:

  * `spam`
  * `ham` (not spam)

---

## 🧠 Machine Learning Workflow

1. **Data Loading**
2. **Text Cleaning & Preprocessing**
3. **Feature Extraction using TF-IDF**
4. **Model Training**
5. **Model Evaluation**
6. **Saving Model & Vectorizer**
7. **Web App Integration using Flask**

---

## 🛠 Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **NLTK**
* **Flask**
* **HTML/CSS**
* **Pickle**

---

## 📌 Model Training

The ML model is trained inside:

📄 `model.ipynb`

Steps include:

* Removing stopwords
* Text vectorization using **TF-IDF**
* Training a classification model
* Saving the trained model and vectorizer

Saved files:

* `finalized_model.sav`
* `tfidf_vectorizer.pkl`

---

## 🌐 Flask Web Application

* **File:** `app.py`
* Takes user input (Email/SMS text)
* Loads the saved model and vectorizer
* Predicts whether the message is **Spam or Not Spam**
* Displays result on the web page

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

*(If `requirements.txt` is not available, install manually)*

```bash
pip install flask pandas numpy scikit-learn nltk
```

### 3️⃣ Run the Flask App

```bash
python app.py
```

### 4️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 🧪 Example Output

**Input:**

```
Congratulations! You have won a free prize. Click now!
```

**Prediction:**

```
Spam 🚫
```

---

## 🎯 Project Purpose

* Learn **Machine Learning basics**
* Understand **NLP workflows**
* Practice **model deployment**
* Build confidence with **end-to-end ML projects**

---

## 📌 Future Improvements

* Add model accuracy display
* Improve UI design
* Add email file upload support
* Deploy on cloud (Heroku / Render)

---

## 🙌 Acknowledgment

This project is built for **learning and practice purposes**, focusing on beginner-friendly implementation of Machine Learning concepts.

