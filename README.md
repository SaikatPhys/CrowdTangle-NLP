# CrowdTangle-NLP
Sentiment and hate content analysis of CrowdTangle datasets

## Data and NLP processing workflow

- Step 1. [Run the CrowdTangle dataset through multilingual sentiment prediction model](https://github.com/SaikatPhys/CrowdTangle-NLP/blob/main/CrowdTangle-sentiment-prediction.ipynb)

> Input dataframe -> Original Facebook data scraped from CrowdTangle

> Output dataframe -> Input dataframe + appended sentiment scores predicted by the model

- Step 2. [Run the CrowdTangle dataset through multilingual hate speech prediction model](https://github.com/SaikatPhys/CrowdTangle-NLP/blob/main/CrowdTangle-hatespeech-prediction.ipynb)

> Input dataframe -> Output dataframe from Step 1

> Output dataframe -> Input dataframe + appended hate speech scores predicted by the model

- Step 3. [Make plots/visualisations and cumpute overall statistics](https://github.com/SaikatPhys/CrowdTangle-NLP/blob/main/CrowdTangle-sentiment-hatespeech-plots.ipynb)

> Input data -> Output dataframe from Step 2

> Outputs -> Inline plots and stats.

- Step 4. Evaluate the performance of the multilingual sentiment and hate speech prediction models on human annotated dataset

-- Step 4.1. Randomly sample representative dataset(s) for human annotations

-- Step 4.2. Cross-validate the annotated labels with model predictions.
