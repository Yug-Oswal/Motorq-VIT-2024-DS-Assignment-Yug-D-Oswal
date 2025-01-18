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
1. Data Preprocessing
  a. Convert the Telemetry 1 and Telemetry 2 tables into one common format
  b. Combine the two tables into one Telemetry table
  c. Ensure that corresponding telemetry messages in both tables are combined into one message to avoid redundancy
  d. Explore this dataset and share at most 3 takeaways from this dataset.
2. Calculate Fuel Economy
  a. Using the telemetry data from the combined table, calculate the Fuel Economy for each vehicle
  b. Please refer to Fuel Economy for an introduction
  c. Discuss your findings and approach taken to calculate this metric with us for follow-ups

## Project:  
1. The file "Motorq-ProblemStatement.ipynb" contains the entire condensed code of my solution to the problem statement.
2. The entire project was done within the span of 5-8 hours.
3. The file contains how I usually handle any Data Science tasks:
  a. Basic EDA on the data procured
  b. Data Cleaning, Pre-processing, and Scaling (if required). Scaling data is done with care to ensure that the distribution of the original data is maintained.
  c. Advanced EDA
  d. Posing Hypotheses related to the Insights we need to collect
  e. Derivative Branches created for EDA to test hypotheses
  f. Recursively create derivative branches if new hypotheses encountered.
  g. Draw and compile conclusions from the first level of derivative branches.
  h. Repeat steps e. to g. for lower level of derivative branches.
  i. Condense conclusions from all level of derivative branches.
  j. Create a new file with only the EDA required for the drawn conclusions.
