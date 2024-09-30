# datafun-06-eda

This project focuses on developing a custom exploratory data analysis (EDA) workflow using GitHub, Jupyter, pandas, Seaborn, and other leading data analytics tools.

## Create and Manage Virtual Environment

1. Open project folder in VS Code.
2. Open a terminal in VS Code to sync the latest project contents: `git pull` 
3. Create a virtual environment: `python3 -m venv .venv`
4. Activate the virtual environment: `source .venv/bin/activate`
5. Install necessary packages: `python3 -m pip install <package_name>`
6. Set VS Code Python Interpreter to use the .venv environment.
7. Use Git to track and push changes:  
   `git add .`  
   `git commit -m "Your commit message"`  
   `git push -u origin main`

## Create Jupyter Notebook
1. Open project folder in VS Code.
2. Create Jupyter Notebook file: 'joannafarris_eda.ipynb'

## Load Dataset into a Pandas Dataframe
1. In project folder save dataset as csv file:`titanic.csv`  
2. In Jupyter Notebook file:  
   * import pandas:`import pandas as pd`  
   * load file into pandas dataframe: `df = pd.read_csv("titanic.csv")`