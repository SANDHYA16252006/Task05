This AI & ML internship task focuses on implementing Decision Trees and Random Forests using the `heart.csv` dataset, which contains health-related features and a target column indicating heart disease presence.

We began by loading and exploring the dataset, checking for null values and understanding the distribution of the target. The data was split into features (X) and target (y), and then into training and testing sets (70:30 ratio).

A Decision Tree Classifier was trained with a controlled `max_depth=4` to avoid overfitting. We evaluated its performance using accuracy, classification report, and confusion matrix. The decision tree was visualized using `plot_tree()`.

Next, we implemented a Random Forest Classifier to improve accuracy and generalization. It used 100 trees and was evaluated using the same metrics. Feature importance was analyzed and visualized with a bar chart.

Finally, 5-fold cross-validation was applied to both models to ensure consistent performance. The Random Forest generally showed higher accuracy and stability.

This task improved our understanding of decision boundaries, overfitting, feature importance, and ensemble learning in machine learning workflows.
