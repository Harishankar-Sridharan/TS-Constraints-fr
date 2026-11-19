# Coût d'externalisation

Cette contrainte permet à l'utilisateur d'indiquer qu'une commande **peut être livrée par un service de coursier externe**. Le moteur d'optimisation décide alors s'il est plus efficace d'utiliser ce service externe ou d'inclure la commande dans une tournée de livraison standard. Notez que ces visites externalisées **n'apparaissent pas dans les tournées ni dans la planification**. Le **coût d'externalisation** est inclus dans le coût total de l'optimisation.

**Format :** Numérique (entier ou nombre réel)

**Exemple :**

* Client A : `1000`
* Client B : `100`

Ces valeurs représentent le coût d'utilisation d'un coursier externe pour chaque client.
