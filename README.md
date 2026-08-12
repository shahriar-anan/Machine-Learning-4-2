# Machine Learning Lab — Practice Questions

## 1. Logistic Regression vs Multinomial Naive Bayes

### Question 1 — Breast Cancer Wisconsin Dataset

**Use:** Breast Cancer Wisconsin (Diagnostic) Dataset

> Given the breast cancer dataset, build a classification system to predict whether a tumor is malignant or benign.

**Requirements:**
1. Load and inspect the CSV dataset.
2. Identify the feature and target columns.
3. Handle missing values if present.
4. Perform appropriate feature preprocessing/scaling.
5. Split the data into training and testing sets.
6. Train a **Logistic Regression** classifier.
7. Train a **Naive Bayes** classifier.
8. Compare both models using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix
9. State which model performs better.

**Important exam practice:** Don't just memorize the algorithm. Practice deciding that **Logistic Regression is appropriate for binary classification** and understanding what preprocessing Naive Bayes requires.

---

### Question 2 — Wine Quality Dataset

**Use:** Wine Quality Dataset

> Predict the quality category of wine using its physicochemical properties. Compare Logistic Regression and Multinomial Naive Bayes.

**Requirements:**
1. Load the CSV dataset.
2. Convert wine quality into suitable classification classes.
3. Show the distribution of the target classes.
4. Split the dataset into training and testing sets.
5. Train Logistic Regression.
6. Train Multinomial Naive Bayes.
7. Compare using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix
8. Explain which classifier is better for the given dataset.

This is particularly good practice because **the target is multiclass**, so you have to think about how Logistic Regression handles multiclass classification.

---

## 2. SVM vs Random Forest

### Question 1 — Breast Cancer Wisconsin Dataset

**Use:** Breast Cancer Wisconsin Dataset

> Develop two classification models to diagnose breast cancer and determine which model provides better predictive performance.

**Requirements:**
1. Display the distribution of the target classes.
2. Visualize at least two feature distributions.
3. Separate features and target.
4. Split into training and testing sets.
5. Apply feature scaling where appropriate.
6. Train an **SVM** classifier.
7. Train a **Random Forest** classifier.
8. Calculate:
   - Accuracy
   - Precision
   - Recall
   - F1-score
9. Display confusion matrices for both.
10. Compare the models and determine the better classifier.

---

### Question 2 — Wine Quality Dataset

**Use:** Wine Quality Dataset

> Build a classification system for wine quality and compare SVM and Random Forest.

**Requirements:**
1. Show the distribution of wine-quality classes.
2. Investigate the distributions of the numerical features.
3. Perform necessary preprocessing.
4. Train SVM.
5. Train Random Forest.
6. Evaluate both using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix
7. Compare their performance.
8. Explain why one algorithm may perform better than the other.

This is very exam-relevant because the problem explicitly requires showing the distribution before comparing classifiers.

---

## 3. K-Means vs GMM

### Question 1 — Mall Customer Segmentation Dataset

**Use:** Mall Customer Segmentation Dataset

> Segment customers into groups using unsupervised learning and compare K-Means and Gaussian Mixture Model (GMM).

**Requirements:**
1. Load the dataset.
2. Select appropriate numerical features.
3. Standardize the features.
4. Use the **Elbow Method** to determine a suitable number of clusters for K-Means.
5. Apply K-Means clustering.
6. Apply GMM using the same number of clusters.
7. Visualize the resulting clusters.
8. Calculate:
   - Silhouette Score
   - Adjusted Rand Index, if ground-truth labels are available/constructed
9. Compare K-Means and GMM.
10. State which clustering method produces better-separated clusters.

---

### Question 2 — Mall Customer Segmentation Dataset

**Use:** Mall Customer Segmentation Dataset

> Perform customer segmentation using K-Means and GMM and determine the optimal number of clusters.

**Requirements:**
1. Plot the distribution of the selected features.
2. Standardize the data.
3. Apply K-Means for several values of K, e.g. 2–10.
4. Plot the **Elbow curve**.
5. Calculate the **Silhouette Score** for different K values.
6. Select the optimal K.
7. Apply GMM with the same number of components.
8. Compare the clusters produced by K-Means and GMM visually.
9. Compare their Silhouette Scores.
10. Give a conclusion about which clustering algorithm is preferable.

---

## 4. PCA — Showing Its Performance
### Question 1 — Dry Bean Dataset

**Use:** Dry Bean Dataset

> Apply PCA to reduce the dimensionality of the Dry Bean dataset and investigate its effect on classification performance.

**Requirements:**

1. Load the dataset.
2. Separate the features and target class.
3. Split the data into training and testing sets.
4. Train a classifier using the original features.
5. Record its performance.
6. Apply PCA to reduce the feature dimensions.
7. Plot the **explained variance ratio** and/or cumulative explained variance.
8. Determine the number of principal components required to retain approximately **90–95% of the variance**.
9. Transform the training and testing data using the selected PCA components.
10. Train the same classifier using the PCA-transformed features.
11. Compare:

    * Accuracy before PCA
    * Accuracy after PCA
    * Number of features before PCA
    * Number of principal components after PCA



### Question 2 — Breast Cancer Wisconsin Dataset

**Use:** Breast Cancer Wisconsin Dataset

> Investigate whether PCA can reduce the dimensionality of the breast cancer dataset while maintaining classification performance.

**Requirements:**
1. Load and preprocess the dataset.
2. Standardize all numerical features.
3. Train an SVM classifier using the original features.
4. Record its accuracy, precision, recall and F1-score.
5. Apply PCA.
6. Plot cumulative explained variance.
7. Select components retaining approximately 95% variance.
8. Train SVM using the PCA-transformed data.
9. Compare performance before and after PCA.
10. Visualize the first two principal components.
11. Explain whether dimensionality reduction was beneficial.
