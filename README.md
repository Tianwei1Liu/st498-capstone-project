# ST498 Capstone Project

## 1. `Codes` folder 

It includes all notebooks that we have developed and analyzed throughout the project, which are as follows:

* `Data cleaning and aggregation.ipynb`: This notebook processes and aggregates data from different sources, cleans them, and aggregates them into a single `~.csv` file. The input for this notebook is all files under `/Data/Raw Form`, and the outputs are named `data_all.csv`, which includes data for the United Kingdom, Spain, Italy, the Netherlands, Poland, and Germany. Additionally, there is a larger dataset named `data_all_europe.csv`, covering 37 countries in the European continent.

* `Exploratory data analysis.ipynb`: This notebook contains the code for **Section 4.2 Explanatory Data Analysis** in the report. The input data is `data_all.csv`, and the output plots are stored in the folder `Plots`.

* `Time series forecasting.ipynb`: This notebook is used for **Section 4.3 Time Series Model** in the report. The input data is `data_all.csv`, filtered using `~['Country'] == 'Spain`. In this notebook, ARIMAX and LSTM models are trained and analyzed. The tuned LSTM model is included under `Models



## 2. `Data` folder 

It include all necessary data we used and outputed throught the project.

* `Raw Form` folder include all data sources we collectde from different websites and databases.


| File Name                                               | Description                                                                       |
|---------------------------------------------------------|-----------------------------------------------------------------------------------|
| `gross production value_tomato.csv`                    |  Our target feature, contains data on the gross production value of tomatoes. |
| `comtrade_all.csv`                                      | Contains data related to international trade, likely export and import countries, value in kg and $. |
| `Food production index (2014-2016 = 100).csv`            | Includes data on food production indexed to the years 2014-2016. |
| `Pesticides indicators (Land, Inputs and Sustainability).csv` | Contains information on pesticides usage. |
| `Inputs_LandUse_E_All_Data.csv`                         | Contains data related to land use, including the change in cropland areas. |
| `population.csv`                                        | Contains population data, categorized by region and other demographic factors. |
| `Fertilizer consumption (kilograms per hectare of arable land).csv` | Contains data on fertilizer consumption, indicating the kilograms used per hectare of arable land. |
| `Weather`                                               | A directory or collection of files to temperature and precipitation records. |
| `Macro-Statistics_Key_Indicators_E_All_Data_NOFLAG.csv`  | Contains macroeconomic statistics and key indicators, related to agriculture economics. |
| `Agricultural machinery, tractors per 100 sq. km of arable land.csv` | Contains data on the density of agricultural machinery, particularly tractors, per 100 square kilometers of arable land. |
| `Agriculture, forestry, and fishing, value added (_ of GDP).csv` | Contains data on the value added by agriculture, forestry, and fishing as a percentage of GDP. |
| `IFADATA Plant Nutrition query - 16-Aug-2023_04.08.xlsx` | An Excel spreadsheet file with plant nutrition data in N, K, and P. |

* `Aggregated and Processed` include three files:
    * `data_all_europe.csv`
    * `data_all.csv`
    * `tomato_export_2021.csv`

    While the first two files have been briefly explained, `tomato_export_2021.csv` contains information about all trade data happending during year 2021 and is the main source for our Section 4.1.

* `Model Performance` contains all model performance metrics in **Section 4.4 Supervised Regression**  stored in `~.csv` format.


## 3. `Models` folder

It contains all models in **Section 4.3 Time Series Model** and **Section 4.4 Supervised Regression**,  and stored either in `~.h5` or `~.pkl`, which could directly been used to generate predictions for new data


## 4. `Plots` folder
It contains all plots generated in **Section 4.2 Explanatory Data Analysis** and **Section 4.4 Supervised Regression**.

