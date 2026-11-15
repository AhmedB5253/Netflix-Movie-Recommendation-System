# 🎬 Netflix Movie Recommendation System

A Machine Learning-based movie recommendation system developed using Python and Singular Value Decomposition (SVD).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/Netflix-Movie-Recommendation-System/blob/main/Netflix_Recommendation_Engine.ipynb)

## 📌 Project Overview

This project aims to build a personalized movie recommendation engine that predicts user ratings and recommends movies based on historical user-rating patterns.

The system uses Collaborative Filtering and Singular Value Decomposition (SVD) to learn hidden relationships between users and movies.

## 🎯 Objectives

- Analyze movie rating data.
- Perform data preprocessing and exploratory data analysis.
- Implement Collaborative Filtering using SVD.
- Predict ratings for unrated movies.
- Generate personalized movie recommendations.
- Evaluate model performance using RMSE and MAE.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Surprise
- Machine Learning

## 📂 Project Structure

```text
Netflix-Movie-Recommendation-System/
│
├── Netflix_Recommendation_Engine.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── Dataset instructions
│
├── reports/
│   └── Netflix_Project_Report.pdf
│
└── images/
    └── Project visualizations
```

## 📊 Dataset

The project uses Netflix historical movie rating data.

The rating dataset contains:
- User ID
- Movie ID
- Rating
- Date

A sample of 200,000 rating records was used for initial experimentation.

The supplied `movies.csv` metadata was analyzed separately because its movie ID system is not directly compatible with the Netflix rating dataset.

## ⚙️ Methodology

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Preparation
5. Collaborative Filtering
6. SVD Model Training
7. Model Evaluation
8. Personalized Movie Recommendations

## 🧠 Algorithm

**Singular Value Decomposition (SVD)**

SVD is a matrix factorization technique that learns latent user and movie factors from historical rating interactions.

These learned factors are used to predict ratings for movies that users have not rated.

## 📈 Initial Model Performance

| Evaluation Metric | Score |
|---|---:|
| RMSE | 1.003243 |
| MAE | 0.808518 |

These are the initial model results on the held-out test dataset.

## 🎥 Sample Recommendations

| Movie ID | Predicted Rating |
|---:|---:|
| 2102 | 4.565113 |
| 3046 | 4.535007 |
| 2452 | 4.511295 |
| 2057 | 4.363807 |
| 2172 | 4.323556 |

The model generated these predictions for a selected user using the sampled rating dataset.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Upload the required datasets.
4. Install the dependencies.
5. Execute the notebook cells sequentially.

## 📦 Installation

```bash
pip install -r requirements.txt
```

## 🔮 Future Improvements

- Hyperparameter optimization.
- Hybrid recommendation systems.
- Integration of compatible movie metadata.
- Interactive recommendation dashboard.
- Improved recommendation ranking evaluation.
- Larger-scale model training.

## 👨‍💻 Author

**Ahmed Bhawrasa Wala**

BCA Student | Aspiring Data Analyst | AI & Machine Learning Enthusiast

## 📄 Disclaimer

This is an educational machine learning project developed for academic and portfolio purposes. Recommendation scores are experimental predictions and do not represent official Netflix recommendations.
