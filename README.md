# Tree-Based Classification Model for Predicting Employee Churn

**Project Overview**  
The objective of this capstone project is to analyze data from a hypothetical corporation to assess the factors driving employee churn. In the final iteration, the Random Forest model achieved an accuracy of 96%, a recall of 90%, and an F1 score of 88%. This model identified the most predictive features that determine whether employees stay or leave. The key factors include 'number_project,' 'last_evaluation,' 'tenure,' and 'overworked.'

**Business Understanding**  
The primary stakeholders for this project were the HR department, which aimed to gain deeper insights into employee churn. The findings from this analysis are intended to inform data-driven decisions that enhance employee satisfaction and engagement, ultimately leading to improved retention rates.

**Data Understanding**  
The dataset used in this analysis contains self-reported information from employees of a fictitious multinational vehicle manufacturing corporation. It consists of 14999 rows and 10 features (columns) of various data types (float64, int64, and object). To prepare the data for modeling, we addressed duplicates, outliers, and missing values. Additionally, we engineered a boolean feature called 'overworked' to represent employees who worked more than 175 hours; this feature was incorporated in the second iteration of the Random Forest model.

**Modeling and Evaluation**  
The final Random Forest model, which included the engineered feature 'overworked,' was employed to identify the most predictive factors for evaluating whether an employee would leave or stay. The following features were found to be the most significant:

Feature Importances
- number_project: 0.367225
- last_evaluation: 0.311365
- tenure: 0.236839
- overworked: 0.079686

The evaluation scores demonstrate strong performance, particularly in terms of accuracy and recall:

Model Scoring Metrics
- AUC: 0.970929  
- Accuracy: 0.966448  
- Precision: 0.895719  
- Recall: 0.906459  
- F-score: 1 - 0.900985  

**Conclusion**  
The analysis concluded that employees at Salifort Motors often feel overworked, which leads to dissatisfaction and higher churn rates. The factors contributing to this issue include the number of hours worked, the number of projects assigned, evaluation scores, and, to a lesser extent, salary.

To improve the work culture and address these issues, it is recommended to implement actions such as capping working hours, recognizing and rewarding employees who put in extra effort, limiting the number of concurrent projects, conducting more frequent company meetings to discuss concerns, and considering long-tenured employees for promotions.
