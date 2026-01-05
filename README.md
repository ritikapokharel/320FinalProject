# 320FinalProject


## **Introduction**
Understanding customer shopping behavior is a central goal for businesses seeking to improve marketing strategies, optimize product offerings, and strengthen customer relationships. As consumer preferences evolve and retail competition intensifies, organizations increasingly rely on data-driven insights to guide decision-making.

In this project, we analyze a public dataset of customer transactions to explore broad patterns in shopping habits and the factors that may influence consumer behavior. Beyond general descriptive trends, we focus on two key predictive questions: Can we build a model that accurately predicts whether a customer is likely to use a discount? and Can we predict whether a customer will have an active subscription? These behaviors are important because they relate directly to customer retention, revenue optimization, and personalized marketing strategies.

By applying statistical methods and machine learning techniques, our goal is to identify the variables most strongly associated with discount usage and subscription likelihood, evaluate the predictive strength of multiple models, and generate insights that may support retailers and decision-makers in better understanding their customer base.



## **Project Conclusion**:

Through our analysis of customer shopping data, in conclusion, we curated/explored/modeled purchasing behavior, which answers the questions from the introduction. Through our data analysis, we discovered that the dataset turned out to be uniform. For example, the purchase amounts are evenly distributed, and demographics like Gender and Age show no statistically significant correlation with spending habits, which is reflected by  our T-tests and Pearson correlation (returned high p-values). This can lead retailers to manage resource usage when it comes to demographic analysis.

From our designed primary analysis, we were able to accurately predict whether a customer will use a discount based on a combination of demographic, product, and behavioral features. To capture different patterns in the data, we trained three supervised learning models: Logistic Regression, Random Forest, and XGBoost, each offering useful strengths such as interpretability, robustness to nonlinear relationships, and strong predictive power. These models learn from historical customer data and estimate the likelihood of discount usage by analyzing attributes such as gender, subscription status, shipping type, payment method, season, item color, size, and numerical features like price or quantity. By comparing how these features differ between customers who used discounts and those who did not, the models learn patterns that allow them to classify new customers accurately. We chose this mix of models to balance simplicity and interpretability with more flexible, high-performance methods that can capture complex interactions in the data. Across all metrics, the models performed well, achieving an AUC of 0.92, which indicates excellent ability to distinguish discount users from non-users based on the behavioral and demographic signals captured in the dataset. XGBoost demonstrated the strongest recall for the positive class, making it the most effective at identifying customers who actually used discounts, while Random Forest achieved the highest overall accuracy. Overall, the ML analysis shows that customer discount usage is highly predictable, and the selected models capture these behavioral patterns with strong reliability.

