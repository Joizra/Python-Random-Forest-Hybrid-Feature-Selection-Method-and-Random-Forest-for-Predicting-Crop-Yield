# Python-Hybrid Feature Selection Method and Random Forest for Predicting Crop Yield

The proposed methodology was implemented on a dataset comprising soil and weather attributes from four locations in Queensland, Australia: Emerald, Dalby, Mungindi, and Taroom. Initially, the methodology was applied to the entire dataset to develop what is known as the Global Model. Subsequently, it was applied individually to each location to construct four distinct models, referred to as Local Models 1, 2, 3, and 4. A comparative performance analysis between the Global Model and the Local Models was conducted, revealing that the Local Models surpass the Global Model in performance metrics.

The approach proposes a hybrid feature selection process that combines causal discovery (PC Algorithm) with backward elimination to construct models that are predictive and also capture the underlying causal relationships within the data, which is crucial for accurate interpretation. A hybrid feature selection methodology outperforms a traditional feature selection process.

The Random Forest model was selected for further experimentation because it surpassed other models, including Linear Regression, Ridge Regression, Lasso Regression, Stochastic Gradient Descent (SGD), and Support Vector Machine (SVM), in terms of performance.

While a Local Model exhibits a better fit and lower errors compared to the Global Model, there is still potential for further improvement.


<p align="center">
  <img src="https://github.com/Joizra/Python-Random-Forest-Hybrid-Feature-Selection-Method-and-Random-Forest-for-Predicting-Crop-Yield/blob/main/Workflow-global%20model.png" width="400" height="300">
</p>
