# DE 300 Homework 1: Aircraft inventory analysis

## How to run the code:

1. Make sure you have Python 3.7+ installed
2. Clone/download this repository:
- git clone https://github.com/iane884/Ian_Evensen_DE300.git
- cd Ian_Evensen_DE300
3. Install dependencies:
- pip install pandas matplotlib seaborn scipy
4. Launch Jupyter Notebook:
- jupyter notebook
5. Open DE300hw1.ipynb and run the notebook cell by cell

## Expected outputs:

1. Info messages:
- output showing missing values in CARRIER, CARRIER_NAME, MANUFACTURE_YEAR, NUMBER_OF_SEATS, CAPACITY_IN_POUNDS, and AIRLINE_ID columns
2. Imputation/Data Cleaning
- print statement showing number of remaining rows after dropping missing values
3. Transformations
- Skewness values before Box-Cox transformations
- Histograms for pre/post Box-Cox transformation for NUMBER_OF_SEATS and CAPACITY_IN_POUNDS
4. Feature Engineering
- Value counts for SIZE column
- Plots showing Proportions of Operating Status by Size and Aircraft Status by Size
