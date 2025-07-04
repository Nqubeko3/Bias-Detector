
# 🧠 Bias Detector: COMPAS Fairness Audit

This project performs a **bias audit** on the [COMPAS](https://github.com/propublica/compas-analysis) dataset — a widely known dataset related to criminal recidivism risk prediction — to assess and visualize **racial bias** in algorithmic decision-making.

## 📌 Project Overview

The purpose of this notebook is to:
- Audit machine learning fairness
- Identify racial bias in predictive models
- Visualize fairness metrics
- Apply bias mitigation techniques like **prejudice remover** and **rejection option classification**

## 📂 Project Structure

- `Bias_Detector.ipynb`: Main Jupyter Notebook containing code, analysis, and visualizations.
- Dataset: Assumes usage of the [COMPAS dataset](https://github.com/propublica/compas-analysis), which must be downloaded separately.

## ⚙️ Technologies Used

- Python (Google Colab compatible)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- AIF360 (AI Fairness 360 by IBM)
- Fairlearn (optional)

## 🔬 Key Features

- **Bias Detection:** Compares prediction outcomes across race groups (African-American vs. Caucasian)
- **Fairness Metrics:** Calculates Disparate Impact, Statistical Parity, Equal Opportunity Difference
- **Visualization:** Bias heatmaps and bar plots to illustrate unfair treatment
- **Mitigation:** Implements Prejudice Remover Regularizer and Rejection Option Classification to reduce bias

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn aif360
```

### How to Run
1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload or link the COMPAS dataset
3. Run each cell step-by-step
4. Review outputs for fairness insights

## 📊 Results

- The original classifier exhibits **racial bias**.
- Post-mitigation techniques show improvement across fairness metrics, although some accuracy is sacrificed.

## 🧭 Future Enhancements

- Incorporate more demographic variables (e.g., gender, age)
- Expand to other datasets with known bias
- Build an interactive dashboard to monitor fairness over time

## 🧑‍💼 Author

**Nqubeko Funda**  
Diploma in IT Support Services – WsU  
Skills: Network Configuration, Prompt Engineering, Machine Learning, AI Fine-Tuning

## 📜 License

This project is for educational purposes and adheres to ethical AI principles. Dataset © [ProPublica](https://github.com/propublica/compas-analysis).
