# JelenPhD
Kinga Jelen PhD
The dataset includes data from in vitro experiments on 11 cell lines: 
V79-379A, V79-753B, DLD1, SQ20B, CI-1, C3H10T1/2, SCC25, HCT116, H184B5 F5-1M/10 and HF19 (folder „data”). 

These data were taken from the survival curves available in the source articles and then 
a linear-quadratic model was fitted to them , 
from which the α and β parameters were obtained (04_Distributions_alpha_beta_q).
 
All operations on the experimental data, their reading,  
preparation(01_PreaparingData.ipynb) and analysis (02_Fitting_LQmodel.ipynb) 
were performed in Jupyter Notebooks.   
The experimental database has been cleared of outliers based on several conditions(03_Outliers.ipynb) 
and data was veryfied (03_Outliers_veryfication_by_q_distribution.ipynb).

A comparison of biological dose (05_SOBP.ipynb) was set up on a depth-dose and LET profile („data/sobp_10mln”) 
as being used in radiobiological in vivo mouse experiments (folder „mc_simulation”).
