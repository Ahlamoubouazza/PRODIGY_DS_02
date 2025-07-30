📊 Task-02: Data Cleaning and Exploratory Data Analysis (EDA)
✅ Objective
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice — such as the Titanic dataset from Kaggle — to explore relationships between variables, and identify meaningful patterns and trends in the data.

📁 Dataset
Sample Dataset:
Titanic Dataset - Task 2

🧪 Steps Performed
-Loading the Dataset

Imported the Titanic dataset using pandas.

-Initial Data Inspection

Checked dataset shape, data types, and missing values using .info() and .isnull().sum().

-Data Cleaning

Handled missing values in columns such as Age, Cabin, and Embarked.

Converted categorical variables to numerical if needed.

-Exploratory Data Analysis

Analyzed survival rates across different variables:

Gender

Pclass

Age Groups

Embarked Locations

Used grouping, pivot tables, and visual plots to explore relationships.

-Visualizations

Created the following plots using matplotlib and seaborn:

Bar plots (e.g., survival by class and gender)

Histograms (e.g., age distribution)

Count plots and heatmaps

📌 Key Findings
Women had significantly higher survival rates than men.

Passengers in 1st class were more likely to survive.

There is a correlation between embarkation port and survival.

Younger passengers had a slightly higher chance of survival.

🛠️ Libraries Used
pandas

numpy

matplotlib

seaborn

📸 Sample Output (Visualizations)

Replace with actual path or GitHub-hosted image link if applicable
