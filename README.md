# XAI-Explainable-AI-SHAP-LIME
An Explainable AI model to understand the working of SHAP and LIME models
SHAP (SHapley Additive exPlanations) is a machine learning interpretability technique that helps to explain the output of complex models by quantifying the contribution of each input feature to the model's prediction for a given instance.

The basic idea behind SHAP is to use game theory to assign "importance scores" to each feature, based on how much they contribute to the final output of the model. Specifically, SHAP uses the Shapley value concept from cooperative game theory to allocate credit for the model output among the input features.

In simple terms, the Shapley value of a feature is the average marginal contribution of that feature to the model output, across all possible combinations of features. By computing the Shapley values for each feature, SHAP can provide a global or local explanation of how each feature affects the model's prediction for a specific instance.

For example, suppose we have a model that predicts the price of a house based on its location, size, number of bedrooms, and other features. We can use SHAP to determine how much each feature contributes to the predicted price for a particular house. By analyzing the SHAP values, we can determine which features have the most significant impact on the predicted price, and how different values of each feature affect the prediction.

Overall, SHAP provides a powerful tool for understanding the behavior of complex machine learning models and explaining their predictions in a way that is both intuitive and actionable.
To make the model more interpretable, I used SHAP and LIME, two popular model interpretation techniques. SHAP uses game theory concepts to assign importance scores to the features used in the model, helping me to identify which features were most important for making predictions. LIME, on the other hand, generates local explanations for individual predictions by creating a simpler model that approximates the original model in the vicinity of a particular prediction.

By applying SHAP and LIME, I was able to create an explainable AI model that not only accurately predicted the outcome of breast cancer patients but also provided insights into which factors were most important in making those predictions. This type of approach can help to build trust in AI models and ensure that decisions made using those models are transparent and fair. Looking forward to sharing more about this exciting project and exploring more ways to make AI models more explainable
