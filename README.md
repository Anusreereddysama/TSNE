# t-SNE Visualization Streamlit App

A Machine Learning project that demonstrates **t-Distributed Stochastic Neighbor Embedding (t-SNE)** for dimensionality reduction and data visualization using Streamlit.

## Overview

t-SNE (t-Distributed Stochastic Neighbor Embedding) is a popular unsupervised machine learning algorithm used for visualizing high-dimensional datasets by reducing them to two or three dimensions while preserving local structure.

This application allows users to explore how high-dimensional customer data can be transformed into lower-dimensional representations for better visualization and analysis.

---

## Features

- Data preprocessing pipeline
- Feature scaling using StandardScaler
- Dimensionality reduction using t-SNE
- Interactive Streamlit web interface
- Visualization of reduced dimensions
- Clean project structure
- Easy deployment on Streamlit Cloud

---

## Project Structure

```text
TSNE/
│
├── data/
│   ├── raw/
│   │   └── Mall_Customers.csv
│   │
│   └── processed/
│       └── cleaned_data.csv
│
├── models/
│   ├── scaler.pkl
│   └── tsne_data.pkl
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   ├── data_preprocessing.py
│   ├── train_model.py
│   └── transform.py
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Dataset

This project uses the Mall Customers Dataset for customer segmentation and visualization.

Dataset Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Joblib

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Anusreereddysama/TSNE.git
```

Navigate to the project directory:

```bash
cd TSNE
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Data Preprocessing

Run:

```bash
python src/data_preprocessing.py
```

This will:

- Load the raw dataset
- Select relevant features
- Clean the data
- Save processed data

---

## Train t-SNE Transformation

Run:

```bash
python src/train_model.py
```

This will:

- Scale the dataset
- Apply t-SNE dimensionality reduction
- Save transformed data

---

## Run Streamlit Application

```bash
streamlit run app.py
```

---

## Machine Learning Workflow

```text
Raw Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Scaling
      │
      ▼
t-SNE Transformation
      │
      ▼
2-Dimensional Representation
      │
      ▼
Visualization using Streamlit
```

---

## Applications of t-SNE

- Data Visualization
- Customer Segmentation Analysis
- Pattern Discovery
- Feature Exploration
- High-Dimensional Data Analysis
- Machine Learning Preprocessing

---

## Future Improvements

- Interactive Scatter Plots
- 3D t-SNE Visualization
- User Dataset Upload
- Cluster Coloring
- PCA + t-SNE Comparison
- Download Visualization Feature

---

## Learning Outcomes

Through this project, users can understand:

- Unsupervised Learning
- Dimensionality Reduction
- Feature Scaling
- Data Visualization
- t-SNE Algorithm
- Streamlit Deployment

---

## Author

Anusree Reddy

GitHub:
https://github.com/Anusreereddysama

---

## License

This project is created for educational and learning purposes.