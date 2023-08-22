# ST498 Capstone Project

## 1. Codes Folder

The "Codes" folder contains notebooks used for project development and analysis:

- `Data cleaning and aggregation.ipynb`: Processes and aggregates data from various sources into `data_all.csv` and `data_all_europe.csv`.

- `Exploratory data analysis.ipynb`: Generates plots for Section 4.2 "Explanatory Data Analysis" and stores them in the "Plots" folder.

- `Time series forecasting.ipynb`: Develops ARIMAX and LSTM models, with the best LSTM model saved as `best_lstm_model.h5`.

- `Supervised regression.ipynb`: Covers data preprocessing, model training, and performance analysis for Section 4.4 "Supervised Regression."

- `Trade network analysis.Rmd`: Conducts network analysis (Section 4.1) using R.

## 2. Data Folder

The "Data" folder includes all project-related data:

### Raw Form

This subfolder contains raw data collected from various sources:

- `gross production value_tomato.csv`: Target feature containing gross production value of tomatoes.

- `comtrade_all.csv`: Data on international trade, including export and import countries, quantities (kg), and values ($).

- `Food production index (2014-2016 = 100).csv`: Data on food production indexed to 2014-2016.

- `Pesticides indicators (Land, Inputs and Sustainability).csv`: Information on pesticides usage.

- `Inputs_LandUse_E_All_Data.csv`: Data on land use, including changes in cropland areas.

- `population.csv`: Population data categorized by region and demographic factors.

- `Fertilizer consumption (kilograms per hectare of arable land).csv`: Fertilizer consumption data in kg per hectare of arable land.

- `Weather`: A directory or collection of files containing temperature and precipitation records.

- `Macro-Statistics_Key_Indicators_E_All_Data_NOFLAG.csv`: Macroeconomic statistics and key indicators related to agriculture economics.

- `Agricultural machinery, tractors per 100 sq. km of arable land.csv`: Data on the density of agricultural machinery, particularly tractors, per 100 square kilometers of arable land.

- `Agriculture, forestry, and fishing, value added (_ of GDP).csv`: Data on the value added by agriculture, forestry, and fishing as a percentage of GDP.

- `IFADATA Plant Nutrition query - 16-Aug-2023_04.08.xlsx`: An Excel spreadsheet with plant nutrition data for N, K, and P.

### Aggregated and Processed

This subfolder contains aggregated and processed data files:

- `data_all_europe.csv`
- `data_all.csv`
- `tomato_export_2021.csv`

### Model Performance

Contains model performance metrics in CSV format.

## 3. Models Folder

The "Models" folder stores all models used in time series forecasting and supervised regression, saved as `.h5` or `.pkl` files, suitable for generating predictions on new data.

## 4. Plots Folder

The "Plots" folder contains all plots generated during the exploratory data analysis and supervised regression sections of the project.
