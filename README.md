# Machine-Learning-Lab-Program-1 :v:
Implement and demonstratethe FIND-Salgorithm for finding the most specific hypothesis based on a given set of training data samples. Read the training data from a .CSV file. :fire:
**This program is written without using python packages.** :blush:

#Find-S Algorithm
##Algorithm:
Initialize h to the most specific hypothesis in H
For each positive training instance x
 i. For each attribute constraint a i in h :
     a. If the constraint a i in h is satisfied by x Then do nothing
     b. Else replace a i in h by the next more general constraint that is satisfied by x
Output hypothesis h
