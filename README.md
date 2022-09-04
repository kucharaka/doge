# DOGE (Dumb Overfitting GINI Evaluation)
1. Init the training sample w/ 2 classes
2. Train any classifier 
3. Draw ROC and put an object at each corner
4. Overfit a high degree polynomial on these objects (choose the degree depending on number of objects in training sample)
5. Integrate resulting polynomial (AUCROC)
6. GINI = 2*AUCROC-1
   
