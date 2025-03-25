# Anomaly Detection with Isolation Forest

This project demonstrates how to apply Isolation Forest for anomaly detection using the Breast Cancer Wisconsin dataset. The tutorial includes data loading, exploratory data analysis (EDA), feature scaling, training the model, and visualizing anomaly scores and outlier classification.

## Files

- isolation_forest_anomaly_detection.ipynb: Main Jupyter notebook containing code and visual outputs
- README.md: Project overview and setup instructions
- requirements.txt: Python dependencies needed to run the notebook

## Dataset

The Breast Cancer dataset is available from `sklearn.datasets`. It contains 569 samples and 30 numerical features representing various properties of digitized tumor cell nuclei. The dataset includes a binary classification label indicating malignant or benign tumors.

## Learning Objectives

- Understand the concept and intuition behind Isolation Forest
- Perform EDA to evaluate feature distributions, correlations, and class balance
- Train an Isolation Forest model to detect outliers without using label information
- Visualize anomaly scores, decision boundaries, and outlier classifications

## How to Run

1. Clone the repository or download the files
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```
   jupyter notebook isolation_forest_anomaly_detection.ipynb
   ```

## License

MIT License

## References

- Liu, F. T., Ting, K. M., & Zhou, Z.-H. (2008). Isolation forest. https://doi.org/10.1109/ICDM.2008.17
- Aggarwal, C. C. (2016). Outlier Analysis. https://doi.org/10.1007/978-3-319-47578-3
- Pedregosa, F. et al. (2011). Scikit-learn: Machine Learning in Python. http://www.jmlr.org/papers/volume12/pedregosa11a/pedregosa11a.pdf
