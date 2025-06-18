# Waste Material Segregation using CNNs

## **Overview**
This project aims to develop an **AI-based waste segregation system** using **Convolutional Neural Networks (CNNs)**. It efficiently classifies waste materials into predefined categories, enhancing recycling efficiency and promoting sustainable waste management.

## **Objective**
- **Classify waste materials** into categories like **Cardboard, Glass, Paper, Plastic, Metal, Food Waste, and Other**.
- **Improve waste segregation efficiency** to support better recycling and reduce landfill waste.
- **Analyze waste properties** to optimize sorting methods for sustainability.

## **Dataset**
- The dataset consists of **images of waste materials**, grouped into separate folders for each category.
- Some classes contain **ambiguous items**, requiring better **data preprocessing**.
- The images are **preprocessed, resized, and standardized** before training.

## **Model Architecture**
This project explores **three CNN-based models** with different configurations:
1. **Model 1:** Basic CNN with **three convolutional layers**, batch normalization, and max pooling.
2. **Model 2:** Regularized CNN with **dropout layers** for improved generalization.
3. **Model 3:** Optimized CNN with **fully connected layers** and **learning rate scheduling**.

## **Training Summary**
| Model  | Accuracy | Validation Accuracy | Overfitting Risk |
|--------|----------|----------------------|------------------|
| Model 1 | **91.8%** | **55.8%** | High |
| Model 2 | **51.6%** | **48.9%** | Moderate |
| Model 3 | **79.9%** | **60.0%** | Lower |

## **Evaluation Metrics**
- **Confusion Matrix**
- **Precision, Recall, and F1-score**
- **Validation Loss Analysis**
- **Learning Rate Adjustments**

## **Next Steps & Improvements**
- **Data Augmentation** to improve generalization.
- **Further Hyperparameter Tuning** to optimize learning.
- **Refinement in Class Definitions** for better classification accuracy.
