

# DeliveryTimePredictor-RF

## Project Overview
"DeliveryTimePredictor-RF" is a machine learning project aimed at predicting the delivery times for a food delivery service using the Random Forest algorithm. This project focuses on enhancing delivery efficiency and aligning predictions with key business performance indicators.

## Purpose
The primary goal of this project is to develop a predictive model that can provide accurate delivery time estimates. This is crucial in improving customer satisfaction, operational efficiency, and overall service quality in the food delivery sector.

## Methodology

## Data Collection and Preprocessing

### Dataset Description
The dataset for this project was sourced from Kaggle, courtesy of Bhanupratap Biswas. It encompasses a rich set of features crucial for predicting delivery times in the food delivery industry, including:

- **Delivery Person's Age**: Reflecting the age of the delivery personnel.
- **Delivery Person's Ratings**: Indicative of the performance and reliability of the delivery personnel.
- **Type of Order**: Categories of the orders (such as Buffet, Drinks, Meal, Snack), impacting preparation and delivery times.
- **Region**: The geographical area of the delivery, influencing delivery duration due to factors like distance and traffic conditions.
- **Historical Delivery Times**: Previous records of delivery durations, serving as essential training data for the model.

You can access the dataset [here](https://www.kaggle.com/datasets/bhanupratapbiswas/food-delivery-time-prediction-case-study/data).

### Preprocessing Steps
The dataset underwent several preprocessing steps to prepare it for the Random Forest model:

1. **Data Extraction and Cleaning**: Extracting relevant data and addressing any inaccuracies or inconsistencies, such as missing values or outliers.
2. **Encoding Categorical Variables**: Utilizing OneHotEncoder to transform categorical variables like 'Type of Order' and 'Region' into a format suitable for the model.
3. **Normalizing Numerical Features**: Applying StandardScaler to numerical features like 'Delivery Person's Age' and 'Ratings' to standardize their range.
4. **Data Splitting**: Dividing the dataset into training and test sets to both train the model and evaluate its performance on unseen data.

### Model Development
- A Random Forest model was chosen for its ability to handle complex datasets and its robustness against overfitting.
- The model was trained on historical data, with hyperparameter tuning for optimization.

### Model Evaluation
- The model's performance was evaluated using metrics such as Mean Squared Error (MSE).
- Predictions were compared against actual delivery times to assess accuracy.

## How to Run the Code
1. **Clone the Repository**:
   ```
   git clone https://github.com/ahrar-azmat/DeliveryTimePredictor-RF.git
   ```
2. **Install Required Libraries**:
   - Ensure Python is installed on your system.
   - Install necessary libraries using pip:
     ```
     pip install -r requirements.txt
     ```
3. **Run the Jupyter Notebooks**:
   - Navigate to the project directory and launch Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - Open the `.ipynb` file and run the cells sequentially.

## Contributions
Contributions to this project are welcome! 

