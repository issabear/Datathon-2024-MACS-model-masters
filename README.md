# Datathon-2024-MACS-model-masters
Repository for Inter-Uni Datathon 

my_learning.ipynb is my attempt at exploring, implementing and collating what I learnt at the UNSW Datathon 2024. 
Our competition model had a 0.88 f1-score at best but this implementation has a 1.00 f1-score with both RandomForestClassifier and XGBoost models. This means both explored models perfectly **predicted fraudulent transactions** in the competition dataset. 

Potentially due to how the features were treated, especially the most important feature (Transaction Time) since the XGBoost model performs very well with almost no adjustment. The most significant flag is the timing of the transaction (particularly early morning hours 3am - 5am). 
