# Mental Illness detection using Sentiment Analysis

## Overview
This project uses **Reddit posts** to classify mental illnesses into five categories:
- Addiction
- Anxiety
- Autism
- Depression
- Schizophrenia

We compare the performance of **machine learning** and **deep learning** models to identify the most effective approach for mental health classification.

## Dataset
The dataset (`mental_health_pre+post_pandemic_reddit.csv`) contains 10,000 posts discussing mental health topics.

## Objective
The goal is to classify mental health conditions using:
- **Machine Learning**: k-Nearest Neighbors (k-NN) and Random Forest
- **Deep Learning**: Artificial Neural Network (ANN)

## Methodology
1. **Data Preprocessing**: Text cleaning, tokenization, lemmatization, and **TF-IDF** vectorization.
2. **Models**:
   - **k-NN**: Classifies data based on its nearest neighbors.
   - **Random Forest**: Ensemble learning using decision trees.
   - **ANN**: Built with multiple hidden layers, batch normalization, and dropout.

## How to Run
1. **Install dependencies**:
   ```bash
   pip install pandas scikit-learn nltk tensorflow matplotlib seaborn keras
   ```
2. **Clone the repo** and run the code:
   ```bash
   git clone https://github.com/yourusername/mental-health-classification.git
   ```

## Performance Metrics
We evaluated models using accuracy, precision, recall, F1-Score, and confusion matrices.

---

## License
Licensed under the MIT License.

---

Let me know if this works!
