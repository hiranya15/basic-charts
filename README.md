# 📊 Experiment 16 – Basic Charts and Visual Encoding using Python
# Hiranya
# 25070123054
# Entc A3
## 

# 1. Aim
To study and apply fundamental data visualization techniques using Python libraries such as Matplotlib and Seaborn in order to analyze patterns, trends, distributions, and relationships within datasets.

# 2. Introduction to Libraries
Data visualization involves representing data in a graphical format to make it easier to understand patterns, trends, and outliers.
Pandas (pd): Used for organizing and analyzing data. It structures raw data into DataFrames, which are suitable for plotting.
Matplotlib (plt): A core plotting library that provides detailed control over the creation of graphs and charts.
Seaborn (sns): A higher-level library built on Matplotlib that simplifies the creation of visually appealing statistical graphics.
NumPy (np): Used for numerical computations, particularly for generating sequences of values required in plotting (e.g., positioning bars).

# 3. Commonly Used Functions
The following functions are frequently used to enhance the appearance and readability of plots:
plt.title() – Sets the title of the graph
plt.xlabel() / plt.ylabel() – Labels the X and Y axes
plt.show() – Displays the plot
plt.figure(figsize=(w, h)) – Defines the size of the figure
plt.legend() – Adds a legend to the plot
plt.grid(axis='y') – Displays grid lines along the Y-axis

# 4. Procedure and Visualization Techniques

Step 1: Data Preparation
Function Used: pd.DataFrame()
Description: Data is initially created using Python dictionaries and then converted into a structured DataFrame format, which is suitable for visualization.

# 
Step 2: Line Plot (Trend Representation)
Purpose: To display how data changes over a continuous range or time.
Function Used: plt.plot()
Description: Plots data points and connects them using lines. Markers can be added to highlight individual points. Multiple datasets can be plotted together for comparison.
# 
Step 3: Bar Plot (Categorical Comparison)
Purpose: To compare values across different categories.
Function Used: plt.bar()
Description: Represents data using rectangular bars whose heights correspond to values.
Additional Features:
Value Labels: Numerical values are displayed on top of bars using plt.text().
Grouped Bar Chart: Bars are positioned side-by-side using np.arange() and width adjustments to avoid overlap.
#
Step 4: Histogram (Distribution Analysis)
Purpose: To analyze the frequency distribution of continuous data.
Function Used: plt.hist()
Description: Divides data into bins and displays how frequently values occur within each range.
#
Step 5: Scatter Plot (Relationship Analysis)
Purpose: To observe relationships or correlations between two variables.
Function Used: plt.scatter()
Description: Displays individual data points without connecting lines.
Conditional Formatting:
Different colors are assigned to data points based on categories (e.g., Pass/Fail), making the visualization more informative.
# 
Step 6: Visualization Using Seaborn
Purpose: To create more refined and visually appealing graphs with simpler syntax.
Functions Used:
sns.lineplot()
sns.barplot()
sns.scatterplot()
sns.histplot()
Special Feature:
The kde=True parameter in sns.histplot() adds a smooth curve to better represent data distribution.

# 5. Conclusion
This experiment highlights the importance of data visualization in interpreting data effectively. Matplotlib allows precise customization of plots, while Seaborn simplifies the process by providing built-in styles and advanced statistical features. Together, these libraries help transform raw data into meaningful visual insights.
