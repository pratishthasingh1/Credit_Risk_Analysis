Overview: 
A credit risk analysis was conducted to determine if someone qualifies for a loan or not. 6 machine learning models were used against data to see which yields the most accurate results. Using Python and SKLearn and Imbalanced Learn softwares in Jupyter Notebook, data was oversampled and undersampled to determine balance accuracy scores, precision and recall. 

Results:
1. Naive Random Oversampling: 
* balanced accuracy scores 65.58%
* precision 99%
* recall scores 66%

2. SMOTE:
* balanced accuracy scores 65.12%
* precision 99%
* recall scores 66%

3. Cluster Centroids Sampler:
* balanced accuracy scores 52.98%
* precision 99%
* recall scores 41%

4. SMOTEENN:
* balanced accuracy scores 61.75%
* precision 99%
* recall scores 53%

5. Balanced Random Forest Classifer:
* balanced accuracy scores 95.44%
* precision 100%
* recall scores 91%

6. AdaBoost Classifer
* balanced accuracy scores 92.54%%
* precision 99%
* recall scores 94%

Summary: 
* Results of machine learning models: Overall, it seems the most accurate models are the ensemble learners -- Balanced Random Forest Classifer and AdaBoost Classifer. Both machine learning models have a high balanced accuracy score as well as a high precision and recall scores. 
* Out of the two, I would recommend using the balanced random forest classifer as that one is the most accurate out of all the models used. 