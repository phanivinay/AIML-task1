# AIML-task1  
🧹 Task 1: Data Cleaning & Preprocessing
🎯 Objective

Learn how to clean and prepare raw data for Machine Learning models — a critical first step before building predictive models.

🧰 Tools & Libraries

Python

Pandas

NumPy

Matplotlib / Seaborn

🗂️ Dataset

I used the Titanic Dataset (you can download it from Kaggle or click here to download
)

This dataset contains information about Titanic passengers — age, gender, class, fare, survival status, etc.

⚙️ Steps Performed
1️⃣ Import & Explore Data

Loaded dataset using pandas.read_csv()

Checked for missing values and data types using .info() and .describe()

2️⃣ Handle Missing Values

Filled missing numerical data with mean/median

Imputed missing categorical values with mode

3️⃣ Encode Categorical Variables

Converted non-numeric columns (like Sex, Embarked) using Label Encoding / One-Hot Encoding

4️⃣ Normalize / Standardize Features

Scaled numerical features using StandardScaler or MinMaxScaler to ensure balanced impact

5️⃣ Detect & Handle Outliers

Visualized outliers using Boxplots (sns.boxplot())

Removed or capped extreme values

📊 Visualization Examples

Missing value heatmap – to see where data is missing

Boxplots & histograms – to understand data distribution

Correlation heatmap – to check relationships between features

💡 What I Learned

How to identify and handle missing data

Encoding techniques for categorical variables

Importance of scaling and normalization

How to detect and manage outliers

The overall data preprocessing pipeline before model training
