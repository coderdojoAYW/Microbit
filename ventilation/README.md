## Ventilation d'un local humide.

Le matériel utilisé se trouve dans le [kit smart health d'Elecfreaks](https://www.elecfreaks.com/learn-en/microbitKit/smart_health_kit/index.html).

Il s'agit :

- D'un capteur de température et d'humidité de type DHT11 (sur P1).
- D'une LED multi-couleurs de type Néopixel destinée à donner une indication sommaire sur la température ambiante (sur P2).
- D'un moteur que l'on fixe sur un support et auquel on ajoute une hélice pour réaliser un ventilateur (sur P9).
- D'un afficheur OLED
- Du module d'extension sensor:bit.
- D'une carte Micro:bit v2.

Et des câbles nécessaires.

Le câblage est le suivant :

![ventilation](https://github.com/user-attachments/assets/53de4847-e9fd-4986-a851-86a0d6959cf6)

La fiche d'activité se trouve [ici](ventilation.pdf).

![att](https://github.com/user-attachments/assets/f8c3fab9-c195-47d2-bf74-e965b5d9ede0)
- Le capteur DHT11 met un certain temps pour fournir des valeurs correctes
- Il faut éloigner le plus possible le moteur de la carte Micro:bit sinon il perturbe de manière électromagnétique le Micro:bit provoquant son reset.
