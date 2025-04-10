<<<<<<< HEAD
# Single component usage
## Sensors
### Temperature

### Humidity

### Minerals/Nutrient Content

### pH Value

## Pump/Valve Control

## Display Presentation
=======
# Sensors

## Temperature

## Humidity

## Minerals/Nutrient Content

## pH Value

# Pump/Valve Control

# Display Presentation

>>>>>>> 43489ba92a7b7cd6a894a4dca9f93a45a9e050f3
- **Sensor Values**
  - Temperature
  - Humidity
  - Nutrient Content
  - pH Value

- **Time**
  - Date
  - Time
  - Time until Harvest
  - Time since Planting
  - Weather outside

- **Culture**
  - Current Crop
  - Experiment Number

<<<<<<< HEAD
- **Other Information**

## Light Controll
- special grow lights


## Temperature regulation (fan/heater)
- old PC fan for cooling and fresh air
- old heating bars from toaster (needs testing and regular checking becouse of high fire risk)

# Programm 
## Main schedule
- turns off entire system during "night"/ inactive times to save power
- system powers of before power shutoff to avoid data loss (raspberry pi can power down on its own but it doesnt have a way to power up again unless power was complettly cut)
- scheduled using standart power time dial
## Redouts
- taking reads from the sensors in intervalls
- (in different, non overlapping schedules to avoid data conflict and make processing easyer)
- during heater/ fan usage, temp is monitored completly until target temperature is reached or time limit hit
## Emergency shutdown
- if ceirtain values are reached (eg. extremly high temperature) or system failure detected
- cuts heater/fan/pump/valve/lights from power supply
- logs failure, trys to send logs, then powers of the computing unit aswell
## Data logging
- automaticly uploaded to some cloud storage and also saved locally (not sure what to use for cloud)
- automaticly sends log/debug messages using discord bot (will propably not be done in the first version)
- data saved in .csv or .txt files for easy evaluation (.json might also be could but i never worked with that)
**File A (normall logging)**
Struture:
day:month:year,houre:minute:second,system running, error since last log, temperature, humidity, pH, EC
Example:
14:02:2025,16:42:00,true, false, 25°C, 0.4, 7.0, 120
Data types:
(calendar data, 24h format, bool, bool, in °C, idk, range 0-14, idk)
**File B (current cycle data)**
Structure:
started on, expected end, cycle number, system change to last cycle, last harvest successfull, currently planted
Example:
25:12:2025, 25:01:2025, 4, false, true, "lettuceX4,spinachX2,raspberryX2"
Data types:
(calender data, calender data, int, bool, string with X_number for counting crop and , as seperator)
**File C (moving part log)**
Structure:
part, running?, error encountered?, running since for xmin, estimated run time, reason for running
(for fan, heater, pump, valve)
Example:
"fan", true, false, 5, 10, "overheating sys"
Data type:
(string, bool, bool, int, int, string)


=======
- **Other Information**
>>>>>>> 43489ba92a7b7cd6a894a4dca9f93a45a9e050f3
