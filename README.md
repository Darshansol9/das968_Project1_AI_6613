# Project1_AI_6613
Condata_2019 Kaggle Competition

Reasons For using Decision Tree algorithms:<br>

They are good at predciting multi-classification problems wherein each algorithm try to build multiple trees and make prediction.
XGBoost - This algorithm learn from weak learner and try to minimize the penality incurred by giving importance to misclassified tuples by increasing their weights. Also it regularize the tree grown to maintain the complexity of th tree grown and accuracy of the model by not computing complex weights. 

RandomForest - Defines best split by computing entropy and information gain from chosen set of variables. It then keeps on creating the tree in same fashion until a stopping criterion is not met. Classification is done of majority voting technique and the class getting maximum probability gets the vote. It is slow as compare to XGBoost but give pretty good results.

ExtraTreeClassifier - Works same as RF, but instead of perfect split it randomly chose variable from selected features as node and make a split. In this fashion, it is fastest among all these algorithms that' why I chose to showcase the balance between time complexity and accuracy. We can observe in the kernel, the accuracy do expect to decrease as compared to RF and XGBoost but it does not comprise to that extend. It is useful to apply such algorithms where running time is managed and accuracy is not ruined.


Everything else is written inside .ipynb file, each section corresponding to the code.<br>
I have cited the resources and videos I learnt to apply in this project<br>

