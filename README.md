# PMGNN report 
This is a report on the project carried out by myself between 23.05.2022 and 29.07.2022, whose purpose was to develop a method, based on graph deep learning, of forecasting pollution measurements in cities across space and time. 

# Overview 
Please consult the "report overview.pptx" presentation.

# Walking through the notebooks 
The order in which the notebooks should be completed is not arbitrary, since some later notebooks depend on the results of the ones prior. Thus, the following order is recommended:
* Obtaining and processing numeric data
  1. DAPHNE preprocessing 
  2. CPCB
  3. weather scraping 
  4. weather processing and feature engineering 
  5. utils 
  6. feature engineering
  7. Dataset 
* Processing graph data 
  1. Interpolation 
  2. osmnx utils 
  3. windows of graphs 
  4. osmnx to PyG conversion 
  5. Pytorch Geometric to Pytorch Geometric Temporal conversion 
* Deep Learning models and predictions  
  1. LSTM weather and time to PM 2.5 
  2. weighted MSELoss with radius
  3. GNN on city graph 


The "plotting journeys" notebook can be completed at any time, since it a useful, but not necessary part of this project.
