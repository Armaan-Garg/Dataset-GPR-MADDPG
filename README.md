# Data for paper,"Deep Deterministic Policy Gradient based Multi-UAV Control for Moving Convoy Tracking"

OSRM tool is used to collect latitude-longitude coordinates for varied road-tracks over which the convoy movement is tracked. 

<img width="284" alt="Screenshot 2022-03-04 at 8 47 56 PM" src="https://user-images.githubusercontent.com/60781655/156789763-39b15dfa-3ea3-4470-bdff-79ff53dfd904.png">

Trajectory data folder contains the latitude and longitude coorindates for the multi-UAV system and the correspoding convoy vehicles they are tracking. It also contains the distance as calcluted from the UAV's position to the vehicle's position.
To apply euclidean distance to latitude-longitude coordinates it needs to be converted into Cartesian coordinates else Haversine formula can be used.


