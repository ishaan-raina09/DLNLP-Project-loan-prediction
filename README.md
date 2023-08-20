# Deep Learning - Portfolio Project

Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), a model that can predict wether a borrower will pay back their loan is built. This way in the future decision about a potential customer can be assessed on their likeliness to pay back the loan. This is a binary classification type of prediction

## About Data
LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California.[3] It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

The data is a subset of the LendingClub DataSet obtained from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club
Source: Udemy course - Python for Data Science and Machine Learning Bootcamp

*  The "loan_status" column is the label.

### How to:
* **The trained model can be loaded and predtions can be made by loaidng the .h5 file.**
  - Do this by using
  from tensorflow.keras.models import load_model
  model.load('Lending_club_binary_classification.h5')
  
* **To run the model directly, just run the .ipynb flie in jupyter notebook.**


