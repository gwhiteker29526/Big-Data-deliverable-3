# Deliverable 3 – Data Mining Models

## Key Insights

This phase of the project applied classification, clustering, and association rule mining to better understand patterns related to diabetes risk.

The classification models showed that the Decision Tree performed slightly better than the k-NN model in terms of accuracy and F1 score. After applying hyperparameter tuning, the Decision Tree improved further, suggesting it was better at capturing relationships between health indicators and diabetes outcomes.

Clustering revealed that individuals in the dataset can be grouped into distinct categories based on features like BMI, age, and health conditions. Some clusters appeared to represent higher-risk groups, while others reflected healthier populations. This highlights how individuals with similar characteristics tend to share similar health outcomes.

Association rule mining uncovered meaningful relationships between variables such as high blood pressure, high cholesterol, and diabetes. These results suggest that diabetes risk is often influenced by a combination of factors rather than a single condition.

---

## Practical Relevance and Real-World Applications

The findings from this analysis have clear real-world applications, particularly in healthcare and public health.

* Classification models can be used to predict whether a patient is at risk of diabetes based on their health profile, allowing for earlier intervention.
* Clustering can help healthcare providers segment patients into different risk groups, enabling more personalized treatment and prevention strategies.
* Association rules can help identify combinations of conditions that frequently occur together, which can improve screening processes and guide medical decision-making.

Overall, these techniques can support data-driven approaches to disease prevention, patient care, and resource allocation.

---

## Challenges and Solutions

Several challenges were encountered during this phase of the project:

* **Large dataset size:** Processing and visualizing a large dataset required careful handling. This was addressed by using efficient libraries and, when necessary, focusing on key features for visualization.
* **Feature scaling for clustering:** Clustering algorithms like K-Means are sensitive to feature scales. This issue was resolved by applying standardization using a scaler before clustering.
* **Model selection and tuning:** Choosing appropriate models and parameters required experimentation. GridSearchCV was used to systematically test different parameter combinations and identify the best-performing model.
* **Interpreting association rules:** Some generated rules were not meaningful or were too general. This was addressed by adjusting support and confidence thresholds to focus on stronger and more relevant patterns.

---

## Conclusion

This phase demonstrated how multiple data mining techniques can be combined to gain deeper insights into a dataset. By using classification, clustering, and pattern mining together, a more complete understanding of diabetes risk factors was achieved.

These methods highlight the importance of combining different analytical approaches to uncover meaningful patterns and support better decision-making in real-world scenarios.
