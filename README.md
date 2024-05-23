# Fraud Detection

#Dataset: Synthetic Financial Datasets For Fraud Detection


Fraud detection research in financial services, especially mobile money, faces a data gap due to the privacy of financial transactions. It uses aggregated data from private sources to simulate regular activity and inject fraudulent behavior, allowing researchers to test fraud detection methods without risking sensitive information.





step: A unit of time representing one hour in the real world. The total number of steps is 744, corresponding to a 30-day simulation.

type: The type of transaction. The possible types are CASH-IN, CASH-OUT, DEBIT, PAYMENT, and TRANSFER.

amount: The transaction amount in local currency.

nameOrig: The customer who initiated the transaction.

oldbalanceOrg: The initial balance of the customer before the transaction.

newbalanceOrig: The new balance of the customer after the transaction.

nameDest: The recipient of the transaction.

oldbalanceDest: The initial balance of the recipient before the transaction. There is no information for customers whose names start with "M" (indicating merchants).

newbalanceDest: The new balance of the recipient after the transaction. As with "oldbalanceDest," there is no information for customers whose names start with "M."

isFraud: Indicates whether a transaction is fraudulent. In this dataset, fraudulent behavior involves gaining control of customer accounts, attempting to transfer funds to another account, and then cashing out.

isFlaggedFraud: Flags transactions that exceed a certain threshold. In this dataset, transfers over 200,000 in a single transaction are flagged as potentially fraudulent.

These fields form the basis of the synthetic dataset, providing a comprehensive view of transaction activities while offering opportunities to study and test fraud detection methods
