# SCT_DS_03
# 📁 Dataset

Source: UCI Machine Learning Repository
Dataset: Bank Marketing Dataset
Files Used: bank-full.csv
This dataset contains information about marketing campaigns by a Portuguese banking institution.

# ⚙ Steps Followed
# 1. Data Preparation

Load the dataset from a ZIP archive.

Explore the dataset: check shape, data types, and null values.

Understand distribution using describe() and info().

# 2. Exploratory Data Analysis (EDA)

Countplot for the target variable (y) to check class balance.

Summary statistics and data overview.

# 3. Data Preprocessing

Convert categorical variables using Label Encoding.

Separate features (X) and target (y).

Split into train and test sets using train_test_split.

# 4. Model Building

Use DecisionTreeClassifier from sklearn.tree.

Set max_depth=5 for better visualization and overfitting control.

Train on training data.

# 5. Model Evaluation

Evaluate model using:

Accuracy

Classification Report

Confusion Matrix

Visualize confusion matrix and classification metrics.

# 6. Feature Importance

Plot feature importances to identify key drivers of the prediction (e.g., duration, poutcome, month).

# 7. Cross-Validation

Perform 5-fold cross-validation to assess model stability.

Display individual scores and mean accuracy.

# 8. Decision Tree Visualization

Plot full decision tree using plot_tree() with feature names and class labels.

✅ (Bonus) Random Forest Classifier

Also implemented a Random Forest Classifier for comparison.

Achieved better accuracy and balanced performance.

# 🔧 Tools & Libraries Used

Python 3.x

pandas

numpy

matplotlib

seaborn

sklearn

# 📌 How to Run

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn


Run the script (in Colab or locally):

python bank_marketing_classifier.py

# 📊 Key Results

Decision Tree Accuracy: ~87.6%

Top Features: duration, poutcome, month, age

Random Forest Accuracy: ~90.6%
