# Cancer-Analysis-in-US

Data Loading: The project begins by loading the cancer dataset from the 'cancer2017.csv' file into a Pandas DataFrame called df.

Data Cleaning: The code performs several data cleaning operations on the loaded dataset. It replaces non-ASCII values with NaN (null) values, cleans the column names by removing leading/trailing spaces and replacing spaces with underscores, and converts certain cell values containing commas to numeric values.

Data Exploration and Visualization: The project includes various data exploration and visualization tasks to gain insights from the dataset. It uses libraries such as Matplotlib, Seaborn, and Plotly to create visualizations.

Missing Data Visualization: The code utilizes the 'missingno' library to create a matrix plot showing the missing values in the dataset.

Incomplete Data Visualization: The code generates line plots and bar plots to visualize the data with missing values. It creates subplots to display the trends for different types of cancer across different states.

NaN Filled Data Visualization: After filling the missing values with the mean values of the corresponding columns, the code creates line plots and bar plots again to visualize the cleaned dataset.

Correlation Heatmap: The code generates a heatmap using Seaborn to visualize the correlation between various types of cancer in the dataset.

Scatter Plot and Pair Plot: The code utilizes Scatter plots and Pair plots to explore relationships between different variables in the dataset.

Box Plot and Strip Plot: The code creates box plots and strip plots to visualize the distribution and variability of the data.

Count Plot and Joint Plot: The code generates count plots and joint plots to analyze the frequency and relationships between specific variables in the dataset.

Additional Analysis: The code includes some additional analysis, such as a scatter plot comparing the number of liver cancer cases with the states and a count plot for the number of female breast cancer cases.

Overall, the 'cancer analysis project' aims to explore and visualize cancer-related data, identify missing values, clean the dataset, and gain insights into the relationships and distributions within the data.
