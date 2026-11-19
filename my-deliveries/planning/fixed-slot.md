# Créneau fixe

Cette contrainte désigne un **visite prioritaire**, fixant le **ressource, le jour et l'heure** de la visite si spécifié.

**Format :** Binaire

* **0** – La visite est **non fixée**.
* **1** – La visite est **fixée** selon les conditions spécifiées.

**Valeur par défaut :** 1

**Dépend de :**

* Heure d'ouverture
* Durée de visite

**Exemple :**

* Une visite est programmée avec un indicateur de priorité réglé sur 1, une heure de début à 09:00 et une durée de 2 heures.
* Le système s'assure que la ressource assignée effectue cette visite **exactement à 09:00** pendant 2 heures, en respectant l'heure d'ouverture.
