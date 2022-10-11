# deep-learning

We modeled a network to predict successful applicates in ventures. We used the "IS_SUCCESSFUL" variable as our determining measure. We also used APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS,and ASK_AMT as factors in our determination.

We did not use "EIN" or "NAME" as we determined those were not relevant variables for this determinantion.

Our model was able to predict with a high degree of success which applications would be successful. The key factor in making our model more accurate was changing one of our layesr from ReLU to Sigmoid. The S-Shaped curve mapped the input values better and produced a much higher accuracy.