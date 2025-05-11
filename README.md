This project focuses on predicting district-wise rainfall in Telangana using advanced machine learning algorithms: Support Vector Machine (SVM), Random Forest (RF), and XGBoost (XGB). The goal is to provide accurate and interpretable rainfall forecasts for better planning in agriculture, water resource management, and disaster preparedness.

We trained all three models using historical rainfall data and relevant climatic features. The SVM model focuses on finding the best hyperplane that separates rainfall data patterns. RF uses multiple decision trees and averages their outputs to improve prediction accuracy and reduce overfitting. XGBoost, a powerful boosting algorithm, optimizes prediction through gradient descent and has shown high performance in structured data tasks.

The predictions from each model are displayed using geospatial visualizations on choropleth maps. These maps show rainfall intensity across different districts using color gradients:

SVM predictions tend to cluster around a narrow range, offering more conservative results.

RF predictions reveal a broader spread, capturing variation in local climate effectively.

XGBoost predictions provide a balanced mix of depth and accuracy, showing fine-grained regional differences.

![Screenshot 2025-04-28 143837](https://github.com/user-attachments/assets/d3056a53-6806-48be-82a1-f9a8928246e9)


To make these insights accessible and useful, we developed an interactive web application that integrates all three models. Users can select a specific district and month to view predicted rainfall values. The interface displays model comparisons side-by-side to help users understand which model performs better in various scenarios. The web platform also includes map-based visualizations powered by OpenStreetMap, ensuring an intuitive and user-friendly experience.

This system is especially useful for stakeholders such as farmers, meteorologists, and policymakers. With early rainfall predictions, crop planning and water resource allocation can be improved. Additionally, this tool can support ongoing research in climate modeling and regional weather forecasting.
output:
![Screenshot 2025-04-10 112026](https://github.com/user-attachments/assets/e9867a39-5c75-4aa3-9617-7735c545e89a)
![Screenshot 2025-04-04 112223](https://github.com/user-attachments/assets/67a53fd2-5d69-4695-b46b-0542b8b8a7d5)

