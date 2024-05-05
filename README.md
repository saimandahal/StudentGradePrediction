# Student Grade Prediction System Using Improved Random Forest Algorithm.​
## Saiman Dahal. Washington State University
#
Improved Random forest: It is the combined process of bootstrapping without replacement, random split node and aggregation of the output.

### Algorithm:
Pick a random split.​

Input: subset S and an attribute a​

Output: a split​

    K number of attributes randomly selected at each node. (a1,...ak)​

    A random cut-point ac selected uniformly in [amax , amin]​

    Return the split [a < ac].​

    If all attributes are in the subset S, then stop split.​

    Return a split such that max(Score(S))​