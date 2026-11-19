# Durée d'une portion découpée d'une livraison

Cette contrainte spécifie le **durée minimale requise pour permettre qu'une visite soit fractionnée** en plusieurs parties. Une visite peut être répartie sur différents jours ou autour d'une pause déjeuner. Cette valeur est étroitement liée au **Durée de visite** .

**Format :**  HH:MM

**Exemple :**

* La visite A a un **Durée de visite** de 4 heures.
* La visite B a un **Durée de visite** de 30 minutes.
* Le **Durée d'une portion d'une visite fractionnée** est réglé à 01:00

Cela signifie que **seules les visites supérieures à 1 heure** peuvent être fractionnées :

* La visite A peut être divisée en plusieurs parties si nécessaire.
* La visite B ne peut pas être fractionnée, car elle est plus courte que la durée minimale d'une portion.

Le **durée minimale pour chaque portion fractionnée** est contrôlée par le **Durée seuil pour couper les visites** .

**Règle supplémentaire :** Une visite **ne peut pas être divisée en plus de 16 blocs**.

**Dépend de :**

* Durée de visite
* Durée seuil pour couper les visites
