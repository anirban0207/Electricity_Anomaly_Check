@"
# ⚡ Electricity Bill Anomaly Checker

A simple anomaly detection project that identifies abnormal electricity usage patterns using statistical techniques.

## 📌 Problem Statement

Utility companies need to detect abnormal electricity consumption before sending bills to customers.

This project:
- Reads daily electricity usage data
- Computes rolling mean and standard deviation
- Calculates Z-scores
- Flags statistically abnormal days

---

## 🛠️ Technologies Used

- Python 3.11
- Pandas
- Matplotlib
- NumPy

---

## 📂 Project Structure

ELECTRICITY_ANOMALY_CHECK/
│
├── data/
├── notebooks/
├── src/
├── requirements.txt
└── README.md

---

## 🚀 How to Run

1. Clone the repository
2. Create a virtual environment
3. Install dependencies:

pip install -r requirements.txt

4. Open the notebook inside notebooks/
5. Run the cells step by step

---

## 📈 Future Improvements

- Add weather correlation
- Implement Isolation Forest
- Build real-time streaming version
- Add dashboard visualization
"@ | Set-Content README.md