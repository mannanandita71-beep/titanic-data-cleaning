# titanic-data-cleaning
Week 1 Task - Data Acquisition, Cleaning, and Preprocessing
# Titanic Data Acquisition, Cleaning, and Preprocessing

## Week 1 Task

This project demonstrates data acquisition, cleaning, and preprocessing using the Titanic dataset.

## Dataset
Titanic Dataset from Kaggle.

## Tools Used
- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Tasks Performed
- Dataset acquisition
- Initial data exploration
- Missing value analysis
- Missing value treatment
- Duplicate checking
- Inconsistency checking
- Outlier detection using boxplots
- IQR-based outlier analysis
- Data preprocessing
- Final dataset validation

## Dataset Cleaning
- Missing Age values were replaced using the median.
- Missing Embarked values were replaced using the mode.
- Cabin was removed because of a high amount of missing data.
- Duplicate records were checked.
- Fare outliers were identified using the IQR method and retained because they may represent genuine observations.

## Final Output
The cleaned dataset was saved as `titanic_cleaned.csv`.
