# Exiger que toutes les compétences soient compatibles

Lorsque le **Compatibilité avec les ressources** la contrainte est appliquée (surtout avec plusieurs valeurs), ce paramètre vous permet de préciser si **une seule** caractéristique de la liste suffit ou si **toutes** les caractéristiques énumérées sont requises.

**Format :** Binaire

* **0** – Une seule caractéristique de la liste est requise.
* **1** – Toutes les caractéristiques de la liste sont requises.

**Valeur par défaut :** 1

**Exemple :**\
Si une visite peut être effectuée par une ressource qui répond à **n'importe laquelle** des caractéristiques énumérées, définissez la valeur sur `0`.\
Si la visite nécessite qu'une ressource réponde à **toutes** caractéristiques de la liste, laissez la valeur sur `1`.
