Data cleaning is a crucial step in the data preprocessing pipeline, ensuring that datasets are accurate, consistent, and ready for analysis. Here are some common data cleaning techniques:

1. **Handling missing values**:
   
   - **Deletion**: Remove rows or columns with missing values.
   - **Imputation**: Fill missing values with a statistical measure like mean, median, or mode.
   - **Prediction**: Predict missing values based on other features using algorithms like K-nearest neighbors or regression.

2. **Handling duplicate data**:
   
   - **Identifying duplicates**: Find and remove exact or near-duplicate records.
   - **Deduplication**: Keep only one instance of each unique record.

3. **Data transformation**:
   
   - **Normalization**: Scale numeric features to a standard range (e.g., 0 to 1).
   - **Standardization**: Transform data to have a mean of 0 and a standard deviation of 1.
   - **Log transformation**: Convert skewed data distributions to a more symmetrical form using logarithmic functions.

4. **Outlier detection and removal**:
   
   - **Statistical methods**: Identify outliers using z-scores, quartiles, or box plots and remove or adjust them.
   - **Machine learning-based methods**: Use clustering or anomaly detection algorithms to find outliers.

5. **Data formatting**:
   
   - **Standardization**: Ensure consistent formats for dates, currency, units, etc.
   - **Parsing**: Splitting data from one column into multiple columns (e.g., separating full names into first and last names).

6. **Handling inconsistent data**:
   
   - **Data validation**: Check for inconsistencies, such as conflicting information in different columns.
   - **Correction**: Manually or programmatically correct errors in the data.

7. **Handling categorical data**:
   
   - **One-hot encoding**: Convert categorical variables into binary vectors.
   - **Label encoding**: Convert categorical variables into numerical labels.
   - **Ordinal encoding**: Convert categorical variables with order into numerical labels preserving the order.

8. **Feature engineering**:
   
   - **Creating new features**: Derive new features from existing ones to improve model performance.
   - **Aggregation**: Combine multiple features into one (e.g., calculating averages, sums).

9. **Data anonymization and masking**:
   
   - **Removing sensitive information**: Replace or remove personally identifiable information (PII) to protect privacy.
   - **Generalization**: Replace specific values with more general ones to anonymize data.

10. **Data validation**:
    
    - **Cross-field validation**: Check for consistency between different fields.
    - **Business rule validation**: Ensure data adheres to predefined business rules.

These techniques can vary depending on the nature of the data and the specific requirements of the analysis or modeling task. It's often necessary to use a combination of these techniques to effectively clean and prepare the data for analysis.
