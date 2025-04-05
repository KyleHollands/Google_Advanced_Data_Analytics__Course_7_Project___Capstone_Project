# Tree-Based Classification Model for Predicting Employee Churn

**Project Overview**  
The objective of this capstone project is to analyze data from a hypothetical corporation to assess the factors driving employee churn. The data was obtained from the HR department of Salifort Motors and includes information about employees such as hours worked, recent performance review scores, promotion status, and other relevant metrics.

The Logistic Regression model performed reasonably well in predicting employees likely to stay, but its accuracy in identifying those who would leave was not as strong. In contrast, the tree-based models showed significantly better performance, especially the second iteration of the Random Forest model after tuning parameters, dropping irrelevant features, and engineering an additional feature.

**Business Understanding**  
The primary stakeholders in this project were the HR department, which sought deeper insights into employee churn. The findings from this analysis aim to support data-informed decisions that enhance employee satisfaction and engagement, ultimately resulting in improved retention rates.

**Data Understanding**  
The dataset contained various employee-related variables of different formats (float64, int64, and object types), including the number of concurrent projects, evaluation scores, overwork status, salary, and departmental information. With the collected data, exploratory data analysis (EDA) was conducted, visualizations were generated to uncover trends and patterns, statistical tests were carried out to assess feature significance, and both regression and tree-based models were developed.

**Modeling and Evaluation**  
The models employed included Logistic Regression, Decision Trees, and Random Forests. Multiple iterations were conducted after feature engineering and selection to enhance model performance. The final metrics for the top-performing model were:

- AUC: 0.970929  
- Accuracy: 0.966448  
- Precision: 0.895719  
- Recall: 0.906459  
- F-score: 1 - 0.900985  

**Conclusion**  
The analysis concluded that employees at Salifort Motors are often overworked, leading to dissatisfaction and higher churn rates. The factors contributing to this issue include hours worked, the number of projects assigned, evaluation scores, and, to a lesser extent, salary.

The recommendation is to improve the work culture by addressing these issues. Suggested actions include capping hours worked, recognizing and rewarding employees who put in extra hours, limiting the number of concurrent projects, holding more frequent company meetings to discuss concerns, and considering long-tenured employees for promotions.
