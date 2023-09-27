Terrain Identification from Time Series Data
============================================
This is a classification task to find different terrains from time series data. The idea is to train a neural network using given data to classify which terrain an unknown data represents. 
Class label 0 represents "standing/walking"
1 represents "going downstairs"
2 : "going upstairs"
And 3: "walking on grass". 
We use F1 macro score as the evaluation metric.


Files
-----

The repository contains 3 Jupyter notebooks: NN_C1.ipynb, NN_C2.ipynb and NN_C3.ipynb.
* NN_C1 runs a random forest model for predictions
* NN_C2 uses 2 1D CNN model
* NN_C3 uses a BiLSTM model. 



Installation notes
--------------------

These files were developed and tested on Google Colab, python version 3.9 and GPU Nvidia K80 / T4. 
