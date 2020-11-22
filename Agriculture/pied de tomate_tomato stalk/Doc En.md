## Background
Passionate about micro-gardening, I often plant vegetables at home recently I had tomatoes in a recycled can under my window and I made a remark almost every day at 12 o'clock the leaves of the tomato were withering, I wanted to know the origin of this phenomenon so I made a datalogger (data logger) to be able to study the environment. 

![pied de tomate](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/pied%20tomato%203.jpeg)

## The collection technique 

to do the data collection I needed to know some values, like:

- air temperature,
- air humidity,
- soil moisture. 

I would retrieve this data via the appropriate sensors, send it to my server and display it in a graph to study the behaviour of my tomato's environment.

## Collection tools

To study the environment of the tomato plant I decided to use a low cost electronic board the __wemos d1 mini__ as a brain equipped with a wifi module to send the data to my __nodered__ server and 3 sensors: __DHT11__, __soil moisture capacitive__, __soil moisture__, a module to connect the sensors (soil moisture) the __CD74HC4067__, and an autonomous energy system composed of battery, charge regulator, and a voltage booster.


### The data 

The temperature is in Celcius °C
humidity is % %.
for the value of the soil moisture sensors they are included in 0 and 1024. 
- 0 totally dry, 
- 1024 100% humidity

link for more information on the material used:
* [Wemos D1 mini](https://docs.wemos.cc/en/latest/d1/d1_mini.html)
* [CD74HC4067, 16 channel analog multiplexer](https://www.sparkfun.com/datasheets/IC/cd74hc4067.pdf)
* [Capacitive soil moisture](https://makersportal.com/blog/2020/5/26/capacitive-soil-moisture-calibration-with-arduino)
* [soil moisture](https://www.circuitstoday.com/arduino-soil-moisture-sensor)
* [dht11](https://www.adafruit.com/product/386) 
* [NodeRed](https://nodered.org/)

## Conclusion 

After 3 months of collecting data and analysing the graph, I deduced that what was causing my tomato leaves to fade __ was the heat__. You can see it on the graph below, the temperature around 12 o'clock climbs to 34°c. The experiment stopped when I picked my tomatoes and the plant died because there was an invasion of white flies.

![electronic](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/datalogger_zoom.png)

![electronic](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/ALl.jpg)
![nodered dashboard](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/nodered1.png)

If you need help, please contact us!
Email: diallo@bloctechno.com
