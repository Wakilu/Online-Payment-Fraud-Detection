# Online-Payment-Fraud-Detection
The dataset consists of a list of  1,048,575 customer transaction. The list cuts across different transaction types like cash-out, transfer, payment, cash-in, and debit. 
Several feature indicators were used, these are: step, type, amount, nameorig, newbalanceorg etc.

The below are columns reference:

• step: represents a unit of time where 1 step equals 1 hourt

• type: type of online transaction

• amount: the amount of the transaction

• nameOrig: customer starting the transaction

• oldbalanceOrg: balance before the transaction

• newbalanceOrig: balance after the transaction

• nameDest: recipient of the transaction

• oldbalanceDest: initial balance of recipient before the transaction

• newbalanceDest: the new balance of the recipient after the transaction

• isFraud: fraud transaction.

# Data Analytics Step 

• Data Collection from Blossom Bank
• Clean Data: Exploration and Transformation
• Analyze Data: Modeling and Prediction
• Interpret result: Evaluation

*Inspection: My data was inspected from head to tail.

*Cleaning: I did data cleaning by changed data type, replaced text and removed unnecessary value.

*Feature engineering: With the used of one-hot encoding i converted categorical data to numerical data.

*Feature selection: Relevant data columns was selected for feature and assigned X for it, data colunm isFraud was used as target with named y.

*Modelling: I trained and tested my model on X and Y, after the importation and initializations of ML algorithm.

*Evaluation: Evaluation goes base on accuracy score, precision, and recall.
