# 🏥 Medical Insurance Analysis

## 📌 About the Project
This project focuses on exploring and analyzing a medical insurance dataset using Python. The analysis investigates demographic, health-related, and lifestyle factors and their relationship with medical insurance charges.
The project includes **Exploratory Data Analysis (EDA), data preprocessing, feature engineering, visualization, and correlation analysis**.

## 🎯 Objectives
* Understand the structure and characteristics of the insurance dataset.
* Perform exploratory data analysis.
* Analyze numerical and categorical variables.
* Identify potential outliers and distribution patterns.
* Transform categorical variables for analysis.
* Create BMI-based categories.
* Analyze relationships between different features and insurance charges using correlation analysis.


## 📊 Dataset
The dataset contains **1,338 records and 7 features**.

| Feature    | Description                   |
| ---------- | ----------------------------- |
| `age`      | Age of the individual         |
| `sex`      | Gender                        |
| `bmi`      | Body Mass Index               |
| `children` | Number of children/dependents |
| `smoker`   | Smoking status                |
| `region`   | Residential region            |
| `charges`  | Medical insurance charges     |


## 🔎 Exploratory Data Analysis
The notebook performs analysis using:

* Dataset inspection
* Descriptive statistics
* Histograms
* Box plots
* Distribution analysis
* Outlier analysis
* Feature relationship analysis

The distributions of variables such as **age, BMI, children, and insurance charges** are explored using visualizations.

## 🧹 Data Preprocessing
The project includes preprocessing of categorical variables.
Examples include:
* Transforming `sex` into `is_female`
* Transforming `smoker` into `is_smoker`
* One-hot encoding the `region` variable

These transformations prepare the data for further statistical and machine learning analysis.

## 🛠️ Feature Engineering
BMI is transformed into categorical groups to make BMI-related patterns easier to analyze.
The processed dataset contains BMI category features such as:
* `bmi_category_Normal`
* `bmi_category_Overweight`
* `bmi_category_Obese`
## 📈 Correlation Analysis

Pearson correlation analysis is performed to investigate the relationship between the available features and `charges`.
The analysis considers variables including:
* Age
* BMI
* Children
* Smoking status
* Gender
* Region
* BMI categories

The correlations are organized and sorted to identify features showing stronger relationships with insurance charges.

## 🧰 Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

## 📂 Project Structure
```text
medical-insurance-analysis/
│
├── insurance.ipynb
├── insurance.csv
└── README.md
```

## ▶️ How to Run
### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/medical-insurance-analysis.git
```
### 2. Navigate to the project
```bash
cd medical-insurance-analysis
```
### 3. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```
### 4. Open the notebook
```bash
jupyter notebook
```
Open:
```text
insurance.ipynb
```
Make sure `insurance.csv` is located in the same directory.

## 📚 Key Learning Outcomes
* Exploratory Data Analysis
* Data preprocessing
* Categorical encoding
* Feature engineering
* Data visualization
* Outlier analysis
* Correlation analysis
* Working with real-world datasets

## 👩‍💻 Author
**Divya Kumari**


## 📜 License

This project is created for educational and learning purposes.
