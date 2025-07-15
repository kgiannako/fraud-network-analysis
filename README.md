# Fraud Network Analysis with BFS & Graph Exploration

## 📝 Project Summary

This project explores the behavior of fraudulent transactions in financial networks using graph analysis techniques. We analyzed two datasets:

- **IEEE-CIS Fraud Detection Dataset (Tabular)** — Used to infer transaction-entity relationships.
- **Elliptic Bitcoin Dataset (Real Transaction Graph)** — Provided direct transaction links and class labels.

---

## 🔍 Key Analyses Performed

- **Graph Construction** — Built directed transaction graphs from real-world and tabular data.
- **BFS Exploration** — Analyzed fraud neighbor relationships within defined hop limits.
- **Connected Component Analysis** — Explored how fraud clusters within transaction networks.
- **Centrality Metrics Comparison** — Assessed the role of fraudulent transactions in network structures.

---

## 📊 Key Findings

- **Fraud Tends to Be Peripheral:**  
  Fraudulent transactions exhibit low degree, betweenness, and closeness centrality, suggesting they operate on the fringes of the transaction network.

- **No Clear Centrality-Fraud Correlation:**  
  Fraud density remained negligible across increasing centrality metrics. This suggests fraud detection models should not overly rely on classical centrality measures.

- **Large Mixed Components:**  
  In the Bitcoin dataset, frauds appear within large, mixed transaction components, often accompanied by licit and unknown nodes.

- **Limited Local Clustering:**  
  BFS exploration around fraudulent transactions showed limited direct fraud neighbor connectivity, indicating isolated or hidden fraud behavior.

---

## 📈 Visualizations & Reports

- Fraud density vs. centrality plots
- BFS neighbor explorations
- Connected component summaries
- Centrality distribution comparisons

---

## 🚀 What's Next?

- Apply community detection algorithms for potential fraud cluster discovery.
- Explore graph embeddings (e.g., Node2Vec) for pattern recognition.
- Integrate time-based transactional analysis.

---

## 🗂️ Project Structure
/data # Raw datasets (ignored in Git)
/src # Analysis scripts & graph utilities
/notebooks # Jupyter exploratory notebooks
/reports # Visual outputs and summaries

