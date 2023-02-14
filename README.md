## Ryerson University - Data Analytics, Big Data, and Predictive Analytics Certification Final Capstone Project:

### Heart Disease Classification Project

**Code**: [CIND820_Final_Results.ipynb](https://github.com/swb1113/Heart_Disease_Classification/blob/main/CIND820_Final_Results.ipynb)  
**Final Report**:  
**Presentation**:  
**Description**: My final capstone project for the 12 month data analytics certificate program from Ryerson University. The focus of my capstone project was to utilize classification (supervised learning) to develop a prediction algorithm. 
Developed both a decision tree-based (random forest) and a logistic regression model to predict heart disease events. 
The efficacy of both models were compared to determine which model was more effective in predicting heart disease events. 
The project also included data exploration and visualization. 
The “Heart Failure Prediction Dataset” found publicly on Kaggle.com was used to train and test the models. 
Lastly, the project was programmed in python using Jupyter notebook and various libraries such as numpy, pandas, matplotlib, seaborn, and sklearn.  
**Skills**: Data cleaning and preprocessing, data analysis, descriptive statistics, random forest model, logistic regression model, stratified K fold validation, feature importance, logisitic coefficients, ROC curve, precision-recall curve.  
**Technology**: Python, sklearn, numpy, pandas, matplotlib, seaborn, plotly, Google collab.  
**Results**: Achieved a final grade of **A**. Overall, both the binary classifiers performed very similarly as both the models had an average accuracy of around 83%. In terms of precision and recall, both the models had a precision of 85% (indicating a low false positive rate), while the random forest model had a recall of 86% and the logistic regression had a recall of 85% (indicating a low false negative rate). The AUC and AP scores also showcase the similarity in the logistic regression and random forest models, both models achieved an AUC score of 0.85, and an AP score of 0.87 and 0.88 respectively.

There were several shortcomings in regard to the methodology of the capstone project. For instance, feature engineering would have benefitted the project in removing less important attributes when training the models. Furthermore, as the evaluation metrics are so similar across both models, it may benefit from increasing the number of folds, experimenting with other aspects of the model to improve model performance or to compare both the models with a different tree-based model (such as decision tree classifier or XGBoost).

bold text In conclusion, this capstone project has shown that cardiovascular disease prevalence can be predicted with the use of simple machine learning algorithms such as logistic regression and random forest models. The continuation of this field of research is pivotal towards introducing the benefits of machine learning algorithms in the use of healthcare industries. The next steps of research should include increasing the complexity and optimization of the algorithms to increase their efficiency and efficacy. The use of live data would also benefit to further test the real world effectiveness of the models.   
