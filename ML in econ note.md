
# Dario Sansone HP 
## paper to start with 
-   Mullainathan and Spiess ([Journal of Economic Perspectives](https://www.aeaweb.org/articles?id=10.1257/jep.31.2.87), 2017) is a good introduction to ML for economist. The Online Appendix has a lot of important technical details to implement ML algorithms in practice
    
-   The Impact of Machine Learning on Economics by Athey ([NBER](https://www.nber.org/chapters/c14009.pdf), 2018)
    
-   Machine Learning Methods That Economists Should Know About by Athey and Imbens ([ArXiv](https://arxiv.org/abs/1903.10075), 2019; [ARE](https://doi.org/10.1146/annurev-economics-080217-053433), 2022)
    
-   Deep Learning for Economists by Dell: [NBER paper](https://www.nber.org/papers/w32768) and [website EconDL](https://econdl.github.io/)
    
-   Literature review by Bahoo et al. ([JoES](https://doi.org/10.1111/joes.12694), 2025). See also overview by Strittmatter (IZA, [2025](http://dx.doi.org/10.15185/izawol.516))

>   [Vikesh Koul](https://github.com/vkoul/Economics-and-Data-Science) has a comprehensive list of resources at the intersection of Data Science and Economics/Social Science/Policy

### Mullainathan and Spiess (JEP, 2017) 
- supervised ML is used for prediction using the complicated data without simply overfitting 
- the logic of ML: is to min the prediction loss 
	- the prediction power of ML is indeed better than OLS 
		- OLS: just linear function; ML: nonlinear and interactive functions 
- ML regression trees - can be considered as linear function with many interactive dummies 
	- deeper the tree, the better fitness within sample, the bigger overfitting 
- ML to avoid overfitting: regularization and empirical tuning (cross validation)
	- (1) conditional on the regularizer constraint, find the optimal loss-minimizing function 
	- (2) estimate the optimal regularizer using empirical tuning 
- ML other methods 
	- LASSO: (probably the machine learning tool most familiar to economists) corresponds to 1) a quadratic loss function, 2) a class of *linear* functions (over some fixed set of possible variables), and 3) a regularizer which is the sum of absolute values of coefficients.
	- random forest: average over many regression trees  
	- neural nets: for binary prediction, use nested logistic regression 
	- ensemble method: average different algorithm method, weights calculated by cross validation 
- economic theory first to choose the model, data var -- to set up the structure, then ML comes in 


<!--stackedit_data:
eyJoaXN0b3J5IjpbMzY2ODEyNjM4XX0=
-->