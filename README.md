\# Iris Dataset Analysis



This project analyzes the Iris dataset using Pandas and Jupyter Notebook.

The project environment and dependencies are managed using uv.



\## Setup on Windows CMD



Run these commands inside the project folder:



cmd

uv sync

.venv\\Scripts\\activate.bat

uv run jupyter notebook





Open iris\_analysis.ipynb and run all cells from top to bottom.



\## Dataset



The dataset is stored in data/iris.csv.



Source:

https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv



\## Analysis



\- Displayed the first and last five rows using head() and tail().

\- Checked the dataset shape, column names, and data types.

\- Checked missing values and duplicate rows.

\- Counted the unique species and flowers per species.

\- Calculated the average sepal length, maximum petal length, and minimum sepal width.

\- Calculated mean measurements for each species using groupby().

\- Displayed descriptive statistics using describe().

\- Filtered flowers by sepal length, petal width, and species.

\- Found the species with the highest average petal length.

\- Sorted the dataset by sepal length in descending order.



\## Findings



\- The dataset contains 150 rows and 5 columns.

\- There are no missing values.

\- There is one duplicate row beyond its first occurrence.

\- There are three species: setosa, versicolor, and virginica.

\- Each species contains 50 flowers.

\- Average sepal length is approximately 5.843 cm.

\- Maximum petal length is 6.9 cm.

\- Minimum sepal width is 2.0 cm.

\- Virginica has the highest average petal length at 5.552 cm.



\## Exported Results



\- output/species\_summary.csv contains the mean measurements for each species.

\- output/filtered\_iris.csv contains flowers with sepal length greater than 6 cm.

\- Both files were checked using Path.is\_file().

