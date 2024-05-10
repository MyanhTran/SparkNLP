# Project Description
Use AGNews dataset (check reference 1 about how you can download it) to train for 5 epochs and compare
the performance of these different models:

a) Use BERT embeddings with a generic annotator model in SparkNLP called ClassifierDL, without
any text preprocessing steps and find the test accuracy for it. 

b) Add preprocessing steps, specifically lemmatization and stop word removal, to the pipeline in (a)
and compare its impact on the overall performance of the model. Report the test accuracies when
each step is implemented individually and when they are used together. Identify the pipeline that
yields the highest test accuracy and give a brief explanation of why it performs the best.

c) Lastly, select the best pipeline from (a) and (b) and use RoBerta embeddings instead of BERT
embeddings. Report which embedding gives the best results and why.
