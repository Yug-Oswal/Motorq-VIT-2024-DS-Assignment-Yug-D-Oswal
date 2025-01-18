# MotorQ Data Science Assignment
This is a repository for a data science assignment conducted by the Startup MotorQ. 

## Information on the Assignment:
We are given multiple telemetry csvs, recording data of motor vehicles over a period of time. 
Dataset Description: The dataset consists of 3 tables- Telemetry 1, Telemetry 2, and Vehicle Data
- Telemetry 1: Each row contains multiple parameters for a particular vehicle at a particular timestamp
  - Vehicle ID- Unique identifier of a vehicle
  - Timestamp - Timestamp at which the parameters were recorded
  - Speed - Speed at the given timestamp in miles per hour
  - Odometer - Value of the odometer at the given timestamp in miles
  - FuelLevel - Percentage of fuel tank filled at the given timestamp
- Telemetry 2: Each row contains the value of a single parameter (denoted by name)
  - Vehicle ID- Unique identifier of a vehicle
  - Timestamp- Timestamp at which the specified parameter was recorded
  - Name-Nameof theparameter recorded
  - Value- Value of the parameter mentioned
- Vehicle Data: Each row maps a single vehicle to its fuel tank capacity and rated miles per gallon
  - Vehicle ID- Unique identifier of a vehicle
  - TankCapacity- Capacity of the fuel tank in Gallons
  - RatedMPG-Thevehicle’s rated Fuel Economy in Miles per Gallon
### Requirements:
