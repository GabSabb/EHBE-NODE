# EHBE-NODE
This repository constitutes complementary material for the paper "Neural Ordinary Differential Equations for Simulations of Residences Heated with Electric Baseboards" presented at eSim 2024.

The experiments were done using Python 3.9.13.
## Repository structure
* Residential_NODE.ipynb: Jupyter notebook that imports and treats the data, generates the model, trains it and visualises the results.
* house_data.csv: Includes the measured data of 9 thermostats of Hydro-Québec's Experimental House for Building Efficiency (EHBE) situated in Shawinigan, Quebec, Canada. It includes room temperature measurements and heating outputs of each electric baseboard associated with each thermostat. It also includes the global horizontal irradiation (GHI) and exterior drybulb temperature. Temperatures are measured in $°C$, heating energy in $Wh$ and GHI in $W/m^{-2}$.
