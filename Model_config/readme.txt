This folder contains configuration files for running lis. 

ldt.config preprocess inputs, which are used to run the spinup run 
lis.config.spinup spins up the model to create a restart file for the ensemble run 
ldt.config.ens sets up inputs for the ensemble run 
lis.config restarts the spinup model run and creates an ensemble 
model.output specifies the outputs I want
foring_atts specifies the acceptable range of forcing values with perturbations applied
pert_atts_final_double specifies the perturbation standard deviations and cross correlations 
forcing_variables specifies the forcing variables that the model needs to run 
