# processed_data folder

The description of variables within each file is below. Dimensions of each array are in [ ]

"DRF.data": $\Delta z$ values of the depth array [$`50`$,]

"area_volume.h5": 

&emsp; &emsp; "Area": area of each grid cell in m$`^2`$ [$`180\times360\times50`$]

&emsp; &emsp; "Volume": volume of each grid cell in m$`^3`$ [$`180\times360\times50`$]

"basin_codes.h5":

&emsp; &emsp; "basin_code": basin code of each grid cell (1: Atlantic, 2: Pacific, 3: Indian, 4: Southern, 5: Arctic) [$`180\times360\times50`$]

&emsp; &emsp; "region_code": region code of each grid cell (0-44) [$`180\times360\times50`$]

&emsp; &emsp; "gamma": neutral density $\gamma$ of each grid cell in kg/m$`^3`$ [$`180\times360\times50`$]

"global_Cstar_timeseries.h5":

&emsp; &emsp; "Cstar_1992_2022": globally-integrated $C^*$ in Pg C [$`31`$,]

&emsp; &emsp; "dCstar_1992_2022": annual rate of change of globally-integrated $C^*$ in Pg C/year [$`30`$,]

&emsp; &emsp; "time": years 1992-2022 [$`31`$,]

"gamma.h5"

&emsp; &emsp; "gamma": neutral density $\gamma$ of each grid cell in kg/m$`^3`$ [$`180\times360\times50`$]

&emsp; &emsp; "latitude": latitudinal array [$`180`$,]

&emsp; &emsp; "longitude": longitudinal array [$`360`$,]

&emsp; &emsp; "depth": depth array [$`50`$,]

"regional_dCstar_timeseries.h5":

&emsp; &emsp; "dCstar_basins": annual rate of change of $C^*$ within each of the 45 ocean regions in mol/m$`^3`$/year [$'45\times30`$]

&emsp; &emsp; "time": years 1992-2022 [$`31`$,]

"vertical_dCstar.h5":

&emsp; &emsp; "dCstar_1993_2002": vertically-integrated rate of change of $C^*$ over 1993-2002 in mol/m$`^2`$/year [$`180\times360`$]

&emsp; &emsp; "dCstar_2003_2012": vertically-integrated rate of change of $C^*$ over 2003-2012 in mol/m$`^2`$/year [$`180\times360`$]

&emsp; &emsp; "dCstar_2013_2022": vertically-integrated rate of change of $C^*$ over 2013-2022 in mol/m$`^2`$/year [$`180\times360`$]

&emsp; &emsp; "dCstar_1993_2022": vertically-integrated rate of change of $C^*$ over 1993-2022 in mol/m$`^2`$/year [$`180\times360`$]

&emsp; &emsp; "latitude": latitudinal array [$`180`$,]

&emsp; &emsp; "longitude": longitudinal array [$`360`$,]

"zonal_dCstar_*.h5": same structure for each ocean basin (Atlantic, Pacific, Indian, Southern, Arctic)

&emsp; &emsp; "dCstar_1993_2002": zonally-averaged rate of change of $C^*$ over 1993-2002 in mol/m$`^2`$/year [$`180\times50`$]

&emsp; &emsp; "dCstar_2003_2012": zonally-averaged rate of change of $C^*$ over 2003-2012 in mol/m$`^2`$/year [$`180\times50`$]

&emsp; &emsp; "dCstar_2013_2022": zonally-averaged rate of change of $C^*$ over 2013-2022 in mol/m$`^2`$/year [$`180\times50`$]

&emsp; &emsp; "dCstar_1993_2022": zonally-averaged rate of change of $C^*$ over 1993-2022 in mol/m$`^2`$/year [$`180\times50`$]

&emsp; &emsp; "latitude": latitudinal array [$`180`$,]

&emsp; &emsp; "depth": depth array [$`50`$,]

