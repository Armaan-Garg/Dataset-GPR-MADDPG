# Data for paper,"Deep Deterministic Policy Gradient based Multi-UAV Control for Moving Convoy Tracking"

OSRM tool is used to collect latitude-longitude coordinates for varied road-tracks over which the convoy movement is tracked. 

<img width="284" alt="Screenshot 2022-03-04 at 8 47 56 PM" src="https://user-images.githubusercontent.com/60781655/156789763-39b15dfa-3ea3-4470-bdff-79ff53dfd904.png">

The trajectory-data folder contains the latitude and longitude coordinates for the multi-UAV system and the corresponding convoy vehicles they are tracking. It also contains the distance as calculated from the UAV's position to the vehicle's position.
Euclidean distance is approx. equal to Haversine distance (usually used for long distance calculation given the lat. and long.) when measured over small scale like within a city where the Earth's curvature can be considered negligible.


