# CrowdTangle-NLP
Sentiment and hate content analysis of CrowdTangle datasets

## Workflow

- Step 1. Run the CrowdTangle dataset through multilingual sentiment prediction model 

> Input dataframe -> Original Facebook data scraped from CrowdTangle

> Output dataframe -> Input dataframe + appended sentiment scores predicted by the model

- Step 2. Run the CrowdTangle dataset through multilingual hate speech prediction model 

> Input dataframe -> Output dataframe from Step 1

> Output dataframe -> Input dataframe + appended hate speech scores predicted by the model

- Step 3. Make plots/visualisations and cumpute overall statistics

> Input data -> Output dataframe from Step 2

> Outputs -> Inline plots and stats.
