# Heart Attack Prediction
Using Machine Learning models to effectively predict heart attacks in patients using data easily obtainable from a standard doctor's appointment

## Best Classifier scores (selected by Recall)

| **Precision** | **Recall** | **Accuracy** | **F1**   | **F2**   |
| ------------- | ---------- | ------------ | -------- | -------- |
| **82.61%**    | **95.00%** | **91.53%**   | **0.88** | **0.92** |

## Dataset Information

The dataset has 294 rows, with 14 features. Several of the values are missing, and are marked with `?`.

The dataset is available from Kaggle [here.](https://www.kaggle.com/imnikhilanand/heart-attack-prediction)

## Model Accuracy Report

![Model Accuracy Report](./Model%20Accuracy%20Report.png)

Models were trained on all samples with a train-test split of either 80/20 or 90/10. The metrics evaluated were precision, recall, accuracy, F1 score, and F2 score.

The decision was made to choose the model via Recall, since in this application a false negative puts the individual at risk due to not receiving the required treatment.

---

For more information please contact me at arjvik@gmail.com.
