## Contexte
passionné de micro-jardinage, je plante souvent des légumes à la maison récemment j'avais des tomates dans un bidon recyclé sous ma fenêtre et javais fait une remarque presque chaque jour à 12H les feuilles de la tomate se fanaient, j'ai voulu savoir l'origine de ce phénomène c'est ainsi que j'ai réalisé une datalogger (enregistreur de données) pour pouvoir étudier l'environnement. 

![pied de tomate](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/pied%20tomato%203.jpeg)

## La technique de collecte 

pour faire le collecte de données j'avais besoin de connaitre quelques valeurs, comme:

- la température de l'air,
-  humidité de l'air,
-  l'humidité du sol. 

je récupérais ces données via les capteurs appropiriés, envoyais ça à mon serveur  et affichais ça dans un graphe pour étudier le comportement de l'environnement de ma tomate.

## Les outils de collecte

Pour étudier l'environnement du pied de tomate j'ai décidé d'utiliser une carte électronique low cost le  __wemos d1 mini__ comme cerveau équipé d'un module wifi pour envoyer les données a mon serveur __nodered__ et 3 capteurs: __DHT11__, __soil moisture capacitive__, __soil moisture__, un module pour connecter les capteurs (soil moisture) le __CD74HC4067__, et un système énergétique autonome composé de batterie, régulateur de charge, et un élévateur de tension.

lien pour plus d'infos sur le matériel utilisé:
* [Wemos D1 mini](https://docs.wemos.cc/en/latest/d1/d1_mini.html)
* [CD74HC4067, 16 channel analog multiplexer](https://www.sparkfun.com/datasheets/IC/cd74hc4067.pdf)
* [Capacitive soil moisture](https://makersportal.com/blog/2020/5/26/capacitive-soil-moisture-calibration-with-arduino)
* [soil moisture](https://www.circuitstoday.com/arduino-soil-moisture-sensor)
* [dht11](https://www.adafruit.com/product/386) 
* [NodeRed](https://nodered.org/)

![electronic](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/ALl.jpg)
![nodered dashboard](https://github.com/Diallomm/Datalogger/blob/master/Agriculture/pied%20de%20tomate_tomato%20stalk/Images/nodered1.png)

Si vous avez besoin d'aide, contactez nous!
Email: diallo@bloctechno.com
