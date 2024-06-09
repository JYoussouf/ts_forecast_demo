A demo ts skforecast template with a grid search hyperparameter optimization and data visualization methods.

## View Notebook with Interactive Plotly Renders Here:
https://nbviewer.org/github/JYoussouf/ts_forecast_demo/blob/main/autoregressive_solar_energy_model.ipynb

## Data Location:
Download the Solar_Energy_Production.csv dataset from here (~54MB): https://www.kaggle.com/datasets/ivnlee/solar-energy-production

## Set-up Instructions:
- Set up a Python3.11 environment (not currently tested beyond that) 
`python3.11 -m venv env`
- Activate the environment and pip install requirements.txt flask packages
```
source env/bin/activate
pip install -r requirements.txt
```

## Views
_Resampled Monthly Plots_
<p align="center">
  <img src="https://github.com/JYoussouf/ts_forecast_demo/assets/90774566/652288cd-46e3-4938-bc09-3fe75c9bace0" alt="Monthly Solar Production - City of Calgary Public Facilities"/>
</p>

_Train-Test Split with skforecast predictions (after grid-search mse optimization)_
<p align="center">
  <img src="https://github.com/JYoussouf/ts_forecast_demo/assets/90774566/47d8f79a-e8eb-4f36-8f1b-9cd2eda57814" alt="Monthly Solar Production - City of Calgary Public Facilities"/>
</p>

_Grid-Search RandomForest Regressor optimization_
<p align="center">
  <img src="https://github.com/JYoussouf/ts_forecast_demo/assets/90774566/25f80dfc-48f0-482b-966c-69cc4b55cc08" alt="Monthly Solar Production - City of Calgary Public Facilities"/>
</p>
