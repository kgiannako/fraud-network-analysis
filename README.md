# fraud-network-analysis
Exploring suspicious patterns in credit card transaction networks using BFS and graph analysis.

# Fraud Network Analysis with BFS and Graph Analytics

## 📊 Project Overview
This project explores fraud detection using graph-based network analysis.  
We analyze the **IEEE-CIS Fraud Detection Dataset** by constructing a transaction-entity network and applying **Breadth-First Search (BFS)** to investigate fraud clustering behavior.

---

## 🛠️ Key Features
- ✅ Transaction graph builder linking transactions to cards, devices, and other entities.
- ✅ Visualization of transaction neighborhoods.
- ✅ BFS-based fraud neighbor analysis at configurable depths.
- ✅ Statistical testing (t-test, chi-square) of fraud clustering.
- ✅ Exploratory Jupyter notebooks showcasing analysis.

---

## 🗂️ Project Structure
/data # Raw datasets (not committed)
/notebooks # Exploratory analysis notebooks

---

## 📈 Key Findings
- Fraudulent transactions exhibit significantly different network connectivity.
- At a **BFS depth of 3**, fraud transactions tend to cluster, confirmed by statistical tests.
- Node degree and fraud neighbor counts may serve as useful features for predictive models.

---

## 🚀 How to Use
1. Download the **IEEE-CIS Fraud Detection Dataset** from [Kaggle](https://www.kaggle.com/competitions/ieee-fraud-detection).
2. Place datasets inside `/data` (they are ignored by Git).
3. Run notebooks from `/notebooks` to explore or modify analysis.
4. Install required packages:
pip install -r requirements.txt


---

## 📄 License
This project is licensed under the MIT License.  
Data usage must comply with the [Kaggle Dataset Terms](https://www.kaggle.com/competitions/ieee-fraud-detection/rules).

---

## 🤝 Contributions & Feedback
Pull requests and feedback are welcome.  
If you have ideas for further exploration or improvements, feel free to open an issue!
