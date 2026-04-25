## Data Cleaning and Preprocessing
## 🚢 Task 2: Titanic Dataset 
## 🛠️ Tools:
* Python (Pandas, NumPy)
---
### 📂 Dataset:
* Titanic Dataset

---

### Data Cleaning Process:
* Handled missing values:
  - Filled Age using median, then ensured no remaining nulls using mode
  - Filled Fare using median
  - Filled Embarked using mode
* Dropped irrelevant column:
  - Removed Cabin column due to excessive missing values
* Removed duplicate records
* Validated dataset:
  - Checked missing values using isnull() / isna()
  - Confirmed no remaining null values
* Converted data types:
  - Converted Age to integer format
* Normalized numerical features:
  - Applied MinMax scaling to Age and Fare
* Handled outliers:
  - Created a reusable function for outlier removal
  - Used Interquartile Range (IQR) method
  - Removed outliers from Age and Fare
* Verified dataset integrity:
  - Checked for duplicates after cleaning
  - Ensured dataset consistency before analysis
---
### 📦 Deliverables:
* Clean dataset with:
  - No missing values
  - No duplicates
  - Normalized features
  - Reduced outliers
* Preprocessing steps implemented in the notebook
---
### 🎯 Final Outcome:
* Developed understanding of data preprocessing techniques including:
  - Handling missing values  
  - Data validation  
  - Feature scaling  
  - Outlier detection  
  - Data cleaning best practices  
---
### ❓ Interview Questions Related To Above Task:

* What is data cleaning?  
  Data cleaning is the process of identifying and fixing errors, missing values, and inconsistencies in a dataset to improve its quality.

* How to handle missing values?  
  Missing values can be handled by removing them or filling them using statistical methods such as mean, median, or mode.

* What are outliers?  
  Outliers are extreme values that differ significantly from other data points and can affect analysis results.

---
**Author:** Marianne Ongondi 
