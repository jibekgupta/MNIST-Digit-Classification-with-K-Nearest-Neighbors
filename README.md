# MNIST Digit Classification with K-Nearest Neighbors(KNN)

A comprehensive implementation of K-Nearest Neighbors classifier for handwritten digit recognition on the MNIST dataset, achieving 97%+ accuracy through systematic hyperparameter optimization.

**Key Achievement:** 97%+ test accuracy on MNIST dataset using optimized KNN classifier.

### 📊 Results

- **Test Accuracy:** 97%+
- **Best Parameters:** Found through systematic grid search
- **Cross-Validation:** 3-fold CV for robust model selection
- **Dataset:** MNIST (70,000 handwritten digit images)

### 🛠️ Technologies Used

- **Python 3.7+**
- **scikit-learn** - Machine learning algorithms and tools
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

### 📈 Implementation Highlights
**1. Data Preprocessing**

- Pixel normalization (0-1 range)
- Strategic subset sampling for computational efficiency
- Stratified train-test split to maintain class distribution

**2. Hyperparameter Optimization**

- **Grid Search Parameters:**
  - n_neighbors: [3, 5, 7, 9, 11, 13, 15]
  - weights: ['uniform', 'distance']


- **Cross-validation:** 3-fold CV for robust evaluation
- **Scoring metric:** Accuracy

**3. Model Evaluation**

- Comprehensive performance metrics (precision, recall, F1-score)
- Confusion matrix analysis
- Per-class performance breakdown
- Error analysis with misclassified examples

### 📊 Key Results

```bash
  FINAL RESULTS
Test Accuracy: 97.05% 
Best Parameters: {'n_neighbors': 3, 'weights': 'distance'}
Cross-Validation Score: 96.60%
```

### 📚 Educational Context
This project is based on exercises from **"Hands-On Machine Learning"** by Aurélien Géron, demonstrating practical application of machine learning concepts through industry-standard workflows.
