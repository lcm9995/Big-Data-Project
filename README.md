

# Local Setup instructions:
## Create virtual environment:
python3.11 -m venv sparkenv 
(*** 3.13 will not work use python 3.11)
## Activate venv:
source sparkenv/bin/activate
or 
.\sparkenv\Scripts\activate

## Install required packages:
### pip install -r requirements.txt

# Run Instructions
## Run all cells in data_prep.ipynb (one time data pre-processing)
## Then run cells in analysis.ipynb sequentially 

# TAXI DATASET: https://www.kaggle.com/datasets/microize/newyork-yellow-taxi-trip-data-2020-2019?select=yellow_tripdata_2019-02.csv
# WEATHER DATASET: https://www.kaggle.com/datasets/aadimator/nyc-weather-2016-to-2022
# taxizone geojson is from https://www.kaggle.com/datasets/mxruedag/tlc-nyc-taxi-zones
