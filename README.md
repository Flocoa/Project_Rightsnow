# RightsNow!
This project leverages data from SACEM and other sources to provide independent artists with a real-time revenue tracking and forecasting dashboard.

The data stack relies on dbt paired with BigQuery, a Python Machine Learning model for forecasting, and Looker for data visualization.

## RightsNow.pdf
A sample preview of the dashboard for both free and premium tiers. It enables artists to track their broadcasts across TV, radio, and web radio while estimating their upcoming earnings.

## RightsNow_prediction.ipynb
A Python notebook using the Prophet model to generate revenue predictions.

## Other files
The dbt project files, with core logic located in the models/ directory alongside dbt_project.yml and schema.yml.
