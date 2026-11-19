# Date de la dernière visite

Cette contrainte spécifie **combien de jours se sont écoulés depuis la dernière visite** avant de commencer la planification actuelle, afin de garantir le respect de l'écart minimum entre les visites.

**Format :** Entier négatif

**Remarque :** Si la fréquence de visite comporte plus d'une récurrence, cette contrainte est **non appliquée**.

**Exemple :**

* **Fréquence des visites :** 1/5
* **Espacement minimum entre les visites :** 2 jours
* **Date de la dernière visite :** -1

Dans ce cas, le client sera visité à partir du **jour 2**, car une visite le jour 1 violerait l'espacement minimum de 2 jours entre les visites.

**Dépend de :**

* Fréquence de visite
* Espacement minimum entre les visites
