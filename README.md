# IDS706-Project2-Yutong
This is the repo for IDS706 course project 2.

CLT downloads and describes any Kaggle data with the dataset name.

### Usage

#### Getting access to Kaggle dataset

If you see OSError: `Could not find kaggle.json. Make sure it's located in /home/vscode/.kaggle. Or use the environment method.`. Please download Kaggle token with your account and mv it to required dirtectory.

#### Downloading Kaggle dataset

`./describe_kaggle_data -d <kaggle_data_name>`

Example: 

`./describe_kaggle_data.sh -d store-sales-time-series-forecasting`
`./describe_kaggle_data.sh -d house-prices-advanced-regression-techniques`