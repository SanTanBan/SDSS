# SDSS

This formulation is a better and smaller version of Mustafa et al. (2016) and is valid for Distance Minimization.

Unlike providing individual layers for each vehicle, we provide individual layer for each vehicle type which drastically reduces the number of variables required to be used.

Another improvement is the provision of including road compatibility w.r.t each vehicle type. This ensures than specific vehicle types can access some roads which are not accessibile by others.
This is incorporated in the Distance Matrix itself (which is different for each Vehicle Type) and is incorporated in the pre-processing.

A sample input excel sheet is provided which has 5 distance matrices for the five vehicle types.

The Distance matrices used to check the problem were generated in excel in the same format as may be manually obtained from QGIS.

The Worksheet "Calculating Random Distances" is used only for generating random road distances and should be ignored.
