# Plagiarism-Detector

This project implements a plagiarism detector program in Amazon SageMaker. It compares answers to an existing reference and determines whether the answer was plagiarized or not through binary classification, depending on how similar is the answer to the reference text. 

The files included are:

1- 2_Plagiarism_Feature_Engineering.ipynb: performs data analysis on the texts and calculates their closenes to the reference text depending on various measures of distance between texts, such as containment and largest common subsequence (lcs).

2- 3_Training_a_Model.ipynb: trains the binary classifier and test its performance.

3- helpers.py: include some helper functions

4- problem_unittests.py: include functions needed for the notebooks.

5- source_sklearn: is a directory that has a single file containing the definition of the binary classifier used.
