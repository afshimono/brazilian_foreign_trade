# Brazilian Foreign Trade
Yet another Data Science exercise!

## What are we doing here?

Retrieving data for foreign trade in Brazil with granularity per State.

## Configuring the Environment

In order to configure your Virtual Environment, please follow the steps:

1. Install Python >= 3.7
2. Run `pip install venv`
3. Activate (on windows, run `source venv/Scripts/activate`)
4. Run `pip install -r requirements.txt`
5. Start the notebook with the command `jupyter notebook`

## Generating PDF

Execute the following command while in the root directory:
```
jupyter nbconvert --to pdf Santa\ Catarina\ Import-Export.ipynb --no-input
```


## Results

### 2019
Imports as percentage per State
![Export Percentages for 2019](img/import_percentage_2019.png)

Exports as percentage per State
![Import Percentages for 2019](img/export_percentage_2019.png)

Top 3 for SC
![Top 3 products by month for SC](img/export_month_SC.png)

### 2017 - 2019
Top 3 imports for SC
![Top 3 imports products for SC in three years](img/import_year_SC.png)

Top 3 exports for SC
![Top 3 exports products for SC in three years](img/export_year_SC.png)

## Download Full Report
If you want to see all results, please [download the full report.](Santa%20Catarina%20Import-Export.pdf)


