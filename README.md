# Heart Attack Prediction

Using Machine Learning models to effectively predict heart attacks before they happen using data easily obtainable from a standard doctor's appointment

## Best Classifier scores (selected by Recall)

| **Precision** | **Recall** | **Accuracy** | **F1**   | **F2**   |
| ------------- | ---------- | ------------ | -------- | -------- |
| **82.61%**    | **95.00%** | **91.53%**   | **0.88** | **0.92** |

## Dataset Information

The dataset has 294 rows, with 14 features. Several of the values are missing, and are marked with `?`.

The dataset can be found in `heart-attack-prediction.csv.xz` in this repository. Use the command `xz -d *.csv.xz` to decompress the archive. It is also available from Kaggle [here.](https://www.kaggle.com/imnikhilanand/heart-attack-prediction)

## Model Accuracy Report

[![Model Accuracy Report](./Model%20Accuracy%20Report.png)](https://docs.google.com/spreadsheets/d/1j-ZZxGc_pj-nXmPhzo0GSiQiJ4NWvFDn3Jmr3aBoHBI/edit?usp=sharing)

Models were trained on all samples with a train-test split of either 80/20 or 90/10. The metrics evaluated were precision, recall, accuracy, F1 score, and F2 score.

The decision was made to choose the model via Recall, since in this application a false negative puts the individual at risk due to not receiving the required treatment.

## Next Steps

I worked on this project as a part of my summer internship as a Data Analyst at pSolv. I presented it to the founders of the company, and we are planning to pitch it to the international hospital chain Christus, who we have worked with in the past. [Here](https://docs.google.com/presentation/d/1x8kv5o3TY47nkiJoUJo3Bzw700LsIpx8YrAaJi0HNUQ/edit?usp=sharing) is the presentation I used. If our proposal is successful, I will be working with sensitive data, so I will not be able to publish anything here.

---

For more information please contact me at arjvik@gmail.com.
