# PCA-with-hyper-parameter-optimization
PCA is often applied as a pre-processing step with classifiers. When using PCA in this manner, one must select the number of PC components to use along with parameters in classifier. In this experiment I demonstrate how to perforthis hyper-parameter optimization by:</br>
1)Combine PCA with data scaling.</br>
2)Compute and visualize PC components</br>
3)Select the number of PCs with K-fold cross validation</br>
4)Implement the multi-stage classifier pipeline in sklearn</br>
5)Perform automatic parameter search using GridSearchCV in combination with a pipeline.</br>
The results of this experiment are present in the notebook wine.ipynb
