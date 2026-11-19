# Durée minimale de la pause conduite

Cette contrainte définit la durée minimale qu'une pause de conduite doit avoir pour être comptée comme temps de repos pendant une session de conduite.

\
**Format**: HH:MM

**Remarque**:\
La durée de la pause de conduite n'est pas considérée comme du temps de travail par TourSolver. Par conséquent, la journée de travail totale est prolongée de la durée équivalente de la pause.

**Exemple**:\
Si une pause n'est considérée comme repos que si elle dure au moins 15 minutes, alors _Durée minimale de la pause de conduite = 00:15_.

Scénario exemple (Durée maximale de conduite sans pause + Durée de la pause de conduite + Durée minimale de la pause de conduite)

* Durée maximale de conduite sans pause = 04:30
* Durée de la pause de conduite = 00:45
* Durée minimale de la pause de conduite = 00:15

Cela signifie que la ressource peut conduire pendant 4 heures et 30 minutes si elle prend au total 45 minutes de pause. Cette pause peut être répartie, par exemple, en trois pauses de 15 minutes, ou une pause de 30 minutes suivie d'une pause de 15 minutes.

Cependant, si la ressource a pris deux pauses de 20 minutes et une pause de 10 minutes, elle doit tout de même prendre une pause supplémentaire d'au moins 15 minutes pour atteindre les 45 minutes requises de repos qualifiant, car la pause de 10 minutes ne satisfait pas l'exigence minimale de 15 minutes et n'est donc pas comptée.
