In this lab, I implemented the Naive Bayes algorithm in Python from scratch and I used it to tackle the
“20 Newsgroups “ classification problem. The model is multinomial and uses the “bag of words”
approach. The summaries below show the class priors, overall accuracies, class accuracies, and
confusion matrices for both training and testing data for two different posterior probability estimators:
the maximum likelihood estimator (MLE) and the Bayesian estimator (BE).


The program naiveBayes2.py must be run with python3 (it was made with and tested with Python 3.5.2). Also, the program is multithreaded and will use all cores availible. (It was tested on a laptop with 8 cores and 16 GB memory and it runs for about a minute.)

The following libraries must be installed:
csv
itertools
multiprocessing
math
pprint
pandas
sys

run the following command to install any library: python3 -m pip install library --user

usage:
type into terminal: python3 naiveBayes2.py train_label.csv train_data.csv test_label.csv test_data.csv vocabulary.txt
