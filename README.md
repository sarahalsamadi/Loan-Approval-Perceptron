# 💰 Loan Approval Prediction (Perceptron Model)

A machine learning implementation of the **Perceptron algorithm** to automate the credit decision-making process.

## 📝 Overview
This project simulates a basic AI system used by financial institutions to evaluate loan applicants. The model learns to classify applicants into 'Approved' or 'Rejected' categories by adjusting weights based on historical data.

## 🧠 Technical Implementation
* **Algorithm:** Perceptron (Single-layer Neural Network).
* **Features Used:**
  * Annual Income
  * Credit Score
  * Years of Employment
* **Optimization:** The model uses a learning rate to update weights during each 'Epoch' until the error reaches zero or the training is complete.

## ✨ Key Features
* **Data Processing:** Uses `pandas` for handling the applicant dataset.
* **Step-by-Step Learning:** The notebook visualizes how weights change after each iteration to minimize prediction errors.
* **Custom Perceptron Function:** A hand-coded implementation of the activation function and weight update rule.

## 🛠 Tech Stack
* **Language:** Python 3
* **Libraries:** `pandas`, `numpy`.
* **Platform:** Jupyter Notebook (`.ipynb`).

## 🚀 How to Run
1. Open the `loan_classification_perceptron.ipynb` file in Jupyter Notebook or Google Colab.
2. Ensure you have the `pandas` library installed.
3. Run the cells to see the training process and the final number of epochs needed for convergence.

---
*Developed as part of AI & Machine Learning studies.*
