# datafun-04-eda


## Make repository in Github and clone to local workspace
```bash
git clone https://github.com/egbogbo11/datafun-04-eda 
```

## Create .gitignore file
Ensure the following entries are added to your .gitignore file to exclude unnecessary files from being committed:

```bash
# Python virtual environment
.venv/

# Visual Studio Code settings and workspace
.vscode/

# Compiled Python files
__pycache__/

# Jupyter notebook checkpoints
.ipynb_checkpoints/
```

## Create and activate virtual environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

```bash
.\.venv\Scripts\activate
```
## Create requirement.txt and download imports
Add the following libraries to your requirements.txt file:

```bash
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn
```

Install into your active project virtual environment with this command:

```bash
py -m pip install -r requirements.txt
```
## Stage and Push Files to GitHub

Use the following Git commands to stage and commit changes:

```bash
git add .
git commit -m "commit: message"
git push origin main
```
##  Complete the following steps to create an EDA for the Iris Dataset
Step 1. Create an title, header, and import the following libraries into your Jupyter notebook:
```bash
pandas
seaborn
matplotlib
```
Step 2. Load Data
- Load the Iris dataset into pandas DataFrame

Step 3. Initial Data Inspection
- Specify the number of rows to display
- Inspect the shape of the DataFrame with shape attribute
- Inspect the data types of the columns with dtypes attribute
- Inspect the data types of the columns with info() method

Step 4. Intital Descriptive Statistics
- Inspect summary statistics for numerical columns

Step 5a. Initial Data Distribution for Numerical Columns
- Inspect histogram by one numerical column
- Inspect histograms for ALL numerical columns
- Show all plots

Step 5b. Intital Data Distribution for Categorical Columns
- Inspect value counts by categorical column
- Inspect value counts for ALL categorical columns
- Show all plots

Step 6. Initial Data Transformation and Feature Engineering
- Feature Engineering
- Renaming a column
- Adding a new column

Step 7. Initial Visualizations
- Create a pairplot of the Iris dataset
- Show all plots

- Create a scatterplot of sepal length and sepal area

Step 8. Initial Insights
- share conclusions and insights from the visualized data
##