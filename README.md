# 🎬 Netflix Movies & TV Shows Data Cleaning 

## 📌 Project Overview
This project focuses on performing comprehensive **Data Cleaning** and **Feature Engineering** on the popular **Netflix** dataset. The raw data contained missing values, inconsistent duration formats, and unoptimized data types. Through a systematic cleaning process using Python, I transformed the raw dataset into a structured format ready for statistical analysis and visualization.

---

## 🖼️ Data Transformation (Before & After)

### Raw Data (Before Cleaning)

<img width="100%" height="100%" alt="rawwwwwwwwwwww" src="https://github.com/user-attachments/assets/32e9b957-8d52-41b0-aead-0cb4458e70ec" />


### Cleaned Data (After Processing)
<img width="100%" height="100%" alt="cleannnnnnnnnnn" src="https://github.com/user-attachments/assets/8f6fefc2-eadf-4bbb-a747-48d33c71d9ff" />



---

## 🛠️ Data Cleaning Steps
In this project, I addressed various data quality issues using **Python** and **Pandas**:

* **Handling Missing Values**:
  * Imputed missing entries in `director`, `cast`, and `country` with **"Unknown"** to preserve data integrity while acknowledging missing information.
  * Removed rows with null values in critical columns like `date_added` and `rating` where imputation wasn't feasible.

* **Feature Engineering (Duration Splitting)**:
  * Resolved the complexity of the `duration` column by splitting it into two distinct columns: `duration_value` (integer) and `duration_unit` (e.g., min, Seasons). This allows for numerical calculations on movie lengths and TV show seasons.

* **Data Type Standardization**:
  * Converted newly created features into appropriate numerical types (int64) to enable mathematical analysis.

* **Dataset Export**:
  * Exported the final cleaned dataset into an Excel format (.xlsx) for seamless integration with BI tools.

---

## 🛠️ Tech Stack
* **Data Source**: <a href="https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download">Kaggle</a>.
* **Language**: Python.
* **Libraries**: Pandas.
* **Environment**: Google Colab.
