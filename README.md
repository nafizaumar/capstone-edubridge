# Capstone Project

# Title: Airbnb Price Recommendation

# Objective:
To build a regression model that predicts the price of Airbnb listings using various features like location, property type, number of beds, and room type.

# Project Workflow:

1. Data Collection & Cleaning 
   - Removed outliers (price > $500)
   - Dropped missing/irrelevant data
   - Filtered low-frequency property types

2. Exploratory Data Analysis (EDA)  
   - Visualized price distribution
   - Identified key features (room type, beds, property type)

3. Feature Engineering & Encoding  
   - Converted categorical features using Label Encoding

4. Model Building  
   - Applied Linear Regression model  
   - Train-test split (80:20)

5. Model Evaluation 
   - Metrics: R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)  
   - Final predicted price: $163.89

# Tools & Libraries Used:
- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

# Key Results:
- Linear Regression worked well with low prediction error  
- Room type, number of beds, and property type are major influencing features  
- Price predictions can help hosts set competitive rates

# Files in This Repo:
- `Capstone project.ipynb`: Full project code  
- `data_sydney.csv`: Dataset used for modeling  

# Future Scope:
- Use advanced regression models (e.g., XGBoost)  
- Add NLP-based features from reviews or descriptions  
- Include location-based pricing (e.g., ZIP code, tourist area)


