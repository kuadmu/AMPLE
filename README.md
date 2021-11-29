# AMPLE

This is the data sample for 'Adaptive Multi-Task Positive-Unlabeled Learning for Joint Prediction of Multiple Chronic Diseases Using Online Shopping Behaviors'.

**Instance:** 

69,22,55,46,73,5,0,1,37,31,9,56,41,59,84,6,110,8 &nbsp;&nbsp; 4,1,1,1,1,1,1,2,1,1,2,1,1,5,1,1,1,1 &nbsp;&nbsp; 2,6,5,8,2,1,11,2,2,2,3,5,5,9,2,7,16,0 &nbsp;&nbsp; 0,1 &nbsp;&nbsp; 0,1  

**Description:**

Each instance consists of 5 columns, split by \t\t. 

**Column 1** shows a sequence of product ids.

**Column 2** shows a sequence of purchase frequencies.

**Column 3** shows a sequence of product category ids.

For **Column1**, **Column 2**, and **Column 3**,  there is a one-to-one correspondence exists between elements at each position.

**Column 4** shows two labels for depression and diabetes --- 0: unlabeled; 1: positive (used for training, validation, and calculating Precision, Recall, F1 Score, and F2 Score)

**Column 5** shows two additional labels for depression and diabetes --- 0: unlabeled; 1: latent positive (used in the elaborated evaluation scenario)

Note that each positive instance is replicated with a minor disturbance 20 times during the training phase to address the imbalanced data.
