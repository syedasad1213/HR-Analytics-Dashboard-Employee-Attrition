# HR Analytics Dashboard - Employee Attrition

This project analyzes employee attrition data and builds machine learning models to predict employee turnover. The analysis is performed in the [`Employee_Data.ipynb`](Employee_Data.ipynb) Jupyter notebook using the cleaned dataset [`Cleaned_Employee_Data.xlsx`](Cleaned_Employee_Data.xlsx).

## Project Structure

- **Employee_Data.ipynb**: Main notebook for data analysis, visualization, preprocessing, and machine learning modeling.
- **Cleaned_Employee_Data.xlsx**: Cleaned dataset used for analysis and modeling.
- **HR Analytics Dashboard.pbix**: Power BI dashboard for visualizing key insights (optional, not covered in the notebook).

## Workflow Overview

1. **Exploratory Data Analysis (EDA)**
   - Data loading and inspection
   - Visualization of attrition rates and feature distributions
   - Correlation analysis

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables (label encoding, one-hot encoding)
   - Feature selection and dropping irrelevant columns
   - Balancing the dataset using SMOTE

3. **Model Training & Evaluation**
   - Decision Tree Classifier
   - Random Forest Classifier (with feature importance and threshold tuning)
   - Support Vector Machine (SVM)
   - Model evaluation using classification reports, confusion matrices, ROC AUC, and precision-recall curves
## Usage

1. Open Employee_Data.ipynb in Jupyter Notebook or VS Code.
2. Run the cells sequentially to perform EDA, preprocessing, and model training.
3. Review the outputs and visualizations to gain insights into employee attrition.

## Results

1. The notebook provides detailed analysis and comparison of different machine learning models for predicting employee attrition.
2. Feature importance and threshold tuning are included to optimize model performance.
3. So far the results prove that Random Classifier provides highest accuracy of 0.91 followed by Support Vector Machine with accuracy of 0.84.

## License

This project is for educational purposes.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- imbalanced-learn (for SMOTE)
- openpyxl (for reading Excel files)

Install dependencies with:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn openpyxl
