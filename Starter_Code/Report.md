Overview of the Analysis
    The purpose of this analysis was to check the credit risk of multiple people before giving them a loan they will be unable to pay back. The information that was used to predict this was a number of things such as : loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts ,derogatory_marks, total_debt and loan_status.
    The data set is a total of 77,535 inputs. The data was split into a training and testing set in order to cross check the information. We started with bulding a Logistic Regression Model to determine whether the borrower in the testing set would be a low or high risk for the loan they requested. It generated ------ data points showing low-risk(0) and high risk (1)
Results:
    Logistic Regression Model
        It has a high accuracy (99.2%), indicating that it correctly predicts both 0 and 1 labels with high overall correctness.
        The precision (87.3%) and recall (94.9%) for the 1 (high-risk loan) label are also reasonably high, suggesting that the model is effective in identifying high-risk loans when they are present.

•	True Positives (TP): 593 (These are the high-risk loans correctly predicted as high-risk.)

•	True Negatives (TN): 18673 (These are the healthy loans correctly predicted as healthy.)

•	False Positives (FP): 86 (These are the healthy loans incorrectly predicted as high-risk.)

•	False Negatives (FN): 32 (These are the high-risk loans incorrectly predicted as healthy.)
