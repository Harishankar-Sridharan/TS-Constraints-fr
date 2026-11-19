# Heures d'ouverture/fermeture 1 à 10

### Heures d'ouverture/de fermeture

Ces contraintes vous permettent de préciser la fenêtre horaire pendant laquelle une visite peut avoir lieu.\
**Heure d'ouverture 1** indique l'heure la plus tôt à laquelle la visite peut commencer, et **Heure de fermeture 1** indique l'heure la plus tardive à laquelle elle peut débuter. Cette fenêtre horaire s'applique à tous les jours sauf si **Jours d'ouverture 1** est défini ; dans ce cas, la fenêtre horaire ne s'applique qu'aux jours spécifiés.

Si aucune fenêtre horaire n'est définie pour une visite, celle-ci peut être réalisée à n'importe quel moment pendant les jours d'ouverture autorisés et dans les heures de travail de la ressource. Vous pouvez configurer jusqu'à quatre fenêtres horaires différentes (chacune avec leurs jours associés) pour une seule visite.

**Format :** HH:MM:SS

**Exemple 1 :**\
Heure d'ouverture 1 = 07:30:00 et Heure de fermeture 1 = 11:30:00 créent une fenêtre de quatre heures pendant laquelle le client peut être visité.

**Exemple 2 :**\
Pour un client nécessitant une livraison entre 23:00 et 03:00, les heures doivent être décalées afin qu'elles se situent dans la même journée. Cela permet de déterminer correctement l'ordre des visites.\
Par exemple :\
Heure d'ouverture 1 = 19:00:00 et Heure de fermeture 1 = 23:00:00 définissent une fenêtre de quatre heures.\
Après optimisation, les heures de visite planifiées doivent être ramenées à la plage horaire d'origine.\
Si TourSolver planifie la visite à 21:00, la visite réelle aura lieu à 01:00 (= 23:00:00 + 2 heures).

Les fenêtres horaires qui s'étendent sur plusieurs jours ne sont pas prises en charge. Par exemple, une fenêtre de 23:00:00 à 03:00:00 ne peut pas être utilisée sans ajuster les heures.

Une visite ne peut pas commencer avant l'heure d'ouverture. Par défaut, une visite qui commence à l'intérieur de la fenêtre horaire peut se poursuivre au-delà de l'heure de fermeture. Si vous souhaitez que la visite se termine avant l'heure de fermeture, activez le **Terminer la visite avant l'heure de fermeture** option.

### Heures d'ouverture/de fermeture 2 à 10

**Heures d'ouverture et de fermeture 2**

Ces contraintes vous permettent de définir une deuxième fenêtre horaire qui s'applique aux jours de visite spécifiés dans **Jours de visite possibles 2**.\
**Heure d'ouverture 2** indique l'heure la plus tôt à laquelle une visite peut commencer, tandis que **Heure de fermeture 2** précise l'heure la plus tardive à laquelle elle peut débuter.

**Format :** HH:MM:SS

**Exemple 1 :**\
Un client est disponible pour une livraison pendant deux périodes distinctes :

* Matin : 09:00 à 12:00
* Après-midi : 14:00 à 17:00

**Pour configurer cela, définissez**:

* Heure d'ouverture 1 = 09:00:00
* Heure de fermeture 1 = 12:00:00
* Heure d'ouverture 2 = 14:00:00
* Heure de fermeture 2 = 17:00:00

**Exemple 2 :**\
Un client peut être visité le :

* Lundi de 07:00 à 17:00
* Mercredi de 09:00 à 18:00

**La configuration serait :**

* Heure d'ouverture 1 = 07:00:00
* Heure de fermeture 1 = 17:00:00
* Jours d'ouverture 1 = 1 (Lundi)
* Heure d'ouverture 2 = 09:00:00
* Heure de fermeture 2 = 18:00:00
* Jours d'ouverture 2 = 3 (Mercredi)

**Heures d'ouverture et de fermeture 3**

Ces contraintes vous permettent de définir une troisième fenêtre horaire qui s'applique aux jours de visite spécifiés dans **Jours de visite possibles 3**.\
**Heure d'ouverture 3** indique quand la visite peut commencer, et **Heure de fermeture 3** indique l'heure la plus tardive à laquelle la visite peut débuter.

**Format :** HH:MM:SS

**Heures d'ouverture et de fermeture 4**

Ces contraintes vous permettent de définir un second créneau qui s'appliquera aux jours de visite définis dans\
Jours de visite possibles 4. L'heure d'ouverture 4 correspond à l'heure à partir de laquelle la visite peut être effectuée.\
L'heure de fermeture 4 correspond à l'heure au-delà de laquelle la visite ne peut plus être effectuée.
