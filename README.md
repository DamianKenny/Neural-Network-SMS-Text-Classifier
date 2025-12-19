# 📩 Neural Network SMS Text Classifier

This project implements a **Neural Network model** to classify **SMS messages** as either **ham** (normal message) or **spam** (advertisement or unwanted message). The project is built in **Python** and runs on **Google Colaboratory**.

The goal is to create a model that accurately predicts the category of any SMS message using supervised learning.

---

## 🧠 Project Overview

The SMS classifier uses a **neural network** to learn patterns in text messages that distinguish normal messages from spam.

The dataset used is the **SMS Spam Collection**, which has been pre-split into **training** and **testing** datasets.

The project includes a function:

```python
predict_message(message)
```

* **Input:** A string message
* **Output:** A list with:

  1. A number between 0 and 1 indicating probability of being **ham (0)** or **spam (1)**
  2. The predicted label: `"ham"` or `"spam"`

Example output:

```python
predict_message("Congratulations! You won a free ticket!")
# [0.87, "spam"]
```

---

## 🛠️ Technologies Used

* Python
* Google Colaboratory
* NumPy
* Pandas
* TensorFlow / Keras
* Scikit-learn

---

## ⚙️ How It Works

1. Import libraries and load pre-split train/test datasets.
2. Preprocess the text messages (tokenization, encoding, etc.).
3. Build and train a **neural network** on the training dataset.
4. Evaluate performance on the test dataset.
5. Use the `predict_message` function to classify new messages.

---

## ✅ Success Criteria

* The model correctly classifies messages as **ham** or **spam**.
* Probability output is meaningful (0 → ham, 1 → spam).
* The function `predict_message` works for unseen messages.

---

## 🚀 Getting Started

1. Open the notebook in **Google Colab**
2. Make a copy in your account
3. Run the first two cells to import libraries and load data
4. Implement preprocessing, model training, and the `predict_message` function
5. Run the final cell to test your model
6. Enable link sharing if submitting the Colab notebook

---

## 📖 Notes

* Some additional learning resources may be helpful, similar to real-world projects.
* The dataset is already pre-split for training and testing.
* Model accuracy can be visualized and fine-tuned for better performance.

---

If you want, I can also **make all three READMEs consistent in style and structure**, so your GitHub looks like a professional ML portfolio. Do you want me to do that?
