Name : Likhitha Sompalli
Company : CODTECH IT SOLUTIONS
ID : CT12DS345
Domain : Data Analytics
Duration : Jun 1st to July 30th 2024
Mentor : G.Sravani

Overview of the Project:

Project: EXPLORATORY DATA ANALYSIS (EDA)
Objective: The objective of this project is to perform Exploratory Data Analysis (EDA) on a dataset to understand its characteristics, distributions, correlations, and outliers. This analysis will help in gaining insights into the data, identifying patterns, and preparing for further analysis or modeling.

Key Activities: 
1)Data Collection and Loading: Select and load a dataset into a pandas DataFrame.
2)Initial Exploration: Get an overview of the data using methods like head(), info(), and describe().
3)Missing Value Analysis: Check for and visualize missing values.
4)Distribution Analysis: Visualize the distribution of numerical features using histograms and KDE plots.
5)Correlation Analysis: Analyze and visualize correlations between features using a correlation matrix and heatmap.
6)Scatter Plot Analysis: Explore relationships between key features and the target variable using scatter plots.
7)Outlier Detection: Identify and visualize outliers using boxplots.

Technologies Used
Python: Programming language used for data analysis.
Pandas: Library for data manipulation and analysis.
NumPy: Library for numerical computing.
Matplotlib: Library for data visualization.
Seaborn: Library for statistical data visualization.
Scikit-learn: Library for machine learning and data mining (for dataset loading).

Key Insights
1)Initial Exploration:
The dataset contains 20,640 entries with 9 features.
There are no missing values in the dataset.
2)Distribution Analysis:
Most features like MedInc, HouseAge, AveRooms, AveBedrms, Population, and AveOccup exhibit skewed distributions.
The target variable MedHouseVal (Median House Value) is right-skewed, indicating that most houses are priced lower with a few very high-priced houses.
3)Correlation Analysis:
MedHouseVal has a strong positive correlation with MedInc (Median Income) and moderate correlations with HouseAge and AveRooms.
There is a strong negative correlation between AveRooms and AveBedrms, indicating that areas with more rooms per house tend to have fewer bedrooms per house.
4)Scatter Plot Analysis:
MedHouseVal increases with an increase in MedInc.
There is a slight positive relationship between MedHouseVal and HouseAge.
AveRooms and AveOccup do not show strong relationships with MedHouseVal.
5)Outlier Detection:
Boxplots reveal outliers in features like AveRooms, AveBedrms, Population, and AveOccup.
These outliers might need to be addressed depending on the analysis or modeling approach.
