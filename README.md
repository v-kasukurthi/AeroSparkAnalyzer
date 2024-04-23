# AeroSparkAnalyzer
Explore flight delay prediction model metrics &amp; insights. Utilizing Apache Spark, this repo showcases accuracy, sensitivity, specificity, precision, and more for flights in 2008. Valuable for aviation analytics and data science enthusiasts.


Here are insights based on the confusion matrix and metrics:

Confusion Matrix:
True Negative (TN): 1,547,036 flights were correctly predicted as not delayed.
False Positive (FP): 53,062 flights were incorrectly predicted as delayed.
False Negative (FN): 129,194 flights were incorrectly predicted as not delayed.
True Positive (TP): 329,116 flights were correctly predicted as delayed.

Metrics:
Prevalence:The prevalence of delayed flights in the dataset is 22%. This means that 22% of the flights in the dataset are actually delayed.
Sensitivity (Recall): The model correctly identifies 72% of the delayed flights. This is the proportion of true positives among all actual positives.
Specificity (Especificity):The model correctly identifies 97% of the flights that are not delayed. This is the proportion of true negatives among all actual negatives.
Precision (Positive Predictive Value - PPV):Among the flights predicted as delayed by the model, 86% are actually delayed.
Accuracy:The overall accuracy of the model is 91%, which is the proportion of correct predictions (both delayed and not delayed) among all predictions.

Insights:
- The model performs well in terms of accuracy (91%), indicating that it correctly predicts whether a flight is delayed or not in the majority of cases.
- The model has a high specificity (97%), suggesting that it is effective at identifying flights that are not delayed. This is crucial for minimizing false alarms and ensuring that non-delayed flights are correctly identified.
- The sensitivity (recall) is 72%, indicating that the model captures a significant portion of delayed flights. However, there is room for improvement in identifying more delayed flights, as some are still being missed (false negatives).
- The precision is 86%, meaning that when the model predicts a flight as delayed, it is correct 86% of the time. This is important for users who want to rely on the model predictions for making decisions about potential delays.

Overall, the model appears to be a solid performer, but further optimization may be possible, especially in improving sensitivity to capture more delayed flights.
