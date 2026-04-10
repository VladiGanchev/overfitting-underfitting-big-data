# Overfitting vs Underfitting - Big Data Analysis

This project demonstrates overfitting and underfitting using Decision Tree models on a real dataset.

## Dataset
Adult Income Dataset (OpenML / UCI)
- ~48,000 records
- 14 features
- Binary classification (>50K income)

## Models
Three models with different complexity:

1. Decision Tree (max_depth=2) → Underfitting
2. Decision Tree (max_depth=5) → Balanced model
3. Decision Tree (no limit) → Overfitting

## Results

| Model | Train Accuracy | Test Accuracy | Interpretation |
|------|---------------|--------------|---------------|
| depth=2 | 0.82 | 0.82 | Underfitting |
| depth=5 | 0.85 | 0.85 | Good balance |
| no limit | 0.99 | 0.80 | Overfitting |

## Goal
To demonstrate bias-variance tradeoff and model generalization.

## Technologies
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Google Colab

## Topic
Big Data Analysis / Machine Learning  
Overfitting and Underfitting demonstration
