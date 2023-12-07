# RealEstate
This analysis provides an overview of the analysis conducted on a dataset comprising over 21,613 house sales in King County, USA. The objectives are to explore the dataset and evaluate various models for predicting house prices under two distinct scenarios: regression and classification with neural network models. The ultimate goal of the analysis is to predict house prices if there is a property in the market, which in turn will be beneficial to real eastate companies. The companies could utilize the proposed models to make decision in buying or selling properties for living or commercial purposes, or they could use the information to give advice for their customers who wish to purchase or sell their houses.

Scenario A: Regression Model Evaluation

In the first scenario, two regression models - linear regression and neural networks - are used to predict the house prices. The structure of this scenario include Data Preprocessing and Predictive Modelling sections.

Data Preprocessing
The dataset is found to be highly right-skewed; thus, it is log-transformed in an attempt to return to normal distribution before feeding into the models. The dataset then is splitting into training and validation sets (70:30 ratio). Finally, it will be normalized to the range 0-1 for better model convergence.

Predictive Modelling
A linear regression and a neural network are employed to compare their prediction power for the house prices. The metrics used for performance evaluation include Mean Square Error, Mean Absolute Error, and correlation betwen predicted and true values.

Findings:

Linear Regression: The linear regression model demonstrated a reasonably good performance in predicting house prices. It is interpretable, easy to implement, and provides a baseline for comparison.

Neural Networks: The neural network model has higher predictive capabilities as it can capture non-linear relationships within the dataset.

Scenario B: Classification Model Evaluation

The structure for the second scenario also include , Data Preprocessing and Predictive Modelling sections.

Data Preprocessing
The dataset will go through same data processing steps in scenario A. However, the house price attribute is transformed into a nominal variable, categorizing houses as "High Price" (for prices of  450,000ormore)and"LowPrice"(forpriceslessthan 450,000).

Predictive Modelling
Two classification models are employed: random forest and neural networks to test out their performance. The metrics used for performance evaluation include Mean Square Error, Mean Absolute Error, and correlation betwen predicted and true values.

Findings:

Neural Networks: The neural network classification model displayed commendable classification performance. However, the Random Forest model proves to be better in performance as it is not affected by outliers.

In summary, this analysis determined that for predicting house prices, a neural network regression model outperforms linear regression due to its ability to handle complex relationships. In the classification scenario, a neural network classification model is lesser in performance to Random Forest as it is subjected to outliers. Nonetheless, it is highely believed that by further optimizing the neural network model, it can be a long-term feasible solution for business in house price prediction or classification.
