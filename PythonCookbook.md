# Python Cookbook
Aims to give code snippets and best practice for data science in Python

# Contents
- Loading Packages
- Reading Data
  
# Loading Packages 
To install packages completely use the anaconda prompt:
    `pip install packagename`
    `conda install packagename`

## example package install
`import pandas as pd`
`import numpy as np`
`import matplotlib.pyplot as plt`


# Reading Data
Reading data is best using pandas, examples per file type below - but most eg will focus on using data frames which are best loaded from csv
- Loading CSV files `df = pd.read_csv('name.csv')`
- Loading Excel files `df = pd.read_excel('read.xlsx')` 