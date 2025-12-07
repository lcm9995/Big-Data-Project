

# Local Setup instructions:
## Create virtual environment:
python3.11 -m venv sparkenv
(*** 3.13 will not work use python 3.11)
## Activate venv:
source sparkenv/bin/activate
or 
.\sparkenv\Scripts\activate

## Install required packages:
pip install -r requirements.txt

# Then: \
# run all cells in data_prep.ipynb \
# then run cells in analysis.ipynb sequentially# Big-Data-Project \

taxizone geojson from https://www.kaggle.com/datasets/mxruedag/tlc-nyc-taxi-zones