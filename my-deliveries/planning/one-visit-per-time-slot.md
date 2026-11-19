# Une visite par créneau horaire

Cette option active le **répétition d'une visite** pour chaque créneau horaire disponible.

**Format :** Binaire

* S'il est réglé sur **1**, la ressource **retourne au dépôt** entre les répétitions.
* S'il est réglé sur **0** (par défaut), la ressource ne **retourne pas au dépôt** entre les répétitions.

**Exemple :**

* Une visite comporte 3 créneaux horaires pendant la journée.
* Si cette contrainte est réglée sur `1`, la ressource effectuera la visite **trois fois**, revenant au dépôt **après chaque visite**.
