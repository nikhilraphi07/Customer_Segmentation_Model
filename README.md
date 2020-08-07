## Customer Segmentation Model

![Customer](https://i.ibb.co/J3PR0m0/term-deposit.png)


### Machine Learning Model to predict whether the customer will subscribe to a Long Term deposit or not with the bank

#### Business Use Case

There has been a revenue decline for a Portuguese bank and they would like to know what actions to take. After investigation, they found out that the root cause is that their clients are not depositing as frequently as before. Knowing that term deposits allow banks to hold onto a deposit for a specific amount of time, so banks can invest in higher gain financial products to make a profit. In addition, banks also hold better chance to persuade term deposit clients into buying other products such as funds or insurance to further increase their revenues. As a result, the Portuguese bank would like to identify existing clients that have higher chance to subscribe for a term deposit and focus marketing efforts on such clients.

#### Data Science Problem Statement
Predict if the client will subscribe to a term deposit based on the analysis of the marketing campaigns the bank performed.

### Run 
================================================================================
- Download the .ipynb i.e the Python Notebook and run the same on Jupyter or Spyder or any open source web application

### Tech Stack (Algorithm's Implemented)
- Vanilla Model for below 3 algorithm's are used as Baseline Model
- Logistic Regresssion
- Random Forest
- Decision Tree

- Also Grid Search CV for Random Forest 
- Ensemble Learning Models

## Project Structure
- Customer_Segmentation_Model.ipynb - The python notebook containing the Machine Learning Model
- new_test.csv - This is the dataset that is used to test the model performance
- new_train.csv - This is the historic dataset used to train the model
- preprocessed_data.csv - The cleansed dataset after performing Missing value treatment, Outlier Detection and EDA. This data is then passed to the model
