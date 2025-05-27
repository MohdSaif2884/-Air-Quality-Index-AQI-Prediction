Air Quality Index (AQI) Prediction Project
This project focuses on analyzing and predicting the Air Quality Index (AQI) using regression models and visualizations. It utilizes a publicly available dataset (e.g., city_day.csv) to train a model that can estimate AQI based on various environmental pollutant levels. The notebook includes steps for data preprocessing, visualization, model training, and evaluation.

🔧 Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Google Colab

📁 Dataset
The dataset used in this project typically includes the following columns:

Date

City

Pollutants like PM2.5, PM10, NO, NO2, NOx, CO, SO2, O3, etc.

AQI and AQI_Bucket (qualitative air quality level)

Make sure to upload a dataset like city_day.csv to proceed with the analysis.

🧼 Steps Performed
1. Data Upload
Upload the CSV file directly into the Colab environment.

2. Data Cleaning
Dropped rows with missing AQI values.

Remaining missing values were filled with the median of each column.

3. Data Preprocessing
Dropped non-numeric and irrelevant columns such as Date, City, and AQI_Bucket.

Scaled the features using StandardScaler.

4. Exploratory Data Analysis
Correlation heatmap to identify relationships between features and AQI.

AQI distribution plot.

Boxplot of various pollutants to identify outliers.

Time-series line chart for AQI trends in Delhi.

5. Model Training
Linear Regression model used to predict AQI.

Evaluation metrics:

Mean Squared Error (MSE)

R² Score

6. Visualization
Actual vs Predicted AQI scatter plot.

Top 20 most polluted cities bar plot based on average AQI.

📊 Sample Output
Model Performance (example output):

yaml
Copy
Edit
Mean Squared Error: 430.12
R-squared Score: 0.78
Visual Insights:

Clear trends of AQI over time.

High correlation of AQI with PM2.5 and PM10.

Identification of top polluted cities in India.

🧠 Insights
PM2.5 and PM10 are strong indicators of AQI.

Urban cities like Delhi consistently show higher AQI values.

Linear regression performs reasonably well, but more advanced models (e.g., Random Forest, XGBoost) can be explored for improved accuracy.

✅ Future Work
Implement more robust models (Random Forest, Gradient Boosting).

Add feature selection techniques.

Develop a real-time AQI prediction dashboard.

Include weather features if available for better context.

📌 How to Use
Open the notebook in Google Colab.

Run the cells sequentially.

Upload the dataset when prompted.

Analyze and interpret the visualizations and model performance.

🙌 Contributing
If you find ways to improve this project or want to explore additional features, feel free to fork the repo or open a pull request.

📬 Contact
For any queries or collaboration ideas, feel free to reach out!

