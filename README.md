[![CI/CD](https://github.com/zachary-fennie/Python-Scripting-for-SQL-Database/actions/workflows/CI_CD.yml/badge.svg)]


# Fennie's Cloud Hosted Notebook Data Manipulation
## Python script reads a dataset, generates descriptive statistics, creates a visualization using Pandas, and performs some data manipulation


## Structure
The notebook will load data, generate descriptive stats, visualations, and data manipulation. Alongside, the repo also contains the following:
* `library` directory contains `extract.py` to extract raw data from an online url source
* `transform_load.py` to transform and load the original raw data from a `.csv` to a `.db` SQLite database
* `crud_query.py` to perform CRUD and query basic SQL operations
The rational is demonstrate what a full data project could like in anticipation of future projects.

### Core Files of the Repo:
* Jupyter notebook
* `icu.db`
* `library.py`
    - `extract.py`
    - `transform_load.py`
    - `crud_query.py`
* `test_main.py`
* `requirements.txt`
* CI/CD pipeline
* `Makefile`
* `README.md`

### Successful SQL Operations
<img width="1336" alt="Screenshot 2024-10-07 at 5 26 19 PM" src="https://github.com/user-attachments/assets/199f3776-66dd-4011-a1e5-570e89d8ded5">

## Data
### FiveThirtyEight's MMS ICU Beds Dataset
This dataset combines data from the Centers for Disease Control and Prevention's Behavioral Risk Factor Surveillance System (BRFSS) and the Kaiser Family Foundation to illustrate the number of people who were at high risk for hospitalization from the novel coronavirus COVID-19 in 2020.\
URL: https://github.com/fivethirtyeight/data/blob/e6bbbb2d35310b5c63c2995a0d03d582d0c7b2e6/covid-geography/mmsa-icu-beds.csv

### Summary Statistics of the ICU Dataset
<img width="1056" alt="Screenshot 2024-10-05 at 6 34 57 PM" src="https://github.com/user-attachments/assets/536234ae-e5ff-47dd-b371-b420a96807c0">

### Data Visualization of High Risk Persons per ICU beds & Hopitals
![output](https://github.com/user-attachments/assets/18565095-13cf-46be-b59b-174f677e9536)

### Jupyter Notebook for Preliminary Examination of Data
[Notebook](https://github.com/zachary-fennie/Python-Scripting-for-SQL-Database/blob/main/main_notebook.ipynb)
