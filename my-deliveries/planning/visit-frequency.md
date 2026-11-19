# Fréquence de visite

Cette contrainte spécifie combien de fois une visite doit avoir lieu dans un nombre défini de jours. TourSolver optimise la planification en répartissant les visites aussi équitablement que possible tout en tenant compte de toutes les autres contraintes applicables.\
Remarque : la contrainte de fréquence guide la planification mais ne garantit pas le respect parfait des intervalles définis. L'interface de TourSolver affiche un indicateur montrant le nombre de visites qui ne respectent pas la fréquence attendue.

**Format :** Caractère 1/5

Si cette contrainte est activée, le **Jours travaillés** doit également être défini pour les ressources.

***

**Exemples**

**Exemple 1 :**

* **Fréquence de visite = 3/5**\
  Le client doit être visité **3 fois en 5 jours**.\
  TourSolver vise à maintenir un **écart de 2 jours** entre chaque visite.

***

**Exemple 2 :**

* **Fréquence de visite = 3/5\***\
  Le client doit être visité **3 fois en 5 jours**.\
  TourSolver privilégie d'assigner les 3 visites au **même intervenant**.\
  Dans ce cas, le maintien d'un espacement égal entre les visites devient secondaire.

***

**Exemple 3 :**

* **Fréquence de visite = 1/5**\
  Le client doit être visité **une fois tous les 5 jours**.\
  Si **Jours travaillés = 1–5**, le client sera visité :
  * une fois entre **jours 1–5**
  * une fois entre **jours 6–10**
  * une fois entre **jours 11–15**\
    Pour garantir un écart minimum spécifique entre ces visites, vous pouvez utiliser le **Espacement minimum entre les visites** .
