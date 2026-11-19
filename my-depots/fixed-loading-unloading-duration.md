# Durée fixe de chargement/déchargement

Cette contrainte définit le **temps minimum** qu'une ressource doit passer au dépôt lorsqu'elle effectue une **opération de chargement ou de déchargement**.\
Ce temps de base peut être **complété** par la durée supplémentaire spécifiée dans la **contrainte Durée de chargement/déchargement par unité** .

En d'autres termes, le temps total passé au dépôt =\
**Temps minimum au dépôt + (Temps par unité × Nombre d'unités)**

***

**Exemple**

* **Temps de chargement minimum au dépôt :** 10 minutes
* **Durée de chargement par unité :** 2 minutes
* **Nombre d'unités à charger :** 5

**Calcul :**\
Temps total au dépôt = 10 minutes + (2 × 5)\
Temps total au dépôt = **20 minutes**

Dans ce cas, la ressource passera **20 minutes** au dépôt avant de partir pour la prochaine visite planifiée.
