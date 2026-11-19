# Pause déjeuner

Ces contraintes sont utilisées pour définir la pause déjeuner de la ressource.

**Format :** HH:MM

**Début :** Spécifie l'heure la plus tôt à laquelle la ressource peut commencer sa pause déjeuner.

**Fin :** Spécifie l'heure la plus tardive à laquelle la pause déjeuner doit être terminée. Lorsque cette contrainte est utilisée, la pause déjeuner définie par le _Durée_ doit se dérouler entièrement à l'intérieur de la fenêtre temporelle Début–Fin.

**Durée :** Indique la durée de la pause déjeuner. Cette durée est considérée comme du temps de pause, non du temps de travail, et est donc déduite du total des heures de travail définies pour la journée.

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

Exemple 2 :

Une ressource avec :\
**Heure de début** = 09:00;\
**Heure de fin** = 18:00;\
**Heure de déjeuner** = 01:00;\
sera capable de travailler (et d'effectuer des visites) pendant une période de 8 heures (= 18 – 9 – 1).
