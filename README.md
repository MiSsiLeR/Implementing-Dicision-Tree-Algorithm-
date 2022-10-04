# Implementing-Dicision-Tree-Algorithm-
Software Used: Python, Google Colab, Sklearn.

Decision Tree:
  Introduction
  Decision tree methodology is a commonly used data mining method for establishing 
  classification systems based on multiple covariates or for developing prediction 
  algorithms for a target variable. This method classifies a population into branch-like 
  segments that construct an inverted tree with a root node, internal nodes, and leaf 
  nodes. The algorithm is non-parametric and can efficiently deal with large, 
  complicated datasets without imposing a complicated parametric structure. When 
  the sample size is large enough, study data can be divided into training and 
  validation datasets. Using the training dataset to build a decision tree model and a 
  validation dataset to decide on the appropriate tree size needed to achieve the 
  optimal final model.
    Decision trees have three main parts: a root node, leaf nodes and branches. The root 
node is the starting point of the tree, and both root and leaf nodes contain questions 
or criteria to be answered. Branches are arrows connecting nodes, showing the flow 
from question to answer
   
   Root - This is always the first node in the path. It is the node from which all other 
decision, chance, and end nodes eventually branch.
Leaf - These show the end of a decision path (or outcome). You can always identify a 
leaf node because it doesn’t split, or branch any further. Just like a real leaf!
Branches - Branching or ‘splitting’ is what we call it when any node divides into two 
or more sub-nodes. These sub-nodes can be another internal node, or they can lead 
to an outcome (a leaf/ end node.)

Train Test Split:
  Scikit-learn alias Sklearn is the most useful and robust library for machine learning 
  in Python. The scikit-learn library provides us with the model_selection module in 
  which we have the splitter function train_test_split().
  Train test Splits arrays or matrices into random train and test subsets.
  Train Test Split is imported using 
  from sklearn.model_selection import train_test_split
  Parameters
  sklearn.model_selection.train_test_split(*arrays, test_size=None, train_size=None, 
  random_state=None, shuffle=True, stratify=None)[sourc]
