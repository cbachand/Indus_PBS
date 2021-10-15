# honors-project
Assimilating Sentinel-1 snow depth measurements into NASA's GEOSldas model using a particle batch smoother to improve snow water equivalent estimates in High Mountain Asia.

Steps: 
1. Generate ensemble of model runs. These runs, as well as information on the model GEOSldas, can be found in the ensemble-runs folder. 
2. These model runs are used to generate a prior distribution for snow depth. Using a particle batch smoother (see PBS folder), we incorporate Sentinel-1 snow depth measurements into the model, and get updated predictions for key variables such as snow water equivalent. 
3. Validate PBS results with reanalysis data, compare to open loop runs. 
