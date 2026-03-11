# Electrocardiograms

## Download the dataset

The dataset can be obtained from [here](https://d32aokrjazspmn.cloudfront.net/materials/ML_Electrocardiograms_dataset.csv). Download it using the following commands and save it to the `data` folder in the `02-Electrocardiograms` directory:

```bash
curl https://d32aokrjazspmn.cloudfront.net/materials/ML_Electrocardiograms_dataset.csv > data/electrocardiograms.csv
```

## Dataset

- Each observation in the dataset is a numerically represented heartbeat taken from a patient's electrocardiogram (ECG).
- `target` is binary and defines whether the heartbeat is at risk of cardiovascular disease [1] or not [0].

## Exercise

🎯 The task is to flag heartbeats at risk of cardiovascular disease:

- Investigate the class balance of the dataset
- Evaluate and compare two models: KNN and LogisticRegression
- Use the Confusion matrix and Classification report to gain insights into the performance of the models
- Select the optimal model based on the appropriate metric
