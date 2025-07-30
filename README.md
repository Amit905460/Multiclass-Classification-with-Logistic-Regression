🌸 Iris Classification with Logistic Regression
This project demonstrates multiclass classification using logistic regression on the classic Iris dataset. It explores how flower measurements like petal and sepal dimensions can be used to predict the species of Iris: Setosa, Versicolor, or Virginica.
🚀 Objectives
- Apply multinomial logistic regression for multi-class classification
- Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrix
- Visualize prediction performance with heatmaps
- Practice clean, interpretable machine learning workflows
📊 Dataset
- Source: seaborn's built-in Iris dataset
- Features: Sepal length, sepal width, petal length, petal width
- Target: Iris species (converted to numerical labels)
🧠 Model
- Algorithm: LogisticRegression(multi_class='multinomial', max_iter=100)
- Train-Test Split: 80/20 with random_state=2
- Evaluation metrics:
- Classification report (Precision, Recall, F1-score)
- Confusion Matrix
- Overall Accuracy (≈96.7%)
📈 Results Snapshot
- Setosa classified with 100% precision and recall
- One misclassification in Versicolor
- Strong overall F1 and macro scores
📷 Visuals
Confusion matrix heatmap added for quick visual inspection of prediction performance.
📁 Usage
Clone the repo, run the Python script or notebook, and explore the evaluation results. No external data downloads needed—it's all self-contained.
git clone https://github.com/your-username/iris-logistic-regression.git


🎓 Skills Demonstrated
- Multinomial classification
- sklearn metrics interpretation
- Visualization with Seaborn & Matplotlib
- Structured ML coding with readability
