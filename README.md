<h2>About the Data</h2>
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
<br>
<br>
<h2>Exploratory Data Analysis and Preprocessing</h2>
During data exploration and preprocessing steps, I examined the distribution of some important features, checked for missing and duplicate values, and looked for potential outliers. Data cleaning involved handling missing values, removing outliers if necessary, removing excesive skewness, scaling the numerical features and encoding categorical variables if applicable. Feature engineering in the later step of training included creating a new feature.
<br>
<br>
<h2>Objectives</h2>
The main objective of this analysis is to develop classification models to predict the target variable accurately while maintaining interpretability. The focus is primarily on prediction, but it's essential to understand the relationships between the predictors and the target variable for interpretability purposes.
<br>
<br>
<h2>Summary of the Classification Models:</h2>

Five classification models were trained and evaluated:
<br>
<br>
* Logistic Regression Model: Achieved moderate training and test scores with a moderate root mean squared error (RMSE). It demonstrates moderate performance in capturing linear relationships between features and the target variable.
<br>
<br>
* Ridge Classifier Model: Performed decently with a slightly higher test score compared to logistic regression. It provides a regularization technique to mitigate multicollinearity and overfitting, resulting in robust model performance.
<br>
<br>
* Decision Tree Classifier Model: Demonstrated strong training and test scores, indicating its ability to capture complex relationships in the data. However, it has a slightly higher RMSE compared to other models, suggesting some variability in predictions.
<br>
<br>
* XGBoost Classifier Model: Exhibited high training and test scores with a relatively low RMSE, indicating its robustness and effectiveness in handling complex datasets. It utilizes an ensemble of decision trees to improve predictive accuracy.
<br>
<br>
* LightGBM Classifier Model: Outperformed other models with the highest test score and lowest RMSE. It leverages gradient boosting and histogram-based algorithms to efficiently handle large datasets and capture intricate patterns in the data.
<br>
<br>
<b>Recommendation for the Final Model:</b>
Based on the results, the LightGBM Classifier model appears to be the most suitable final model. It achieved the lowest root mean squared error (RMSE) and a relatively higher test score compared to the other models. Thus, the LightGBM Classifier model captures complex patterns in the data more successfully, enhancing its predictive performance.
<br>
<br>
<h2>Insights and key findings</h2>
Among the evaluated classification models, LightGBM emerged as the top performer, exhibiting the highest test score and lowest RMSE. Decision tree classifiers also showed promise in capturing complex relationships, while ridge regularization enhanced stability in logistic regression. Overall, LightGBM's superior performance and efficiency make it the recommended choice for deployment.
