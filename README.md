# Detect_obstacles_in_roads
Detection of obstacles in the roads using accelerometer data
) PROBLEM DEFINITION
BMS wants to detect obstacles on the roads utilizing XYZ axis data from the accelerometer of the units installed in the moving vehicles. These detections will be used for the development of a digital twin platform where BMS is planning to monitor the state of bad potholes / speed bumps / etc.
and provide data solutions in road authorities and municipalities where they can prioritize the fixing of obstacles that are causing dangerous events or accidents in the roads

Potential objects to detect are listed below:

potholes
speed bumps
manholes
cracks in the roads
etc.
It is not expected that the candidate will manage to detect all of the above categories but should rather focus on one or two of them with a higher priority the potholes and speed bumps

ii) DATA UNDERSTANDING
The XYZ dataset contains 10hz measurements of the accelerometer of a single vehicle for one day movement activity in Bilbao, SP.

| Field | Type | Description | Unit precision | Example
------------------------------------------------------------------------------------------
| time | datetime | 10hz frequency timestamp | datetime | 2022-09-29T09:54:34.315+0000
| acc_x | float | x-axis acceleration value | milli-g | 10.4
| acc_y | float | y-axis acceleration value | milli-g | 9.3
| acc_z | float | z-axis acceleration value | milli-g | 9.3
| speed | float | The acceleration speed | km/h | 15.3
| road_speed_limit | integer | The road speed limit | km/h | 120
| heading | float | Geo position heading | degrees | 359
| latitude | float | Geo position latitude | degrees | 45.458943
| longitude | float | Geo position longitude | degrees | 2.228940
| vehicle_make | string | The vehicle brand | - | hyundai
| vehicle_model | string | The vehicle model | - | accent
| vehicle_type | string | The vehicle type | - | car
| road_type | string | The type of the road | - | local_road

iii) Expected results
The candidate should create a folder with his/her name inside the directory 'Results'
Add inside their folder the python file or notebook of the analysis
The presentation of the designed solution
Any other material they want to include
The candidates are expected to add an evaluation of their proposed solution with clearly defined metrics that they will choose
