# Python-Ports-Distance-Calculator
A distance calculator that is able to return the distance between two ports based on the derived sea route.

Same as the R version. The python script directly uses the raster map (cost map) I transformed by using R. The script first transform the raster map into an array. By using the route_through_array function provided by scikit-image, the least cost route was able to be derived and stored as an array for further distance calculation.
