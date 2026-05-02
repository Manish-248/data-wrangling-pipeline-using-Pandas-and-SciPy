# 📊 Data Wrangling Techniques using Python (Pandas & SciPy)

## 🔹 Overview

This project demonstrates a complete **data wrangling pipeline** using Python.
It covers real-world data preprocessing techniques required before applying machine learning models.

The notebook is designed with **clean code, detailed explanations, and structured steps**, making it both **educational and production-ready**.

---

## 🎯 Objectives

* Understand the data science workflow
* Perform data cleaning and preprocessing
* Handle missing and inconsistent data
* Combine and transform datasets
* Prepare structured data for machine learning

---

## 🧰 Technologies Used

* Python 🐍
* Pandas
* NumPy
* SciPy
* Scikit-learn
* SQLite
* Matplotlib (basic visualization)

---

## 📂 Project Structure

```
📁 Data-Wrangling-Python/
│
├── 📓 data_wrangling_notebook.ipynb
├── 📄 README.md
├── 📁 datasets/
│   ├── iris.csv
│   ├── a_loading_example_1.csv
│   ├── a_loading_example_2.csv
│   └── a_selection_example_1.csv
```

---

## 🔥 Key Features Implemented

### ✅ 1. Data Loading

* Load datasets from CSV and URLs
* Handle headers, separators, and formats

### ✅ 2. Data Cleaning

* Fix incorrect data formats
* Handle missing values using:

  * Mean
  * Median
  * Constant values

### ✅ 3. Large Data Handling

* Chunk-based loading (`chunksize`)
* Iterator-based streaming
* Custom batch generator using `yield`

### ✅ 4. Database Integration

* SQLite database creation
* Insert and retrieve data using SQL
* Convert SQL results to Pandas DataFrame

### ✅ 5. Data Combination

* Concatenation (`pd.concat`)
* Merging (`pd.merge`)
* Reshaping (`melt`, `pivot`)

### ✅ 6. Data Analysis

* GroupBy operations
* Aggregations (mean, min, max)
* Descriptive statistics

### ✅ 7. Data Selection

* `loc` and `iloc` indexing
* Boolean filtering
* Masking and conditional updates

### ✅ 8. Categorical Encoding

* One-Hot Encoding (`pd.get_dummies`)
* Label Encoding + OneHotEncoder

### ✅ 9. Text Processing (NLP Basics)

* Bag of Words (CountVectorizer)
* Term Frequency (TF)
* TF-IDF
* N-grams (context-based features)
* Hashing Vectorizer

---

## 🧠 Key Learnings

* Data preprocessing is **80% of real-world data science**
* Clean data → Better model performance
* Efficient memory handling is crucial for large datasets
* Feature engineering significantly impacts results

---

## 📊 Sample Output

* Cleaned datasets with missing values handled
* Aggregated insights using groupby
* Encoded categorical variables
* Text transformed into numerical feature vectors

---

## ⚠️ Challenges Faced

* Handling missing and inconsistent data
* Understanding differences between `loc` and `iloc`
* Managing memory for large datasets
* Converting categorical/text data into numerical form

---

## 🚀 Future Improvements

* Add data visualization (EDA)
* Build machine learning models on processed data
* Automate preprocessing pipeline
* Deploy as a data processing API

---

## 👨‍💻 Author

**Manish Chandra**

---

## ⭐ If you found this useful

Give this repo a ⭐ and feel free to connect!
