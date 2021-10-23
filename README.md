# Hackaton "int20h" - Calculating LTV
## Installation
### Step 1
To start this project, you have to clone this repository and install next libraries:
1. NumPy
2. Pandas

### Step 2
Run Task2.ipynb with jupyter-notebook

Run all cells, the last cell prints calculated LTV

### Warning
data_analytics must be in the same directory as Task2.ipynb

## Solution

1. Calculate 'Free trial' subscribes and unique 'Subscriber ID', amount was the same => All users start their subscribes from trial
2. Calculate amount of subscribes for each 'Subscriber ID', then separate all rows by amount of subscribes into groupes (dataframes).
3. Then, using len of each group , calculate conversion for each 'purchase to purchase'.
4. Calculate multiplication of dev proceeds and conversions for each 'purchase to purchase'
5. By summing all that were calculated in previous step, we got LTV.

Result LTV = 16.33

