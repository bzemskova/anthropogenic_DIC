# raw_Cstar_data folder

- Each HDF5 file corresponds to the year specified in the file name

- Each HDF5 file contains the following variables:

&emsp; &emsp; &emsp; * "Cstar": $C^*(x,y,z)$ at each latitude, longitude, depth grid point  in mmol/m^3 (3D array: $180\times360\times50$)

&emsp; &emsp; &emsp; * "latitude": latitudinal coordinates (1D array: $180$ elements)

&emsp; &emsp; &emsp; * "longitudinal": longitudinal coordinates (1D array: $360$ elements)

&emsp; &emsp; &emsp; * "depth": depth coordinates (1D array: $50$ elements)
