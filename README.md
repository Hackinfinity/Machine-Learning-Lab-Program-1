# Machine-Learning-Lab-Program-1 :v:
Implement and demonstratethe FIND-Salgorithm for finding the most specific hypothesis based on a given set of training data samples. Read the training data from a .CSV file. :fire: <br/>**This program is written without using python packages.** :blush:

# Find-S Algorithm
## Algorithm:
<p>Initialize h to the most specific hypothesis in H</p>
For each positive training instance x</br>
 <ol>
 <li>i. For each attribute constraint a i in h :
  <ul>
   <li>a. If the constraint a i in h is satisfied by x Then do nothing</li>
   <li>b. Else replace a i in h by the next more general constraint that is satisfied by x</li>
  </ul>
 </li>
 <li>Output hypothesis h</li>
 </ol>
 This program is also available in my Blog <a href="https://www.hackinfinity.weebly.com/mllab1.html">Hack Infinity</a>


