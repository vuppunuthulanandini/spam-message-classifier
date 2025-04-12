# 📧 Spam Message Classifier

This project is a simple and effective **SMS spam classifier** built using the **Naive Bayes algorithm** in Python. It classifies text messages as either **Spam** or **Ham (Not Spam)**. The project was implemented using **Google Colab** and trained on a public dataset from **Kaggle**.

---

## 📂 Dataset

- Source: [Kaggle - SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Format: CSV file with two columns:
  - `label`: spam or ham
  - `message`: the actual text message

---

## 📌 Project Goals

- Load and clean the dataset
- Preprocess text data using `CountVectorizer`
- Train a **Multinomial Naive Bayes** classifier
- Evaluate model performance using accuracy, classification report, and confusion matrix
- Make predictions on custom input messages

---

## 🚀 Technologies Used

- Python 🐍
- Google Colab 📒
- Scikit-learn (`sklearn`)
- Pandas
- Matplotlib & Seaborn (for visualizations)

---

## 🧠 Model Performance

- **Accuracy:** ~98%
- **Precision/Recall:** High for both spam and ham classes
- **Confusion Matrix:** Shows strong separation between the two classes

---

## 🛠 How to Run

1. Download the dataset (`spam.csv`) from [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
2. Upload it to your Google Colab environment
3. Run each cell step-by-step in `spam_classifier.ipynb`
4. Optionally, test your own messages by editing the test input cell

---

## 📸 Output Preview

- ✅ Accuracy score
- 📄 Classification report
- 🔲 Confusion matrix
- 🧪 Message prediction output

---

## ✍️ Author

- **Nandini** – [GitHub](https://github.com/your-username)

---

## 📌 License

This project is open-source and available under the [MIT License](LICENSE).
