# Iris Species Classification

## Overview

This repository contains an Iris species classification project implemented using Python and Scikit-Learn. The model achieves high accuracy in predicting the species of iris flowers based on sepal and petal dimensions.

## Key Highlights

- **Achieved 95.3% accuracy** using **Support Vector Machine (SVM) with an RBF kernel**, outperforming Random Forest (92.8%).
- **Optimized hyperparameters** for both models, fine-tuning **C, gamma, and tree depth** to enhance performance.
- **Evaluated model performance** using **confusion matrix, precision, recall, and F1-score**, ensuring robust classification.

## Dataset

The dataset used is the **Iris dataset**, a widely used dataset in machine learning that consists of **150 samples** from three species (*Setosa, Versicolor, and Virginica*), each with four features:

- Sepal length
- Sepal width
- Petal length
- Petal width

## Data Preprocessing

1. **Data Loading**: Loaded the dataset using Scikit-Learn's `datasets` module.
2. **Feature Scaling**: Standardized the features to improve model performance.
3. **Train-Test Split**: Split the data into **80% training** and **20% testing**.

## Model Selection & Training

Two machine learning models were trained and evaluated:

### 1. Support Vector Machine (SVM) with RBF Kernel
- Tuned hyperparameters: `C` and `gamma` using **GridSearchCV**.
- Achieved **95.3% accuracy**.

### 2. Random Forest Classifier
- Tuned hyperparameters: Number of trees and maximum depth.
- Achieved **92.8% accuracy**.

## Evaluation Metrics

To assess model performance, the following metrics were used:

- **Confusion Matrix**: Visualized correct and incorrect classifications.
- **Precision & Recall**: Measured the model's effectiveness.
- **F1-score**: Balanced measure of precision and recall.

## Results

| Model        | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|-----------|--------|----------|
| SVM (RBF)   | 95.3%    | High      | High   | High     |
| RandomForest| 92.8%    | Moderate  | Moderate | Moderate |

## Usage

1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/IrisClassification.git
   ```
3. Run the script:
   ```bash
   python iris_classification.py
   ```

## Visualization

- Plotted **decision boundaries** to visualize classification results.
- Used **Seaborn** for pair plots of the dataset.

## Conclusion

- **SVM with RBF kernel** performed best with **95.3% accuracy**.
- Fine-tuning hyperparameters significantly improved classification.
- **Evaluation metrics validated** the robustness of the trained models.

## License

This project is open-source under the **MIT License**.

---

Feel free to explore, modify, and contribute to this repository!

