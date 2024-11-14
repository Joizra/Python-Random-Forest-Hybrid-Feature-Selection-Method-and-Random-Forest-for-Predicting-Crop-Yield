# Python-Hybrid Feature Selection Method and Random Forest for Predicting Crop Yield

## Executive Summary
The prediction of crop yield remains a significant concern for farmers, governments, and society, as the volume of crop production impacts food availability. Traditional methods of predicting crop yields have limitations, needing the exploration of more efficient techniques. In recent years, the use of Machine Learning, particularly the Random Forest algorithm, has increased. However, a primary challenge in applying machine learning is the process of feature selection. To address this issue, this project proposes a hybrid method that combines causal discovery and backward feature selection for selecting features, along with the Random Forest algorithm for training the dataset to develop a predictive model capable of estimating crop yields. The proposed methodology has been implemented on a dataset comprising soil and weather attributes from four locations in Queensland, Australia: Emerald, Dalby, Mungindi, and Taroom. Initially, the methodology is applied to the entire dataset to develop what is referred to as the global model, which is then compared to the performance of the Random Forest alone without the hybrid feature selection method. The results show that the proposed method outperforms the latter. Subsequently, the method is applied individually to each location to construct separate models, resulting in a total of four models, designated as local models 1, 2, 3, and 4, respectively. A comparative performance analysis between the global model and the local models is conducted, resulting that the local models surpass the global model in terms of performance.

## Results
A comparative performance analysis between the Global Model and the Local Models was conducted, revealing that the Local Models surpass the Global Model in performance metrics.

## Methodology
The proposed methodology was implemented on a dataset comprising soil and weather attributes from four locations in Queensland, Australia: Emerald, Dalby, Mungindi, and Taroom. Initially, the methodology was applied to the entire dataset to develop what is known as the Global Model. Subsequently, it was applied individually to each location to construct four distinct models, referred to as Local Models 1, 2, 3, and 4. A comparative performance analysis between the Global Model and the Local Models was conducted, revealing that the Local Models surpass the Global Model in performance metrics.

The approach proposes a hybrid feature selection process that combines causal discovery (PC Algorithm) with backward elimination to construct models that are predictive and also capture the underlying causal relationships within the data, which is crucial for accurate interpretation. A hybrid feature selection methodology outperforms a traditional feature selection process.

The Random Forest model was selected for further experimentation because it surpassed other models, including Linear Regression, Ridge Regression, Lasso Regression, Stochastic Gradient Descent (SGD), and Support Vector Machine (SVM), in terms of performance.

While a Local Model exhibits a better fit and lower errors compared to the Global Model, there is still potential for further improvement.


<p align="center">
  <img src="https://github.com/Joizra/Python-Random-Forest-Hybrid-Feature-Selection-Method-and-Random-Forest-for-Predicting-Crop-Yield/blob/main/Workflow-global%20model.png" width="389" height="504">
</p>
