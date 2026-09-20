# 🚕 Taxis Dataset Analysis Using Python
Python-based Taxis Dataset Analysis using Pandas, NumPy, Matplotlib, and Seaborn. Includes data cleaning, missing value handling, exploratory data analysis, and multiple visualizations to analyze fares, distances, tips, payment methods, and pickup locations.

## 📌 Project Overview
This project analyzes the Taxis dataset using Python to understand taxi trip patterns, fare distribution, payment methods, distance, tips, and relationships between numerical variables.
The project includes data cleaning, missing value handling, and data visualization using Pandas, Matplotlib, and Seaborn.
## 🎯 Objectives
-	Load and explore the Taxis dataset.
-	Identify and handle missing values.
-	Convert the pickup timestamp into datetime format.
-	Analyze taxi fares, distances, tips, and payment methods.
-	Create different visualizations to identify patterns and relationships.
-	Understand correlations between numerical variables.
## 🛠️ Technologies Used
-	Python
-	Pandas – Data manipulation and analysis
-	NumPy – Numerical operations
-	Matplotlib – Data visualization
-	Seaborn – Statistical data visualization
## 📂 Dataset
The dataset is loaded directly from Seaborn:
```
import seaborn as sns

df = sns.load_dataset("taxis")
```
## 🧹 Data Cleaning
The following data cleaning steps were performed:
1.	Checked the dataset for missing values.
2.	Identified columns containing missing data.
3.	Used the median to fill missing numerical values.
4.	Used the mode to fill missing categorical values.
5.	Converted the pickup column into datetime format.
6.	Verified that missing values were handled successfully.
## 📊 Visualizations
The project contains the following visualizations:
### Matplotlib / Pandas
1.	Line Chart
-	Shows fare over time using the pickup timestamp.
2.	Bar Chart
-	Displays total fare for each pickup borough.
3.	Pie Chart
-	Shows the distribution of trips based on payment method.
4.	Histogram
-	Displays the distribution of taxi trip distances.
5.	Box Plot
-	Shows the distribution of tip amounts for each pickup borough.
### Seaborn
6.	Count Plot
-	Displays the number of trips in each pickup borough.
7.	Scatter Plot
-	Shows the relationship between distance and fare.
-	Points are differentiated by pickup borough.
8.	Heatmap
-	Shows correlations between:
1.	Distance
2.	Fare
3.	Tip
4.	Tolls
5.	Total
9.	Pair Plot
-	Visualizes pairwise relationships between distance, fare, tip, and total.
-	Data points are categorized by pickup zone.
10.	Violin Plot
-	Shows fare distribution for different payment methods.
## 🔍 Key Analysis Areas
The analysis focuses on:
-	🚕 Taxi trip frequency
-	💰 Fare distribution
-	📍 Pickup borough performance
-	💳 Payment method usage
-	📏 Trip distance distribution
-	💵 Tip distribution
-	📈 Relationship between distance and fare
-	🔥 Correlation between numerical variables
## 📁 Project Structure
Taxis-Dataset-Analysis/
│
├── Taxis_Dataset_Analysis.ipynb
└── README.md
## ▶️ How to Run
1.	Install Python.
2.	Install the required libraries:
pip install pandas numpy matplotlib seaborn
3.	Open the Jupyter Notebook:
jupyter notebook
4.	Open Taxis_Dataset_Analysis.ipynb.
5.	Run the cells sequentially to perform the analysis and generate the visualizations.
## 👩‍💻 Skills Demonstrated
-	Python Programming
-	Pandas
-	NumPy
-	Data Cleaning
-	Missing Value Handling
-	Exploratory Data Analysis (EDA)
-	Matplotlib
-	Seaborn
-	Data Visualization
-	Correlation Analysis
-	Statistical Analysis
##📌 Conclusion
This project demonstrates how Python can be used to clean, analyze, and visualize real-world taxi trip data. The visualizations help identify patterns in fares, distances, payment methods, tips, and pickup locations, providing useful insights into taxi trip behavior.

## 👩‍💻 Author
Sugantha B
-	Aspiring Data Analyst | Python | SQL | Power BI | Excel

