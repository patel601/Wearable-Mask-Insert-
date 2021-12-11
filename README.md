# Wearable-Mask-Insert-
The wearable mask insert is to incentivize mask wearing by providing useful feedback about user vitals (to monitor symptoms of COVID-19, including fever or decline in blood-oxygen saturation), tracking the time a user spends enjoying the outdoors, and tracking how often a user smiles under the mask. The mask consists of multiple hardware components that cooperatively enable consistent data collection and transmission. To transmit analog data and power various peripheral sensors, a pair of FireBeetle Boards with BLE4.1 technology were utilized. The analog data being transmitted was collected from a Force Sensitive Resistor, a Thermistor, a Photoresistor, a PPG Sensor, and Capacitive Touch Sensors (MPR121).

Our user interface has different modes, like dashboard mode (where you can look at basic vitals), mask helper mode (where you can see if the mask is worn correctly, emotion mode (to sense if you are smiling under the mask), outside mode (to detect whether you are outdoors), and tree-magotchi mode (to grow a tree for an incentive).

The hardware code was done using Arduino, and the user interface was done using Processing. 
