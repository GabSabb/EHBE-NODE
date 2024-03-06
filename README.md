# EHBE-NODE
This repository constitutes complementary material for the paper "Neural Ordinary Differential Equations for Simulations of Residences Heated with Electric Baseboards" presented at eSim 2024.

The experiments were done using Python 3.9.13.

## Repository structure
* Residential_NODE.ipynb: Jupyter notebook that imports and treats the data, generates the model, trains it and visualises the results.
* house_data.csv: Includes the measured data of 9 thermostats of Hydro-Québec's Experimental House for Building Efficiency (EHBE) situated in Shawinigan, Quebec, Canada. It includes room temperature measurements and heating outputs of each electric baseboard associated with each thermostat. It also includes the global horizontal irradiation (GHI) and exterior drybulb temperature. Temperatures are measured in $°C$, heating energy in $Wh$ and GHI in $Wm^{-2}$. The original dataset can be found under the same name on [Zenodo](https://doi.org/10.5281/zenodo.10156745) or [GitHub](https://github.com/HarryVallianos/Automated-MultiZone-Model-Generation).
* requirements.txt: Text file listing the different Python libraries requiered to run the Jupyter notebook.

## Other publications the same data as this repository

1. Charalampos Vallianos, Matin Abtahi, Andreas Athienitis, Benoit Delcroix & Luis Rueda (2023) Online model-based predictive control with smart thermostats: application to an experimental house in Québec, Journal of Building Performance Simulation, https://doi.org/10.1080/19401493.2023.2243602
2. Charalampos Vallianos, Andreas Athienitis, Benoit Delcroix, Automatic generation of multi-zone RC models using smart thermostat data from homes, Energy and Buildings, Volume 277, 2022, 112571, ISSN 0378-7788, https://doi.org/10.1016/j.enbuild.2022.112571
3. Vallianos, C. et al. (2023). Automated RC Model Generation for MPC Applications to Energy Flexibility Studies in Quebec Houses. In: Wang, L.L., et al. Proceedings of the 5th International Conference on Building Energy and Environment. COBEE 2022. Environmental Science and Engineering. Springer, Singapore. https://doi.org/10.1007/978-981-19-9822-5_73
