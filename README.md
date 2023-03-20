## Smoke Detector using Regression Models

A smoke detector is a gadget that detects smoke and sounds an alarm to warn others. They are mainly found in offices, homes, and factories. Smoke detectors are classified into two types:


- Photoelectric Smoke Detector - This sort of detector has an infrared, ultraviolet, and visible light source, as well as a sensor. It measures light intensity and triggers an alert if it falls below a certain threshold value, because light intensity diminishes in the presence of dust particles, smoke, and so on.


- Ionization Smoke Detector - This sort of detector has an electronic circuit that monitors the current difference and sounds an alert if it is discovered to be greater than a certain threshold. Because the ions will be unable to travel freely owing to smoke and duct particles, the current in the circuit will drop.


The goal is to create an AI model utilising the provided dataset, that will correctly trigger an alert if smoke is detected. The accuracy of ten (10) regression models will be evaluated and they will be depicted in graphs before selecting the best of them.


### Feature Description
- UTC - The time when experiment was performed.
- Temperature - Temperature of Surroundings. Measured in Celsius
- Humidity - The air humidity during the experiment.
- TVOC - Total Volatile Organic Compounds. Measured in ppb (parts per billion)
- eCo2 - CO2 equivalent concentration. Measured in ppm (parts per million)
- Raw H2 - The amount of Raw Hydrogen present in the surroundings.
- Raw Ethanol - The amount of Raw Ethanol present in the surroundings.
- Pressure - Air pressure. Measured in hPa
- PM1.0 - Paticulate matter of diameter less than 1.0 micrometer .
- PM2.5 - Paticulate matter of diameter less than 2.5 micrometer.
- NC0.5 - Concentration of particulate matter of diameter less than 0.5 micrometers.
- NC1.0 - Concentration of particulate matter of diameter less than 1.0 micrometers.
- NC2.5 - Concentration of particulate matter of diameter less than 2.5 micrometers.
- CNT - Simple Count.
- Fire Alarm - (Reality) If fire was present then value is 1 else it is 0.
