
### No Free Lunch Theorem

Data Generating Process - Raw_data - Actual distribution [Machine Learning assumes same apriori data distribution for all observed data, or for previously unobserved data]

[All classifiers have same error rate]

![[Pasted image 20221203124802.png]]
**state[s] that any two optimization algorithms are equivalent when their performance is averaged across all possible problems**




### Regularization 

Consider for a logistic regression process : the Error or Loss function -  $J(\vec{w})= MSE_{train}(\vec{w})+\lambda \vec{w}^{T}\vec{w}$  - which says $\lambda$ to be the strength of preference for smaller values of $\vec{w}$. 



### Hyperparameter and Validation Dataset 

Bayesian Optimization for Updating the hyperparameters of the model - black-box optimization, and not an analytic process. **This optimization requires a sequential strategy for obtaining the actual value from the measurements by updating our hypotheses of our belief-space to look at certain areas of the hyperparameter-space** . These are the parameters that determine to a great extent the behaviour of the model.


#### model-based black-box optimization 

Whenever I have any blackbox-operation over any function, I can throw this process at it and obtain a very relevant optimization.