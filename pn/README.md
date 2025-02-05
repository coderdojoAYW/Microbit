## Passage à niveau.

Le matériel utilisé se compose :

- D'un feu pour passage à niveau avec une LED blanche et deux LEDs rouges.
- D'un servo pour l'ouverture et la fermeture de la barrière.
- D'un détecteur de présence d'un train (voie H0 isolée avec détection par court-circuit ou simulation e présence par un crash switch)
- D'un adaptateur ([par exemple une carte Octopus:bit de Elecfreaks](https://www.elecfreaks.com/learn-en/microbitKit/Tinker_Kit/octopus_bit.html)).
- D'une carte Micro:bit v2.

Et des câbles nécessaires

Le câblage est le suivant :

![feux pn](https://github.com/user-attachments/assets/59376264-998d-47a9-9091-e62ebb2cced5)

Ce projet a pour but de contrôler la fermeture et l'ouverture d'un train en essayant de respecter le fonctionnement des passages à niveau de la SNCB :

- En l'absence de train le feu blanc clignote et la barrière est levée.
- Lors de l'arrivée d'un train la séquence de fermeture est activée :
  - Feux rouges allumés en alternance, feu blanc éteint.
  - Sonnerie activée.
  - Au bout d'un certain délai, commande de la fermeture de la barrière.
  - Après fermeture de la barrière, arrêt de la sonnerie, les feux rouges continuent à être allumés en alternance.
- Après le passage du train la barrière se relvève et le feu repasse dans la phase blanc clignotant.

La fiche d'activité se trouve [ici](controle_pn.pdf).

Le code final du carrefour est également téléchargeable en extension .hex dans la liste de fichier en haut de page.

Ce projet peut être prétexte à de la conception 3D pour la réalisation du passage à niveau ([voir ici](/pieces3D)) et à la réalistion d'un environement pour l'y intégrer.
