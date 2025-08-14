Binary Classification Threshold Optimization

In this project, I worked on improving a binary classification model’s results by tuning the decision threshold instead of just using the default 0.5.
Changing this threshold helped me get a better balance between precision, recall, and F1-score for the problem.

🔹 Goal of the Project

Build a binary classification model.

Try out different thresholds.

Pick the one that gives the best performance for our case.

📊 Final Results

Best Threshold: 0.374

Precision: 70.45%

Recall: 83.78%

F1-score: 76.54%

Confusion Matrix:

[[79, 26],
 [12, 62]]

🛠 Tools & Skills Used

Python for coding.

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.

Worked with Logistic Regression, Precision-Recall trade-off, threshold tuning, and model evaluation.

💡 What I Learned

The default threshold is not always the best option.

Changing the decision threshold can improve model results a lot.

The “best” threshold depends on whether you want more precision or more recall based on the problem.

📂 What's in This Repo

binary_classification_threshold_optimization.ipynb – Complete notebook with code, analysis, and graphs.

▶ How to Run

Clone the repo:

git clone https://github.com/yourusername/binary-classification-threshold-optimization.git


Install requirements:

pip install -r requirements.txt


Open the notebook:

jupyter notebook binary_classification_threshold_optimization.ipynb
