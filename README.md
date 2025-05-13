# 📉 Recession Prediction using SVM and Linear Regression

> A forward-looking economic forecasting model that leverages **machine learning**, **regression analysis**, and **historical macroeconomic indicators** to predict upcoming recessions — all through a simple desktop app built with Python.

[![DOI](https://img.shields.io/badge/Published-IJRASET-blue)](https://doi.org/10.22214/ijraset.2023.55902)
![Python](https://img.shields.io/badge/language-Python3-yellow)
![Machine Learning](https://img.shields.io/badge/ML-SVM%20%7C%20Linear%20Regression-blue)
![UI](https://img.shields.io/badge/UI-Tkinter-lightgrey)

---

## 📌 What This Project Does

- Predicts the **likelihood of a recession** in a given year
- Uses **economic indicators** like GDP, income, employment, retail sales, and manufacturing
- Provides **model confidence scores** to show prediction reliability
- Runs as a simple, interactive **desktop GUI** using `Tkinter`
- Assists **policy-makers**, researchers, and the public in anticipating and preparing for economic downturns

> 📊 This project combines **economic theory** and **ML models** to deliver real-world insights — in real time.

---

## 🧠 Why It Matters

Recessions disrupt lives. By predicting downturns before they hit, economies can **plan ahead, preserve jobs, protect citizens, and boost resilience**.

This project empowers:
- 📈 **Economists** to monitor early trends
- 🏦 **Policy-makers** to take proactive action
- 💼 **Businesses** to strategize hiring and investment
- 👨‍💻 **Developers & students** to learn ML in finance

---

## 🔍 Features

- 📅 Input any **future year**, get real-time inflation prediction
- ⚖️ Displays output from **two different models** (SVM and Linear Regression)
- 📉 Picks the best prediction based on **confidence scores**
- 🖼️ Integrated GUI with exception handling and validation
- 📂 Dataset display option for transparency

---

## ⚙️ Tech Stack

| Component         | Tech Used                         |
|------------------|-----------------------------------|
| Language          | Python 3.6                        |
| UI Framework      | Tkinter                           |
| ML Libraries      | Scikit-learn, Pandas, Numpy       |
| Visualization     | Matplotlib                        |
| IDE               | PyCharm                           |
| Data              | Inflation data (1958–2018)        |

---

## 🧪 ML Algorithms

### 📌 Linear Regression
- Predicts inflation as a function of time (year)
- Simple, interpretable, and fast

### 📌 Support Vector Regression (SVR)
- Captures nonlinear patterns in data
- Provides an alternate prediction for better decision-making

> ✅ The system selects the more **confident model** between the two and displays its result.

---

## 🖥 How It Works

1. 🧾 User enters a **year after 2019**
2. 🧠 ML models predict the **inflation rate** for that year
3. 📊 Confidence scores for both models are shown
4. ✅ Final prediction is selected based on higher accuracy

### Test Scenarios:
- ❌ Invalid year → custom error
- ❌ Empty input → user alert
- ❌ Year < 2020 → re-entry requested
- ✅ Valid year → prediction with results from both SVM and LR

---

## 🏗 System Architecture

```plaintext
[User Input Year]
        ↓
[Data Validation & Cleaning]
        ↓
[Train-Test Split]
        ↓
[SVM Model]     [Linear Regression]
      ↓                  ↓
[Predicted Values + Confidence Score]
        ↓
[Higher Confidence → Final Result Displayed]
