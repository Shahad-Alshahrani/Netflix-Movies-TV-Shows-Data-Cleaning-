# 🎬 Netflix Movies & TV Shows Data Cleaning 

## 📌 Project Overview
This project focuses on performing comprehensive Data Cleaning and Feature Engineering on the popular **Netflix** dataset. The raw data contained missing values, inconsistent duration formats, and unoptimized data types. Through a systematic cleaning process using Python, I transformed the raw dataset into a structured format ready for statistical analysis and visualization.

---

## 🖼️ Data Transformation (Before & After)

### Raw Data (Before Cleaning)

<img width="80%" height="80%" alt="raw" src="https://github.com/user-attachments/assets/70adf24b-4cde-4f46-971a-5b55767e4a3f" />


### Cleaned Data (After Processing)
<img width="80%" height="80%" alt="clean 1" src="https://github.com/user-attachments/assets/c4d991a0-b562-4e09-918e-6a0b2cda0ab3" />

<img width="80%" height="80%" alt="clean 2" src="https://github.com/user-attachments/assets/5ac8a43f-feae-4f15-8cf6-dcb8885f3a9c" />


---

## 🛠️ Data Cleaning Steps
In this project, I addressed various data quality issues using **Python** and **Pandas**:

* **Handling Missing Values**:
* Imputed missing entries in director, cast, and country with "Unknown" to preserve data integrity while acknowledging missing information.
* Removed rows with null values in critical columns like date_added and rating where imputation wasn't feasible.

* **Feature Engineering (Duration Splitting)**:
* Resolved the complexity of the duration column by splitting it into two distinct columns: duration_value (integer) and duration_unit (e.g., min, Seasons). This allows for numerical calculations on movie lengths and TV show seasons.

* **Data Type Standardization**:
* Converted newly created features into appropriate numerical types (int64) to enable mathematical analysis.

* **Dataset Export**:
* Exported the final cleaned dataset into an Excel format (.xlsx) for seamless integration with BI tools.

---

## 🛠️ Tech Stack
* **Data Source**:<a href="https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download">Kaggle</a>.
* **Language**: Python.
* **Libraries**: Pandas.
* **Environment**: Google Colab.
