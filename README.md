# Basketball Playoffs Prediction Project Structure

**2024 MEIC - 1st Semester**  
**Course:** Machine Learning
**Grade:** TBD

## Project developed by:
- Gonçalo Matias
- Tomás Monteiro

## 1. Project Organization

### Project Structure
```
basketball_playoffs_predictions/
│
├── data/
│   ├── basketballPlayoffs/            # Original data files
│   ├── basketballPlayoffs_cleaned/    # Cleaned Data
│   ├── basketballPlayoffs_model/      # Data for the model development
│   └── Season_11/                     # Data used for the 11th year predictions.
│
└── src/
    ├── notebook_1                     # Data Loading
    ├── notebook_2                     # Data Preprocessing
    ├── notebook_3                     # Exploratory Data Analysis
    ├── notebook_4                     # Feature Engineering
    ├── notebook_5                     # Model Development
    └── notebook_6                     # Model Development for predicitions
```

## 2. Key Considerations for Each Notebook

### 01_data_loading.ipynb
- Introduction to the problem
- Initial import of libraries
- Initial data analysis

### 02_data_preprocessing.ipynb
- Map categorical values
- Data cleaning
- Outlier treatment

### 03_exploratory_data_analysis.ipynb
- Analyze trends
- Data visualization
- Create meaningful visualizations

### 04_feature_engineering.ipynb
- Calculate overall feature creation to simplify the problem
- Document feature creation logic
- Validate feature importance

### 05_model_development.ipynb
- Split data into training and testing sets to predict year 10
- Create and train models
- Analyze and save results

### 06_model_evaluation_for_predicitons.ipynb
- Load data for the new year
- Add previously calculated features (overalls)
- Develop and train the model for competition