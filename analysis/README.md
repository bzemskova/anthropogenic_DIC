# analysis folder

Jupyter notebooks for data post-processing

1. "basin_timeseries.ipynb": annual rate of change of $C^*$ ($\Delta C^*$) integrated over each of the 45 ocean regions

- output figures: "../figures/regions_timeseries.png"

- output data files: "../processed_data/regional_dCstar_timeseries.h5"

2. "separate_ocean_regions.ipynb": separate each grid cell into 45 ocean regions and calculate area/volume of each grid cell

- output figures: none

- output data files: "../processed_data/basin_codes.h5", "../processed_data/area_volume.h5"

3. "total_timeseries.ipynb": globally-integrated $C^*$

- output figures: "../figures/global_Cstar_timeseries.png"

- output data files: "../processed_data/global_Cstar_timeseries.h5"

4. "vertical_integration.ipynb": vertically-integrated rate of change of $C^*$

- output figures: "../figures/vert_int_deltaCstar.png", "../figures/vert_int_delta_deltaCstar.png"

- output data files: "../processed_data/vertical_dCstar.h5"

5. "zonal_integration.ipynb": zonally-averaged rate of change of $C^*$

- output figures: "../figures/zon_int_deltaCstar_decadal.png", "../figures/zon_int_deltaCstar.png"

- output data files: "../processed_data/zonal_dCstar_*.h5"



