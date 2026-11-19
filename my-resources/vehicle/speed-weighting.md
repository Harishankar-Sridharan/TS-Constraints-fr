# Pondération de la vitesse

Si les temps de parcours observés sont généralement trop bas ou trop élevés, l'utilisateur peut les ajuster en spécifiant, pour chaque ressource, si elle circule plus vite ou plus lentement que la vitesse définie dans les statistiques routières. Cela permet à l'utilisateur d'adapter les données de trafic aux contraintes spécifiques de chaque ressource tout en conservant les variations de vitesse en fonction de l'heure de la journée et du sens de circulation.

Le **Normal** la valeur est la valeur par défaut et sert de vitesse de référence définie dans le profil du véhicule et/ou fournie par Here maps (statistiques routières).

**Format :** Nombre

**Exemple :**\
Les statistiques routières indiquent une vitesse de **50 km/h** sur l'Avenue Aristide Briand à Bagneux.

* Si l'utilisateur considère cette vitesse trop élevée, il attribue un **Coefficient de vitesse de 1,2 (plus lent)**. La ressource circule alors **20 % plus lentement**, à **40 km/h** au lieu de 50 km/h.
* Si l'utilisateur considère cette vitesse trop basse, il attribue un **Coefficient de vitesse de 1,2 (plus rapide)**. La ressource circule alors **20 % plus rapidement**, à **60 km/h** au lieu de 50 km/h.
