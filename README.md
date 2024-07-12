# kaggle-sales-predictions

The project in this repository is based on Store Sales - Time Series Forecasting Kaggle Competition.

However, the main topic of the project is not winning the challenge. I'm currently part-time employed in GIST, analytics company from my thesis. The project I'm working on there is named Hierarchical Time Series Forecasting. This project is also my bachelor's thesis.

Due to guidlines of my university, I cannot use the same data for my job and bachelor's thesis. So, in order to write the thesis, I need some other data, ideally equivalent to the one I'm using in the project. After making a research, I found the dataset from this Competition the most suitable for my thesis.

So, this repository is a replication of my solution from GIST project on the open-source dataset. However, some techniques from the initial project are not applicable to this dataset, but some new can be used.

The main goal of the original project is to build a system, that will make forecasts on different levels of the hierarchy: all sales -> product category -> product etc. There is no defined metric for the model, so I will choose <b>RMSLE</b> and <b>MAE</b>.

## Steps to run

### Step 1. Add data

Open a terminal at the root directory of the project and enter the following command:

```sh
mkdir data
```

Then add the downloaded data files from Kaggle to the created directory.
