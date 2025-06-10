# 🚗 Vehicle Clustering with KMeans

This project demonstrates how to use **KMeans Clustering** (an unsupervised machine learning algorithm) to group vehicles based on characteristics such as weight, engine size, and horsepower.

The goal is to identify natural groupings or clusters in the data without using any predefined labels.

---

## 📊 Dataset

A **synthetic dataset** is generated with the following features:

- `Weight` — Vehicle weight in kilograms (1000–3000 kg)
- `EngineSize` — Engine displacement in liters (1.0–4.0 L)
- `Horsepower` — Engine power output (50–300 HP)

---

## 📌 Features

- Synthetic data generation using NumPy and pandas
- Clustering with `KMeans` from Scikit-learn
- Visualization of clusters using Matplotlib
- No labeled data required (unsupervised learning)

---

## 📁 Files

- `vehicle_clustering.py` — Main script for data generation, clustering, and plotting
- `README.md` — Project documentation
