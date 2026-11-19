# contrainte Durée de chargement/déchargement par unité

Cette contrainte spécifie le **temps nécessaire au dépôt pour charger ou décharger une unité de produit**. La valeur est multipliée par le **quantité de produit** à charger ou décharger, selon le type de trajet.

> **Remarque :** Ceci s'applique **seulement** au **Quantité 1** contrainte des visites et **ne pas** aux autres 23 quantités possibles.

**Format :** HH:MM

**Exemple :**

* **Durée fixe de chargement/déchargement :** 00:3:00
* **Durée de chargement/déchargement par unité :** 120 secondes (2 minutes par unité)
* **Quantité à charger :** 8 unités

Calcul :

* Temps pour les unités = 120 s × 8 = 960 s = 16 minutes
* Durée totale au dépôt = 30 min (fixe) + 16 min = **46 minutes**

**Dépend de :** Quantité (Livraisons)
