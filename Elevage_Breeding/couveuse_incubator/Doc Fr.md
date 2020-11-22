## Contexte
Nous avons avons des poules pondeuse à la maison et il se trouve que la maman poule refuse de couver 🤷‍, donc quand on récuperait pas vite les oeufs (pour en faire des omelettes) les autres poules cassaient les oeufs pour les déguster (horrible non 😅). C'est la que j'ai décider de fabriquer une couveuse et ca marché aprés 21 jours de couveson j'ai eu mes premiers poussin, cool non ? 😎

![photo des poussins]()

## La technique de collecte 

j'étais pas obligé de creer un datalogger pour la couveuse, mais bref comme j'avais un système qui pouvait se connecter au wifi j'ai décider de récuper les données et les garder. Donc j'ai comme données

- la température de l'air,
- l' humidité de l'air,
- état du chauffage (si c'est allumé ou éteint)
- alerte au quand ou il systéme surchauffe (on prévoit tout😅)

je récupérais ces données via les capteurs appropiriés, envoyais ça à mon serveur  et affichais ça dans un graphe , et stocker les données dans ma base de données mongo db

## Les outils de collecte

Pour étudier l'environnement de la couveuse j'ai décidé d'utiliser une carte électronique low cost le  __Wemos D1 mini__ comme cerveau équipé d'un module wifi pour envoyer les données a mon serveur __nodered__ , 2 capteurs: __DHT11__, __Ds18b20__, __un relais 220v__, __un ventilateur__, __une lampe de 50w__

### Les données 

Pour la température on a 2 capteurs un Dht11 et un Dallas Ds18b20 qui est plus précise que le Dht11
- La température est en Celsius °C
- humidité est pourcent %
- relais peut avoir que 2 états, 1 pour allumer et 0 pour éteindre
- alerte aussi peut avoir que 2 états, 1 pour allumer et 0 pour éteindre

lien pour plus d'infos sur le matériel utilisé:
* [Wemos D1 mini](https://docs.wemos.cc/en/latest/d1/d1_mini.html)
* [Ds18b20](https://datasheets.maximintegrated.com/en/ds/DS18B20.pdf)
* [ relais 220v](http://idehack.com/blog/utilisation-dun-module-relais-avec-larduino/)
* [dht11](https://www.adafruit.com/product/386) 
* [NodeRed](https://nodered.org/)


Si vous avez besoin d'aide, contactez nous!
Email: diallo@bloctechno.com
