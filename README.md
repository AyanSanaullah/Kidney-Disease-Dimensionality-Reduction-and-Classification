# Kidney Disease Dimensionality Reduction and Classification

This project focuses on applying dimensionality reduction techniques and classification models to a kidney disease dataset. By implementing PCA, Kernel PCA, and SVD from scratch and using libraries like Scikit-learn, we aim to compare their performance and evaluate the accuracy of models using these techniques.

---

## Features
- **Dimensionality Reduction**:
  - Principal Component Analysis (PCA) from scratch and using Scikit-learn.
  - Kernel PCA with RBF, Polynomial, and Linear kernels from scratch.
  - Singular Value Decomposition (SVD) implementation.
- **Classification**:
  - K-Nearest Neighbors (KNN) classifier for accuracy evaluation.
  - Feature transformation using various dimensionality reduction techniques.
- **Dataset Preprocessing**:
  - Missing value imputation using mean strategy.
  - Feature scaling using standardization.

---

## Dataset
The project uses the **Kidney Disease dataset**, stored as `Kidney.csv`.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AyanSanaullah/Kidney-Disease-Dimensionality-Reduction-and-Classification/
   cd https://github.com/AyanSanaullah/Kidney-Disease-Dimensionality-Reduction-and-Classification/
   ```
2. Install the required Python packages

---

## Usage

1. Update the dataset path in the script:
   ```python
   file_path = "C:\\path\\to\\Kidney.csv"
   ```

2. Run the script:
   ```bash
   python kidney_disease_data_analysis.ipynb
   ```

3. The results will include:
   - Explained variance for each method.
   - Number of components required to retain 95% variance.
   - Classification accuracy for different transformations.

---

## Key Outputs

### Dimensionality Reduction
- **PCA**: Number of components for 95% explained variance.
- **Kernel PCA**: Explained variance with RBF, Polynomial, and Linear kernels.
- **SVD**: Normalized explained variance.

### Classification Results
- Best accuracy scores and optimal number of components for:
  - PCA
  - Kernel PCA with RBF, Polynomial, and Linear kernels
  - SVD

---

## Dependencies
- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install dependencies with:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```


---

## Future Work
- Add more datasets for benchmarking.
- Experiment with other classifiers (e.g., SVM, Random Forest).
- Visualize clustering performance with dimensionality reduction.

---

## License
This project is licensed under the [Apache 2.0 License](LICENSE).
