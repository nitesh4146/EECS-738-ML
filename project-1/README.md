## EECS738 Project 1
### Submitted by  : Nitish Gupta
### Date          : 03/01/2021


## Gussian Mixture Model
This project implements Gussian Mixture Model and it's expectaition maximization algorithm. We further dive deeper into three different dataset from [UCI ML dataset](https://archive.ics.uci.edu/ml/datasets.php), namely,  
[1] Iris
[2] Wisconsin Diagnostic Breast Cancer¶
[3] Wine Quality

![GMM](./images/gmm.png)  
[src: https://medium.com/@SeoJaeDuk/archived-post-multivariate-gaussian-distributions-and-entropy-3-991578ca534c]  


### Correlation Matrix (Wine Quality Dataset)  
Strong correlation implies higher effect on output feature. Selecting the best correlation features gives more accurate and generalized clustering output.  
![corr](./images/data3_corr.png)  

### Histograms of individual feature vectors
![hist](./images/data3_hist.png)  


### Log-Likelihood plot
![log](./images/data1_loglike.png)  

### Prediction vs Actual Output Cluster (feature)
![predict](./images/data2_pred.png)  
