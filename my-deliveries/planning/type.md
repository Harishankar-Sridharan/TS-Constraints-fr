# Type

Cette contrainte spécifie si une visite implique un **livraison/dépôt** ou un **retour/retrait**.

**Format :** Binaire

* **0** – L'itinéraire est en **mode de livraison**.
* **1** – L'itinéraire est en **mode de collecte**.
* **2** – L'itinéraire est en **mode de livraison**, ce qui doit être terminé **avant toute collecte** puisse avoir lieu.

**Dépend de :** Quantité

**Exemple :**\
Si une ressource doit d'abord livrer des articles avant de collecter des retours, définissez la valeur sur `2`.\
Si la visite implique uniquement une collecte, définissez la valeur sur `1`.
