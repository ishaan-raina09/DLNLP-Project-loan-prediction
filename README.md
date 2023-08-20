# Deep Learning - Loan Approval Project

We, group-2 of DLNLP Project course have made the following project;

Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), a model that can predict wether a borrower will pay back their loan is built. This way in the future decision about a potential customer can be assessed on their likeliness to pay back the loan. This is a binary classification type of prediction

## About Data
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California.[3] It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

The data is obtained from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club

*  The "loan_status" column is the label.


  - Did this by using
  from tensorflow.keras.models import load_model
  model.load('Lending_club_binary_classification.h5')
  



