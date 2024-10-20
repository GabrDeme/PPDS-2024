# Python Programming for Data Science Course

Welcome to the repository for the **Python Programming for Data Science Course**!

This Python course for Data Science provides an introduction to using Python for data analysis and manipulation. It involves extracting insights from data through statistical techniques, visualization, and machine learning, with Python being one of the most popular languages for this purpose.

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
- **Matplotlib and Seaborn**: Data visualization libraries that allow the creation of intuitive graphs and visualizations to facilitate data analysis and interpretation.

---

## The use of Librarys in our Projects
- Programmimg Languages
  The code uses the **Matplotlib** library to create a bar chart that shows votes for different programming languages. It starts by creating a figure and axes with plt.subplots(), where the actual chart is drawn. The ax.bar() function plots bars for each language, using custom colors from the cores list. The chart is customized with a title, axis labels, and a y-axis limit from 0 to 500 using ax.set_title(), ax.set_xlabel(), ax.set_ylabel(), and ax.set_ylim(). The ax.bar_label() function adds the exact number of votes on top of each bar for clarity. Finally, plt.show() displays the chart.

<img alt="Our First Graphic - Programming Languages" src="/Assets/First_Graphic.png">

- Students Medias
  The bar chart displays the final grades of students, with names on the x-axis and their average grades on the y-axis. The chart is generated using Python libraries like **Pandas** for data handling, **NumPy** for grade calculation, and **Matplotlib** and **Seaborn** for visualization. Each student's average grade is calculated from four test scores, and bars are colored based on whether the student passed (green) or failed (red). The chart includes labels for the exact averages on top of each bar, with a title and axis labels for clarity. The y-axis is limited from 0 to 12, highlighting one failing student, Benjamin Hall, with an average of 3.75.

<img alt="Students Media" src="/Assets/Students_Media.png">


- Cars Filtration
  The code uses Pandas, Seaborn, and Matplotlib to generate a bar chart showing the Top 5 Car Brands Sold in 2010. After loading the car data from a CSV file and cleaning it by dropping missing values, it filters the dataset for cars from the year 2010. The top 5 most-sold brands are calculated using value_counts() and displayed in a bar chart with Seaborn's barplot(). The x-axis represents the car brands, and the y-axis shows the number of cars sold, with labels on top of each bar indicating the exact figures. The chart is customized with titles, axis labels, and a y-axis limit of 0 to 5000.

<img alt="Cars Filtering" src="/Assets/Car_Brands.png">
