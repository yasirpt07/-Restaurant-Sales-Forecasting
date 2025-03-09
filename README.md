# Restaurant Sales Forecasting using Machine Learning

## Overview
This project was completed as part of a **Data Science Internship at Cognifyz Technologies**. It involves forecasting restaurant sales using machine learning techniques, data analysis, and visualization to derive insights that help in business decision-making.

## Tasks Completed
### Level 1
1. **Data Exploration & Preprocessing**
   - Checked for missing values and handled them.
   - Converted data types where necessary.
   - Analyzed the distribution of the target variable (Aggregate Rating).

2. **Descriptive Analysis**
   - Calculated statistical measures (mean, median, standard deviation, etc.).
   - Analyzed categorical variables such as Country Code, City, and Cuisines.
   - Identified top cuisines and cities with the highest number of restaurants.

3. **Geospatial Analysis**
   - Mapped restaurant locations using latitude and longitude.
   - Analyzed the distribution of restaurants across different locations.
   - Identified correlations between location and restaurant ratings.

### Level 2
4. **Table Booking & Online Delivery Analysis**
   - Determined the percentage of restaurants offering table booking and online delivery.
   - Compared average ratings of restaurants with and without table booking.
   - Analyzed online delivery availability across different price ranges.

5. **Price Range Analysis**
   - Identified the most common price ranges among restaurants.
   - Calculated the average rating for each price range.
   - Determined the highest-rated price range category.

6. **Feature Engineering**
   - Extracted additional features from existing columns (e.g., restaurant name length).
   - Created categorical features like 'Has Table Booking' and 'Has Online Delivery.'

### Level 3
7. **Predictive Modeling**
   - Built regression models (Linear Regression, Decision Trees, Random Forest) to predict restaurant ratings.
   - Split the dataset into training and testing sets.
   - Evaluated models using metrics like RMSE, MAE, and R².

8. **Customer Preference Analysis**
   - Analyzed relationships between cuisine types and restaurant ratings.
   - Identified the most popular cuisines based on customer votes.
   - Determined cuisines that tend to receive higher ratings.

9. **Data Visualization**
   - Created charts (histograms, bar plots, etc.) to represent rating distributions.
   - Compared average ratings of different cuisines and cities using visualizations.
   - Explored relationships between features and restaurant ratings.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib & Seaborn (for visualization)
- Geospatial mapping tools

## Installation
To run this project locally, install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Run
Run the Jupyter Notebook to execute the machine learning pipeline:
```bash
jupyter notebook Restaurant_Sales_Forecasting.ipynb
```

## Results
The model provides valuable sales and customer behavior insights, helping restaurant owners optimize their services and pricing strategies.

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## Author
**Mohammed Yasir Arafath**

## License
This project is open-source under the MIT License.

