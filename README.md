# Dataset-Training-with-Python
Project Description
This project focuses on utilizing three different learning methods to predict the number of shares and revenue for their respective dataset. The attributes relevant for training were identified, and data exploration was conducted to understand the relationships between variables. Data cleaning involved removing irrelevant attributes to optimize resource usage. Code was done and exported from Google Colab. Data exploration and data cleaning process was performed in Python to maintain integrity of dataset.

Learning Methods
KNN Nearest Neighbor: Utilized to analyze the attributes closest to the target (shares/revenue).
Decision Tree: Chosen for its interpretability and ability to handle various attributes. 
SVM: Selected for its practical application with numerical values. Effective for the high-dimensional dataset 1.
Evaluation
Accuracy was used as the performance measure to determine the effectiveness of each learning method. The news dataset had low accuracy due to the use of reduced number of attributes and the prediction of exact share numbers. In contrast, the shoppers dataset achieved significantly higher accuracy rates with reduced attributes. The compile time for the 1st dataset was 49 minutes, while 2nd dataset code compiled in 6 seconds.

In the news dataset, sacrificing accuracy for faster compilation time was necessary. To improve accuracy, additional attributes could be included to train the classifiers more accurately predict the # of shares, in doing so however would significantly increase compilation time. The shoppers dataset demonstrated better performance due to reduced attributes and categorical measures.


