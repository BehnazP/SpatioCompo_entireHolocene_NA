# SpatioCompo for entire Holocene North America
Reconstruction of pollen-based land-cover (REVEALS) for entire Holocene (0-11700 BP). The reconstructions are based on the mathematical models developed in https://doi.org/10.1016/j.spasta.2018.03.005 and https://doi.org/10.1029/2018EA000547. 

## Land-cover maps for entire Holocene (0-1170 BP) which are based on pollen observations for North America
### The usage of the land-cover maps is free, however attribution to the publication is required.

The netCDF file in Land-cover Maps folder
* Land_Cover_entireHolocene_NA.nc

The `.csv` files in Land-cover Maps folder
1. Land_Cover_50.csv
2. Land_Cover_225.csv
3. Land_Cover_550.csv
4. Land_Cover_1000.csv
5. Land_Cover_1500.csv
6. Land_Cover_2000.csv
7. Land_Cover_2500.csv
8. Land_Cover_3000.csv
9. Land_Cover_3500.csv
10. Land_Cover_4000.csv
11. Land_Cover_4500.csv
12. Land_Cover_5000.csv
13. Land_Cover_5500.csv
14. Land_Cover_6000.csv
15. Land_Cover_6500.csv
16. Land_Cover_7000.csv
17. Land_Cover_7500.csv
18. Land_Cover_8000.csv
19. Land_Cover_8500.csv
20. Land_Cover_9000.csv
21. Land_Cover_9500.csv
22. Land_Cover_10000.csv
23. Land_Cover_10500.csv
24. Land_Cover_11000.csv
25. Land_Cover_11500.csv

based on the results in Paper (soon to be submited)

The columns represent
* Lon: longitude
* Lat: latitude
Land Cover Changes (LCC)
* C_*: Coniferous forest
* B_*: Broadleaved forest
* U_*: Unforested/Open land

LonLatElev in the name indicates the covariates used in the model, that is, Longitude, Latitude, and Elevation.

The numbers in the file names indicate the midpoints, which correspond to the time windows:
| Midpoint | Time Window       |
|----------|-------------------|
| 50       | 1950-1850 CE      |
| 200      | 1850-1600 CE      |
| 500      | 1600-1250 CE      |
| 1000     | 1250-750 CE       |
| 1500     | 750-250 CE        |
| 2000     | 250 CE - 250 BCE  |
| 2500     | 250-750 BCE       |
| 3000     | 750-1250 BCE      |
| 3500     | 1250-1750 BCE     |
| 4000     | 1750-2250 BCE     |
| 4500     | 2250-2750 BCE     |
| 5000     | 2750-3250 BCE     |
| 5500     | 3250-3750 BCE     |
| 6000     | 3750-4250 BCE     |
| 6500     | 4250-4720 BCE     |
| 7000     | 4750-5250 BCE     |
| 7500     | 5250-5750 BCE     |
| 8000     | 5750-6250 BCE     |
| 8500     | 6250-6750 BCE     |
| 9000     | 6750-7250 BCE     |
| 9500     | 7250-7750 BCE     |
| 10000    | 7750-8250 BCE     |
| 10500    | 8250-8750 BCE     |
| 11000    | 8750-9250 BCE     |
| 11500    | 9250-9750 BCE     |


### Reference:
* Dawson, Andria, John W. Williams, Marie-José Gaillard, Simon J. Goring, Behnaz Pirzamanbein, Johan Lindstrom, R. Scott Anderson et al. "Holocene land cover change in North America: continental trends, regional drivers, and implications for vegetation-atmosphere feedbacks." Climate of the Past Discussions 2024 (2024): 1-52. (https://doi.org/10.5194/cp-2024-6)
* Pirzamanbein, Behnaz, Johan Lindström, Anneli Poska, and Marie-José Gaillard. "Modelling Spatial Compositional Data: Reconstructions of past land cover and uncertainties." Spatial statistics 24 (2018): 14-31. (https://doi.org/10.1016/j.spasta.2018.03.005)
* Pirzamanbein, Behnaz, Anneli Poska, and Johan Lindström. "Bayesian Reconstruction of Past Land Cover From Pollen Data: Model Robustness and Sensitivity to Auxiliary Variables." Earth and Space Science 7, no. 1 (2020): e2018EA00057. (https://doi.org/10.1029/2018EA000547)


### Licenses
#### Data
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Land-cover maps based on pollen observations for Europe</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Behnaz Pirzamanbein</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/BehnazP/SpatioCompo_entireHolocene" rel="dct:source">https://github.com/BehnazP/SpatioCompo_entireHolocene</a>.
