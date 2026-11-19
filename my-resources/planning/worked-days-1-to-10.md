# Jours travaillés 1 à 10

Cette contrainte spécifie tous les **Jours travaillés** (jusqu'à 64 jours) auxquels s'appliquent les fenêtres temporelles définies par les **Temps de travail** contraintes.

\
**Format :** Valeurs de caractères.

Les jours travaillés peuvent être saisis individuellement (par exemple, _1,4_), comme des entiers (_1 à 64_), ou en utilisant des plages de dates (par exemple, _14/05/2016 => 17/07/2016_).

**Exemple 1 :**

* _Jours travaillés = 1,2,5_ (ou _14/05/2016, 15/05/2016, 18/05/2016_) signifie que la ressource peut effectuer des visites les jours 1, 2 et 5 de la période de planification (ou aux dates correspondantes) dans les fenêtres temporelles définies par les contraintes de temps de travail.
* _Jours travaillés = 1–5_ (ou _14/05/2016 => 18/05/2016_) signifie que la ressource peut effectuer des visites tous les jours 1 à 5 de la période de planification (ou à toutes les dates de la plage) dans les fenêtres de temps de travail définies.

**Exemple 2 :**\
Une ressource travaille :

* Lundis de 07:00 à 17:00
* Mercredis de 09:00 à 18:00\
  Configuration :
* _Temps de travail = 07:00–17:00_, _Jours travaillés = 1_
* _Temps de travail 2 = 09:00–18:00_, _Jours travaillés 2 = 3_

**Exemple 3 :**\
Une ressource travaille :

* Du lundi au vendredi de 07:00 à 17:00
* Samedi de 09:00 à 12:00\
  Configuration :
* _Temps de travail = 07:00–17:00_, _Jours travaillés = 1–5_
* _Temps de travail 2 = 09:00–12:00_, _Jours travaillés 2 = 6_
