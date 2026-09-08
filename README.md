# Isomorphic Twin Question Generator — HighScores Assignment

This repository contains a Python script developed for the HighScores.ai technical assignment. The script dynamically generates an isomorphic twin statistics question based on a box plot, calculates the Interquartile Range (IQR), plots the distribution, and outputs a structured JSON package containing options, LaTeX formulas, correct answers, and step-by-step explanations.

## 🚀 Features
* **Dynamic Generation:** Randomly generates valid statistical data points ($Q_1$, $Q_3$, Median, Min, Max) ensuring a mathematically correct Interquartile Range ($IQR = Q_3 - Q_1$).
* **Automated Plotting:** Uses `matplotlib` to render and save a clean box plot image (`isomorphic_twin_boxplot.png`).
* **Structured Output:** Exports the generated question, image path, LaTeX formula, shuffled multiple-choice options (A, B, C, D), correct option tag, and a detailed explanation in JSON format.

## 🛠️ Prerequisites
Make sure you have Python installed along with Matplotlib:
```bash
pip install matplotlib
