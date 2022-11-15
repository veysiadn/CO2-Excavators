## Excavator Activity Analysis 
----
<font size = 4 > This repository is containing data analysis of sensor node attached to an excavator for activity classification. </font>

----

### Data
<font size = 4 >  Data contains sensor data from 3 different sensors attached to the excavator. Sensors include;  </font> 

*  <a href="https://www.sparkfun.com/products/15335"> ICM-20948 </a> IMU for built-in logging of:
    * 3-axis Accelerometer
    * 3-axis Gyroscope
    * 3-axis Magnetometer
 
* <a href = "https://www.sparkfun.com/products/15005"> NEO-M9N GPS Module </a> is a 92-channel u-blox M9 engine GNSS receiver, with ~1.5 meter accuracy
* <a href =  "https://www.sparkfun.com/products/15440"> BME280 </a> atmospheric sensor breakout is an easy way to measure barometric pressure, humidity, and temperature readings.

* On-board RTC,  so that all data can be time stamped.

<font size = 4> All sensors are connected to the <a href="https://www.sparkfun.com/products/16832"> The SparkFun OpenLog Artemis </a>board, open source data logger,  via I<sup>2</sup>C</font> bus.

<font size=4>  Collected data is in the data folder. As an initial data collection setup, two sensor nodes are arranged. </font>
* A node with all sensors attached to the excavator
* A node without GPS sensor.

<font size=4> The sensor setup is depicted in the picture below.</font>
<!-- 
Add image of the sensor setup here.
-->

<img src=./data/img/sensor-setup.png>

There is also a video of the data collection process and link to the video will be added here.