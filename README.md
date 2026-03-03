This repository contains analysis notebooks and sample data to support Hjort et al. 2026 
# Setup:
1.	Clone the repository or download the notebooks & data
2.	Ensure the following dependencies are installed
      - python=3.7.16
      - matplotlib=3.5.3
      - notebook=7.5.4
      - pandas=1.3.5
      - numpy=1.21.6
      - scikit-learn=1.0.2
      - scipy=1.7.3
      - statsmodels=0.13.5
3.	Launch JupyterNotebook 

# Data:
This repository contains two datasets
- **Sample_Choice_Data** contains the contingency degradation behavioral data from n=40 mice performing the Pavlovian reversal task (see Fig. 1) 
- **Sample_GLM_Data** contains neural data from mPFC and processed predictors from an example mouse during a reversal session (see Fig. 2).
- Additional data supporting the manuscript is available at https://doi.org/10.6084/m9.figshare.31431814

# Notebooks:
This repository contains two notebooks
-	**BehaviorModels** contains the meta-RPE model we developed alongside other canonical variable learning rate models (see Fig. 1 and methods). This notebook outputs the value curves from each model alongside unweighted (negLL) and weighted (BIC) fit metrics for a given animal
-	**GLM** contains the generalized linear modeling method we developed to assign p-values to individual predictors in neural encoding models (see Fig. 2 & Fig. ED2). This notebook outputs p-values for each predictor x cell. 
-	Both notebooks should run in 5 minutes or less on a standard computer. We tested this software on desktop computers running Windows 10 and 11.

