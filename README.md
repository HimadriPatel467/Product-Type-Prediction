# Product Type Prediction Using Neural Networks

## Abstract

This project explores the impact of hidden layer sizes in a Multi-Layer Perceptron (MLP) neural network on predicting product types using the 'supply_chain_dataset.csv' dataset. By varying hidden layer sizes from 1 to 100, the study identifies an optimal configuration for maximizing accuracy while balancing model complexity.

## Introduction

In the realm of supply chain management, predictive analytics are crucial for optimizing operations. This study focuses on neural networks, which excel at capturing complex patterns in data. The selection of appropriate hyperparameters, such as hidden layer sizes, significantly influences model performance.

## Dataset Description

The 'supply_chain_dataset.csv' dataset contains 100 records across 23 variables including Price, Availability, Number of Products Sold, and Revenue Generated. These variables provide insights into factors affecting product types within the supply chain.

## Methodology

### Data Processing
- The dataset is meticulously curated with no missing values, ensuring high integrity.
- Descriptive statistics provide an overview of key variables influencing product type prediction.

### Machine Learning Model
- **Model:** Multi-Layer Perceptron (MLP) classifier.
- **Hyperparameters Studied:** Hidden layer sizes ranging from 1 to 100.
- **Metrics:** Accuracy, Precision, Recall, F1-score, and Confusion Matrix used for evaluation.

## Results and Analysis

- Experimentation shows that moderate hidden layer sizes (around 10) yield the highest accuracy.
- Beyond certain thresholds, increasing hidden layer sizes may not significantly improve accuracy and could lead to overfitting.

## Conclusion

The study underscores the critical role of hyperparameter optimization in neural network models for supply chain applications. Finding the right balance between model complexity and performance is essential for effective product type prediction.

## References

- [Fahlman, S. E., & Lebiere, C. (1989). The cascade-correlation learning architecture. Neural Networks, 2(5), 523–545.](#)
- [LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. Nature, 521(7553), 436–444.](#)
- [Kaggle Supply Chain Analysis Dataset](https://www.kaggle.com/code/amirmotefaker/supply-chain-analysis/input)
