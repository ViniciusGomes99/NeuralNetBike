# Bike Rental Prediction using Neural Network

In this Machine Learning project, a neural network is employed to develop a regression model that predicts the number of rented bikes. The dataset utilized contains daily bike rental data spanning a 2-year period. The variables include temperature, air humidity, wind speed, as well as qualitative factors such as season, month, day of the week, holidays, working days, and weather conditions.

## Reference
- Hadi Fanaee-T
- Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto
- INESC Porto, Campus da FEUP Rua Dr. Roberto Frias, 378 4200 - 465 Porto, Portugal

## Steps

### Step 1: Import Libraries
The necessary libraries, including TensorFlow, pandas, numpy, seaborn, and matplotlib, are imported.

### Step 2: Import Dataset
The dataset is loaded, and basic information and descriptive statistics are displayed.

### Step 3: Data Cleaning
The dataset is checked for null values, and certain columns are dropped. Date-related columns are converted, and the dataset is indexed accordingly.

### Step 4: Data Visualization
A heatmap is plotted to visualize correlations between different variables.

### Step 5: Data Processing
Qualitative variables are processed using one-hot encoding, and the dataset is concatenated for further analysis.

### Step 6: Model Building and Training
A neural network model is constructed using TensorFlow's Keras API. The model is compiled and trained using the Adam optimizer and mean squared error loss.

### Step 7: Model Evaluation
The loss progress during training is visualized. The model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).

## Evaluation Metrics
The model achieves a coefficient of determination (R²) of 71.69%, indicating its ability to explain 71.69% of the variance in the dependent variable based on the included independent variables.

## Contact Information
For any queries or feedback, please contact me trought my [Linkedin](https://www.linkedin.com/in/vinicius-capozzi)
