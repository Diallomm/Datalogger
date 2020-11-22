## Background
We have laying hens at home and it turns out that the mother hen refuses to hatch 🤷, so when we didn't get the eggs quickly (to make omelettes) the other hens would break the eggs to eat them (horrible no 😅). That's when I decided to make an incubator and it worked after 21 days of incubation I had my first chicks, cool no? 😎


![photo des poussins]()

## The collection technique 

j'étais pas obligé de creer un datalogger pour la couveuse, mais bref comme j'avais un système qui pouvait se connecter au wifi j'ai décider de récuper les données et les garder. Donc j'ai comme données

- la température de l'air,
- l' humidité de l'air,
- état du chauffage (si c'est allumé ou éteint)
- alerte au quand ou il systéme surchauffe (on prévoit tout😅)

je récupérais ces données via les capteurs appropiriés, envoyais ça à mon serveur  et affichais ça dans un graphe , et stocker les données dans ma base de données mongo db


## Collection tools

To study the incubator's environment I decided to use a low cost electronic board the __Wemos D1 mini__ as a brain equipped with a wifi module to send data to my __nodered__ server, 2 sensors: __DHT11__, __Ds18b20__, __a relay 220v__, __a fan__, __a 50w lamp__.

### The DATA 

For the temperature we have 2 sensors a Dht11 and a Dallas Ds18b20 which is more accurate than the Dht11.
- The temperature is in Celsius °C
- humidity is % %.
- relay can only have 2 states, 1 to switch on and 0 to switch off.
- alert can also have only 2 states, 1 to turn on and 0 to turn off.

link for more information on the material used:
* [Wemos D1 mini](https://docs.wemos.cc/en/latest/d1/d1_mini.html)
* [Ds18b20](https://datasheets.maximintegrated.com/en/ds/DS18B20.pdf)
* [relais 220v](http://idehack.com/blog/utilisation-dun-module-relais-avec-larduino/)
* [dht11](https://www.adafruit.com/product/386) 
* [NodeRed](https://nodered.org/)


If you need help, please contact us!
Email: diallo@bloctechno.com
