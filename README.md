# BayWheel station location optimization


## Project description
The proejct herein starts with bike usage data from existing bike sharing docks, and completes with a new suggested distribution of bike sharing docks, optimized for bike demand and walkign distance. It follows in three parts:
 - Real bike sharing data is analyzed to quantify bike demand for existing bike docking stations. 
 - Bike demand above is  used to teach a K-neirest neBa ghbor (KNN) algorithm, to predict bike demand across the city at locatoins that do not currently have docking stations.
 - We then optimize station placements by minimizing the average walking distance to a nearest bike station, based on the demand predicted by the KNN algorithm. Optimization can be done for any n nubmer of stations across the city, and the output is the optimized location for n stations. 
 
 Below is an example optimiation result for 20 stations.
![Example optimized bike docking station distribution across SF](https://github.com/nivalle/BayWheelPredict/blob/master/Figures/ExampleBikeStationOptimization.png)

## Useful links 
- Data source: https://www.lyft.com/bikes/bay-wheels/system-data
- Evolutionary strategy: https://en.wikipedia.org/wiki/Evolution_strategy


