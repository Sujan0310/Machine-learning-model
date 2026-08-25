🧠 Model Performance Evaluation

The Breast Cancer dataset was evaluated using two machine-learning models:

🌳 Decision Tree Classifier
📈 Linear Regression (used as a binary classifier)
📊 Performance Comparison
Model	Accuracy	Precision	Recall	F1-Score
🌳 Decision Tree	91.81%	93.46%	93.46%	93.46%
📈 Linear Regression	92.98%	90.60%	99.07%	94.64%
🔍 Key Takeaways
📈 Linear Regression
🏆 Highest Accuracy: 92.98%
🏆 Highest Recall: 99.07%
🏆 Highest F1-Score: 94.64%
Achieved excellent recall, making it highly effective at identifying positive cases.
Its lower precision (90.60%) means it produces slightly more false positives than the Decision Tree.
🌳 Decision Tree
🎯 Accuracy: 91.81%
🎯 Precision: 93.46%
🎯 Recall: 93.46%
🎯 F1-Score: 93.46%
Provides a more balanced performance across precision, recall, and F1-score.
🏥 Medical Context

In medical diagnosis, recall is especially important because a false negative can mean that a potentially positive case is missed.

With a recall of 99.07%, the Linear Regression model demonstrates a strong ability to identify positive cases. However, its lower precision indicates a higher number of false positives.

High Recall → Fewer Positive Cases Missed
High Precision → Fewer False Positives

🏆 Final Conclusion

Overall, Linear Regression achieved the best overall performance, with higher accuracy, recall, and F1-score compared with the Decision Tree Classifier.

However, the Decision Tree provides a more balanced precision–recall trade-off.

🎯 Priority	Recommended Model
Highest Recall	📈 Linear Regression
Highest Accuracy	📈 Linear Regression
Highest F1-Score	📈 Linear Regression
Balanced Precision & Recall	🌳 Decision Tree
⭐ Best Overall Model: Linear Regression

For applications where minimizing missed positive cases is the primary objective, Linear Regression is the stronger choice based on these evaluation results.
