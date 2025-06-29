This repository includes the latest work included in the thesis "Application of predictive modeling methods to model volatile release under entrained flow conditions"

The steps were explained in detail in the methodology part of the thesis (which can be found in the repository).

## CSV Files
- Compiled raw data used in preprocessing are the concatenated version of features.csv and labels.csv files. 
- labels.csv represents the mass loss (wt% wf)
- Rest of the changes and intermediate files generated depend on the preprocessing part (which could be the main focus for the further improvements)
- filtered_mad1 : Filtered out with MAD method z = 1
- mad1_Ea.csv : Filtered out with MAD method z = 1 and Arrhenius parameters added

## 2-step-modeling.py
- E_A and A_0 predictions were made by using LightGBM according to its outperforming outcomes obtained by the initial experiments done with different models.
  
