




------------------------------------------------------------------------------------------
	                   Readme for the BayesDGC & BayesGC Package
	 		       version July, 2020
------------------------------------------------------------------------------------------

The package includes the code of BayesDGC & BayesGC, which solves the crowdsourcing aggregation problem with Bayesian generative learning respectively using features by dnn and only using annotations[1].

[1] S.-Y. Li, S.-J. Huang and S. Chen. Crowdsourcing Aggregation with Deep Bayesian
Learning, submitted to Science China Information Science.
 

ATTN: 
- This package is free for academic usage. You can run it at your own risk. For other
  purposes, please contact Ms. Shao-Yuan Li(lisy@nuaa.edu.cn).

- This package was developed by Ms. Shao-Yuan Li (lisy@nuaa.edu.cn). For any
  problem concerning the code, please feel free to contact Ms. Li.

------------------------------------------------------------------------------------------



Code description: 
BayesDGC.py:  the BayesDGC model proposed in [1] which used both features and annotations for Bayesian deep crowd aggreation.
BayesGC.py:   the BayesGC  model proposed in [1] which used only annotations for Bayesian crowd aggreation.
ThreshPostProcess/ThreshPostProcess.m:  the post processing MATLAB code of getting the top-K prediction results where K is the number of postive examples.

data_sample/:  one dataset sample used in [1], corresponds to the dataset1 l=1

To get results of the two models, run BayesDGC.py in vs code, then run  ThreshPostProcess.m in matlab







 



