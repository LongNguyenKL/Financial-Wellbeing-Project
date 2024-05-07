
# Financial Well-being Evaluation Based on Self-Reported Financial Metrics 


This project aims to identify the key metrics that influence financial well-being. Then, by applying classification machine learning and regression methods, we aim to unravel patterns and correlations that help predict one's financial well-being.

![App Screenshot](https://github.com/LongTheAnalyst/Financial-Wellbeing-Project/assets/168775448/cfcecb65-40ae-43b6-8b10-aeaa3761bb0e)



## Documentation

- NFWBS_PUF_2016_data.csv: data from the [2016 National Financial Well-being Survey](https://www.consumerfinance.gov/documents/5588/cfpb_nfwbs-puf-user-guide.pdf) collected by the Consumer Financial Protection Bureau.
- financial_wb.ipynb: the code for this project
- Project Report - Copy.docx: project final report
- Financial Well-Being.pptx: a summarized result report in PowerPoint format
## Features

Project includes:

- Uploading and cleaning data
- Classification models:
  - Random forest classifier
  - K-nearest neighbor (KNN) Classifier
  - Ada boost classifier
- K-fold cross-validation
- Hyperparameter tuning
- Regression model:
  - Multiple linear regression model
  - Ordinary least squares (OLS) regression model
  - Multicollinearity and variance inflation factor (VIF)
  - Recursive feature elimination (RFE)


## Lessons Learned

Since financial well-being is mostly a human behavioral study, the classification models report quite an impressive accuracy. Among the models mentioned, the random forest classifier returns the best performance based on cross-validation score.

On the other hand, the application of the linear regression model presents certain challenges, indicated by the weak fit. It can be concluded that the relationship between one's financial well-being and the selected attributes.

Using RFE, an individual's mortgage, savings, self-control, health, and material hardship appear to be the most significant predictors of their financial well-being.

There is room for improvement in the regression model. We can reselect the attributes from the survey or transform the variables to address the non-linearity.


## Authors

Thank you to those who have contributed and supported this project:

- [Long Nguyen](https://www.linkedin.com/in/long-nguyen-4583791a2/)
- Kadiatou Sogodogo
- Srujana Bele
- [Prof. Arindam Ray](https://www.linkedin.com/in/arindamray/)

