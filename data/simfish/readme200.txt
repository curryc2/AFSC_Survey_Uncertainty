Author: Jason Conner
Phone: 206-526-4797
Email: jason.conner@noaa.gov

This folder contains the second set of Kotaro Ono fish density simulations. The result files are prefixed with region and species as well as the MCMC seed used to produce them. I am using sequential seeds as a sort of versioning system.

In this set of seed=200, I have updated to Kotaro's new code, which includes the presence/absence model. I have updated from the previous run (seed=100), to express lon/lat in meters, and density in kg/km^2. I have also included the Predict_data data in the packaged version of simfish (source file = simfish_2.0.200.tar.gz).

Also, Kotaro's code calculates density as kg/km*m, so to express simulated densities in kg/km^2 you will need to divide CPUE by 1000. Or to express in kg/ha, divide by 10. This is also on the fix list for future versions. The user will need to join the result data with Predict_data for spatial analysis

Folder Contents (18 files):
----------------------------
.RData files
	AI_Atka_seed200
	AI_NRockfish_seed200
	AI_Pollock_seed200
	AI_POP_seed200
	EBS_Arrowtooth_seed200
	EBS_Cod_seed200
	EBS_Pollock_seed200
	EBS_Yellowfin_seed200
	SLP_Arrowtooth_seed200
	SLP_POP_seed200
	SLP_Turbot_seed200
readme200.txt - this file
sumfish_1.2.2.tar.gz (simfish requires sumfish)
simfish_2.0.200.tar.gz