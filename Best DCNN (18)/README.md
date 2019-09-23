# Best DCNN Results - Examples and Tools

## To view results:
All results and calculations related to Net 18, the current best DCNN at classifying 1D CAs, are available in the Mathematica notebook _Random Colours(Beast-ECA19r200)(updated).nb_.  Note that Net 19 is also in this file, but is no better than 18 despite being a massive weights file (about 181MB).  Make sure to have the weights file _netECA18-r200.wlnet_ in your notebook directory, and load it before doing anything with it in this notebook.

## To hunt CAs:
1. Place netECA18-r200.wlnet in same directory as CA-Search-NN.nb
2. Open the notebook and run the initialisation cells
3. Type _HuntCA[r, k, num]_ to check for Class 4 CAs with range _r_, _k_ colours, out of _num_ randomly-generated candidates
