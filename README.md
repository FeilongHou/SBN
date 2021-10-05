# SBN
# Introduction
This is the final project for MATH 189. \
In this project, we need to exam the Swiss Bank Note dataset(SBN.txt) in order 
to predict whether a note is false or counterfeit using supervised learning.

# Conclusion
In this project we performed training of 2 models, LDA and Logistic Regression, on Swiss Bank Notes dataset. Then we attempt to do Factor Analysis in order to reduction dimensions of dataset to see if there is any improvement in prediction accuracy.\
It is not waste of time doing factor analysis, we saw increase in accuracy about 9% for Logistic Regression and no significant improvement for LDA. But the increase in accuracy is relatively small with the fact that we have fairly high accuracy of 91% before factor analysis. We can save time by using initial model and still having high accuracy. But going from 91% to almost 100% accuracy is still a great improvement. Depends on the circumstances, factor analysis can be applied to increase accuracy.\
We suggest using LDA for initial dataset since it has the least violation, easy to setup and have great accuracy of 99.5%. Since there are violations for models, PCA, and factor model. We should take the model accuracy with some grain of salt. \
Keep in mind that we are working with a very small sample size. All the results may change if we have a sufficiently large sample size. With a larger sample size, we can divide dataset into training group and testing group, and test our model after training to future comfirm the true accuracy of our model. We highly recommend to repeat this analysis with a larger sample.\
