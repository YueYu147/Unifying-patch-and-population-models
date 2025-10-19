# Unifying-patch-and-population-models
Matlab code in the paper "Reconciling contrasting predictions from patch- and population-based spatial models".


This ZIP file has three subfolders: "1_deterministic_simulation", "2_sde_simulation", and "3_demographic_simulation".


In the subfolder "1_deterministic_simulation", 6 files are list:


1. "single_det_LV_main": 
This file is the main MATLAB code for single-species deteminisitc Lotka-Volterra model, where perturbations were implemented as external catastrophic events. Figures 2a, b, d, e can be generated using this code.


2. "two_det_LV_main":
This file is the main MATLAB code for two-species deteminisitc Lotka-Volterra model, where perturbations were implemented as external catastrophic events. Figures 4 and S6 can be generated using this code.


3. "det_LV_ode":
This file is a defined function included in files "single_det_LV_main" and "two_det_LV_main".


4. "single_det_resource_main": 
This file is the main MATLAB code for single-species deteminisitc resource competition model, where perturbations were implemented as external catastrophic events. Figures 2c, f can be generated using this code.
 

5. "two_det_resource_main": 
This file is the main MATLAB code for two-species deteminisitc resource competition model, where perturbations were implemented as external catastrophic events. Figure S7 can be generated using this code.


6. "det_resource_ode": 
This file is a defined function included in files "single_det_resource_main" and "two_det_resource_main".


In the subfolder "2_sde_simulation", 6 files are list:


1. "single_sde_LV_main": 
This file is the main MATLAB code for single-species Lotka-Volterra model, where perturbations arise from environmental stochasticity. Figures 3 and S1 can be generated using this code.


2. "two_sde_LV_main": 
This file is the main MATLAB code for two-species Lotka-Volterra model, where perturbations arise from environmental stochasticity. Figures 5 and S8 can be generated using this code.


3. "LV_sde": 
This file is a defined function included in files "single_sde_LV_main" and "two_sde_LV_main".


4. "single_sde_resource_main": 
This file is the main MATLAB code for single-species resource cmpetition model, where perturbations arise from environmental stochasticity. Figure S2 can be generated using this code.


5. "two_sde_resource_main": 
This file is the main MATLAB code for two-species resource cmpetition model, where perturbations arise from environmental stochasticity. Figure S9 can be generated using this code.


6. "consumer_drift": 
This file is a defined function included in files "single_sde_resource_main" and "two_sde_resource_main".


In the subfolder "3_demographic_simulation", 6 files are list:


1. "single_dem_LV_main":
This file is the main MATLAB code for single-species Lotka-Volterra model, where perturbations arise from demographic stochasticity. Figures S3 and S4 can be generated using this code.


2. "two_dem_LV_main":
This file is the main MATLAB code for two-species Lotka-Volterra model, where perturbations arise from demographic stochasticity. Figures S10 and S11 can be generated using this code.


3. "dem_LV_dispersal":
This file is a defined function included in files "single_dem_LV_main" and "two_dem_LV_main".


4. "single_dem_resource_main":
This file is the main MATLAB code for single-species resource competition model, where perturbations arise from demographic stochasticity. Figures S5 can be generated using this code.


5. "two_dem_resource_main":
This file is the main MATLAB code for two-species resource competition model, where perturbations arise from demographic stochasticity. Figures S12 can be generated using this code.


6. "dem_resource_dispersal":
This file is a defined function included in files "single_dem_resource_main" and "two_dem_resource_main".

