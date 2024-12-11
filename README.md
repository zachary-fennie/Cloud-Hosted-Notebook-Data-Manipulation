![CI/CD](https://github.com/zachary-fennie/Python-Scripting-for-SQL-Database/actions/workflows/CI_CD.yml/badge.svg)


# Fennie's Cloud Hosted Notebook Data Manipulation
## The Project aims to set up a cloud-hosted Jupyter Notebook, i.e. Google Colab, and perform data manipulation tasks on a simple dataset. To accomplish this, I will use a the Google Colab cloud-hosted platform. The notebook will contain Python script reads a dataset, generates descriptive statistics, creates a visualization using Pandas, and performs some data manipulation.


## Structure of the Repo & Notebook 
The notebook will load data, generate descriptive stats, visualizations, and data manipulation. To demonstrate what a full data project could like in anticipation of future projects, the repo also contains the following:
* `library` directory contains `extract.py` to extract raw data from an online url source
* `transform_load.py` to transform and load the original raw data from a `.csv` to a `.db` SQLite database
* `crud_query.py` to perform CRUD and query basic SQL operations

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


### Cloud Hosted Jupyter Notebook
[Notebook](https://github.com/zachary-fennie/Cloud-Hosted-Notebook-Data-Manipulation/blob/main/main_notebook.ipynb)


### Successful Commit
<img width="1075" alt="Screenshot 2024-11-03 at 7 28 32 PM" src="https://github.com/user-attachments/assets/9e13b009-1060-4ac6-956f-b3b59dcdadc3">


## Data
### FiveThirtyEight's MMS ICU Beds Dataset
This dataset combines data from the Centers for Disease Control and Prevention's Behavioral Risk Factor Surveillance System (BRFSS) and the Kaiser Family Foundation to illustrate the number of people who were at high risk for hospitalization from the novel coronavirus COVID-19 in 2020.\
URL: https://github.com/fivethirtyeight/data/blob/e6bbbb2d35310b5c63c2995a0d03d582d0c7b2e6/covid-geography/mmsa-icu-beds.csv


### Summary Statistics of the ICU Dataset
<img width="1056" alt="Screenshot 2024-10-05 at 6 34 57 PM" src="https://github.com/user-attachments/assets/536234ae-e5ff-47dd-b371-b420a96807c0">


### Data Visualization of High Risk Persons per ICU beds & Hopitals
![output](https://github.com/user-attachments/assets/18565095-13cf-46be-b59b-174f677e9536)
