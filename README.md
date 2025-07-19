# Electric Vehicle Adoption Forecasting

A comprehensive analysis and forecasting project for Electric Vehicle (EV) adoption trends across different counties and states using machine learning techniques.

## 📊 Project Overview

This project analyzes electric vehicle population data by county to understand adoption patterns and forecast future EV trends. The analysis includes data exploration, preprocessing, outlier detection, and predictive modeling using Random Forest Regression.

## 🗂️ Dataset

**File:** `Electric_Vehicle_Population_Size_History_By_County_.csv`

The dataset contains historical electric vehicle population data with the following key features:

- **Date**: Time period of the data
- **County**: Geographic county information
- **State**: Geographic state information
- **Electric Vehicle (EV) Total**: Total number of electric vehicles
- **Percent Electric Vehicles**: Percentage of EVs in the region

## 🔧 Technologies Used

- **Python 3.x**
- **Data Analysis**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn
  - RandomForestRegressor
  - RandomizedSearchCV for hyperparameter tuning
- **Data Preprocessing**: LabelEncoder
- **Model Persistence**: joblib

## 📈 Analysis Components

### 1. Data Exploration

- Dataset overview and structure analysis
- Missing value detection and handling
- Data type validation

### 2. Outlier Detection & Treatment

- Interquartile Range (IQR) method for outlier identification
- Outlier capping technique to preserve data while reducing skew
- Statistical boundary analysis (Q1, Q3, IQR)

### 3. Data Preprocessing

- DateTime conversion and validation
- Missing value imputation
- Feature encoding for categorical variables
- Data cleaning and preparation

### 4. Machine Learning Model

- **Algorithm**: Random Forest Regressor
- **Hyperparameter Optimization**: RandomizedSearchCV
- **Evaluation Metrics**:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared Score

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### Running the Analysis

1. Clone this repository
2. Ensure the dataset `Electric_Vehicle_Population_Size_History_By_County_.csv` is in the project directory
3. Open and run the Jupyter notebook `EV_Adoption_Forecasting.ipynb`

## 📁 Project Structure

```
├── Electric_Vehicle_Population_Size_History_By_County_.csv  # Dataset
├── EV_Adoption_Forecasting.ipynb                          # Main analysis notebook
├── .gitignore                                              # Git ignore file
└── README.md                                               # Project documentation
```

## 🎯 Key Features

- **Comprehensive Data Analysis**: Thorough exploration of EV adoption patterns
- **Robust Outlier Handling**: Statistical methods for data quality improvement
- **Predictive Modeling**: Machine learning approach for forecasting EV trends
- **Visualization**: Clear charts and graphs for data insights
- **Model Optimization**: Hyperparameter tuning for improved accuracy

## 📊 Results & Insights

The analysis provides insights into:

- Historical EV adoption trends by county and state
- Percentage growth patterns in electric vehicle adoption
- Predictive forecasts for future EV population growth
- Geographic variations in EV adoption rates

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or additional analysis features.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or suggestions regarding this analysis, please feel free to reach out through GitHub issues.

---

_This project was developed as part of data analysis and machine learning studies, focusing on sustainable transportation trends and electric vehicle adoption forecasting._
