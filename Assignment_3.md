Normalization and Standardization in Data Science
1. Normalization

Definition: Normalization is a data preprocessing technique used to scale numerical data into a fixed range, usually between 0 and 1. It helps bring different data values into a common range and makes data easier to compare and analyze.

Advantages:

- Makes data values comparable.
- Improves the performance of some machine learning algorithms.
- Helps prevent features with larger values from dominating others.

Disadvantages:

- Highly affected by outliers.
- Requires minimum and maximum values.
- New data may need to be rescaled when the data range changes.

2. Standardization

Definition:Standardization is a data preprocessing technique used to transform numerical data so that its mean becomes 0 and standard deviation becomes 1. It helps make different features comparable and is useful in many machine learning algorithms.

Advantages:

- Makes features comparable.
- Useful for algorithms like SVM, PCA, and Logistic Regression.
- Maintains the relative distribution of data values.

Disadvantages:

- Does not produce a fixed range.
- Can be affected by outliers.
- Requires calculation of mean and standard deviation.
