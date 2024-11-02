# Python Programming for Data Science Course

Welcome to the repository for the **Python Programming for Data Science Course**!

This course introduces Python programming tailored for data analysis, exploration, and predictive modeling, covering statistical techniques, data visualization, and machine learning methods. Python is used to extract insights from data, making it one of the most popular languages in Data Science.

## Course Content

### 1. Introduction to Python
- **Basic Concepts**: Syntax, variables, and data types.
- **Decision Structures and Loops**: Conditionals (`if`, `else`, `elif`) and loops (`for`, `while`) for flow control.
- **Collections**: Lists, tuples, dictionaries, and sets for storing and manipulating data.
- **Functions**: Creating functions to modularize code, including parameters and return values.
- **File Manipulation**: Reading and writing text and CSV files.

### 2. Python for Data Science
- **Numpy**: Library for numerical calculations and manipulation of multidimensional arrays.
- **Pandas**: Essential tool for manipulating tabular data, including reading files, cleaning, and transforming data using dataframes.
- **Datetime**: Module for working with dates and times, essential for time series and temporal analysis.
- **Matplotlib and Seaborn**: Data visualization libraries for creating graphs and visualizations to aid data interpretation.
- **Scikit-Learn**: A machine learning library that provides simple and efficient tools for data mining and data analysis, widely used for implementing regression, classification, clustering, and more.
- **Statsmodels**: Used for statistical modeling and analysis, providing classes and functions for estimating and testing different models.
- **Beautiful Soup**: A Python library for web scraping that extracts data from HTML and XML files, allowing users to parse and navigate HTML structures to retrieve specific data. 

---

### Key Data Science Techniques

#### Linear Regression

Linear regression is a statistical technique used to model the relationship between a dependent variable and one or more independent variables by fitting a linear equation. The model is represented by the formula:

  **y=β 
  0
​
   +β 
  1
  x+ϵ**

where \(y\) is the predicted value, \(\beta_0\) is the intercept, \(\beta_1\) is the slope of the line, and \(\epsilon\) represents the error term. Linear regression can be implemented using **Scikit-Learn**, which provides tools to fit, interpret, and validate the model. This approach is commonly used for predicting continuous values and establishing correlations between variables.

#### Example
<img alt="First example of Linear Regression" src="/Assets/Linear_Regression.png">

#### Clustering

Clustering is an unsupervised learning technique that aims to group similar data points based on features or behaviors. It is commonly used for pattern recognition, segmentation, and anomaly detection. **Scikit-Learn** provides algorithms like **K-means**, which works by dividing data points into clusters by minimizing the variance within each cluster. Clustering techniques help identify patterns within unstructured data and are valuable in exploratory data analysis.

---

## Library Use in Projects

- **Programming Languages**:
  The code uses **Matplotlib** to create a bar chart displaying votes for different programming languages. It customizes the chart with titles, labels, and limits, and **plt.show()** displays the chart.

<img alt="Our First Graphic - Programming Languages" src="/Assets/First_Graphic.png">

- **Student Averages**:
  A bar chart that shows students' average grades, calculated using **Pandas** and **NumPy**. The chart visually indicates passing and failing grades using color coding, enhancing understanding of student performance.

<img alt="Students Media" src="/Assets/Students_Media.png">

- **Cars Filtering**:
  **Pandas**, **Seaborn**, and **Matplotlib** generate a bar chart displaying the top car brands sold in 2010. The chart, customized with labels and limits, illustrates how **Pandas** and **Seaborn** simplify data filtration and visualization.

<img alt="Cars Filtering" src="/Assets/Car_Brands.png">

- **Ice Cream Sales Based on Temperature**: 
  This plot shows the correlation between temperature (°C) and ice cream sales (in millions). Using **Pandas** for data handling, **NumPy** for temperature conversion, **Seaborn** for styling, and **Scikit-Learn's** Linear Regression, the scatter points represent actual sales, while the purple line indicates the trend. Higher temperatures correlate with increased sales.

<img alt="Ice Cream Sales Based on Temperature" src="/Assets/Ice_Cream_Sales.png">

- **Country Clustering**: <br/>
  This scatter plot showcases the clustering of countries based on **Latitude** and **Longitude** using **KMeans** from **Scikit-Learn**. Different colors represent clusters, grouping countries geographically. **Pandas** was used for data handling, and **Matplotlib** and **Seaborn** were used for visualization and styling.

<img alt="Country Clusterization" src="/Assets/Countries_Clusterization.png">

- **Dollar Exchange Rate Over Time**: <br/>
  This line chart illustrates the R$/USD exchange rate in January each year from 2000 to 2024, showing the trend in currency valuation. **Pandas** was used for data organization, while **Matplotlib** and **Seaborn** were used for creating and styling the dashed line plot, capturing fluctuations over time.

<img alt="Dollar Exchange Rate Over Time" src="/Assets/Dolar_Graphic.png">
