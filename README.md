# Exploratory-Data-Analysis-EDA-Task-2
Exploratory Data Analysis (EDA)
EDA is the process of understanding a dataset before building any machine learning model. It involves:
-Understanding the structure and contents of the data.
-Finding patterns, trends, and relationships.
-Detecting outliers and missing values.
-Visualizing the data using graphs.

1.  Import Libraries
pandas is used to load and manipulate tabular data (e.g., CSV files).
matplotlib.pyplot is for basic graphs like bar charts or histograms.
seaborn is built on matplotlib and used for statistical plots.
sns.set(style="whitegrid") applies a clean background for better visualization.
2.  Load the Dataset
pd.read_csv() reads the Titanic dataset (a .csv file).
df.head() displays the first five rows.
3. **Explored the Structure of the Data**  
   - Used `.shape`, `.info()`, and `.isnull().sum()` to find the number of rows, columns, data types, and missing values.

4. **Generated Summary Statistics**  
   - Used `.describe()` to view statistics like mean, standard deviation, minimum, and maximum for numeric columns.

5. **Plotted Histograms**  
   - Plotted histograms for all numeric features to check the distribution of data (e.g., Age, Fare).

6. **Created Boxplots**  
   - Plotted a boxplot for the ‘Age’ column to detect outliers and understand the spread of data.

7. **Visualized Feature Relationships**  
   - Plotted a **correlation heatmap** to analyze relationships between numeric features.
   - Checked for multicollinearity and feature significance.

8. **Explored Categorical Patterns**  
   - Used **countplots** to explore how survival varied by **gender** and **passenger class**.

9. **Wrote Down Observations**  
   - Based on the visuals and statistics, I noted down key findings and patterns:
     - Women and 1st class passengers had higher survival rates.
     - Fare is highly skewed.
     - Age contains missing values and outliers.

10. **Prepared the Notebook for Submission**  
    - Saved the `.ipynb` notebook and added a `README.md` explaining the steps and findings.

This task helped me gain practical experience in:
- Understanding raw datasets,
- Using visualization tools for pattern recognition,
- Deriving useful insights before moving to machine learning models.
