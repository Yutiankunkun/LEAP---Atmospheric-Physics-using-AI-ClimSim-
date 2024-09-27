## LEAP - Atmospheric Physics using AI (ClimSim)
### Overview
In this competition, you’ll develop machine learning models that accurately emulate subgrid-scale atmospheric physics in an operational climate model—an important step in improving climate projections and reducing uncertainty surrounding future climate trends.

### Evalutaion
$$\ R^2 = 1 - \frac{SS_{\text{res}}}{SS_{\text{tot}}} \$$

### Data Description
train.csv - the training set
test.csv - the NEW test set
sample_submission.csv - NEW prediction weightings
test_old.csv - the (old) test set
sample_submission_old.csv - (old) prediction weightings

### Results
LB：0.69331<br>
PB：0.69122<br>
Ranking：207/693<br>

### Solution
Baseline：Keras seq2seq<br>
Model：cnn＋transfomer<br>
