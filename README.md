# 🥊 MMA Fight Outcome Predictor
A machine learning project that predicts the outcome of MMA fights using fighter statistics from Kaggle and UFCStats.com.
The model uses a Random Forest Classifier trained on cleaned and normalized performance data, such as striking, grappling, and win ratios, to estimate the probability of a fighter winning.


# 🚀 Features
Cleans and processes real-world MMA fighter data using Pandas.
Engineers performance metrics like:
  1. strike_efficiency
  2. grapple_efficiency
  3. win_ratio
  4. performance_index

Normalizes numerical features with StandardScaler.
Trains a Random Forest model to predict win likelihoods.
Allows comparison between two fighters with predicted probabilities.

# 🧠 Model
Algorithm: Random Forest (Supervised Learning)
Frameworks: scikit-learn, pandas, numpy
Evaluation: Accuracy score, classification report, feature importance visualization.

# 🧩 Tech Stack
Python
Pandas
NumPy
Scikit-learn
Google Colab
