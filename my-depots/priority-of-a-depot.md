# Priorité d'un dépôt

Cette contrainte vous permet de définir un Dépôt comme prioritaire par rapport aux autres sites.

* Si deux Dépôts sont proches l’un de l’autre, le système privilégiera le site ayant la valeur de priorité la plus élevée.
* Si les Dépôts sont éloignés, le système prendra toujours en compte la valeur de priorité, mais aussi la distance entre la ressource et les Dépôts.
* Un dépôt avec une valeur plus élevée est considéré comme ayant une priorité plus élevée.

**Format :** Nombre (entier)

**Exemple :**

* Le Dépôt A a une valeur de priorité de 8 et le Dépôt B a une valeur de priorité de 5.
* Si les deux Dépôts sont proches, le système visitera d’abord le Dépôt A.
* Si le Dépôt B est plus éloigné, le système peut toujours prioriser le Dépôt A en fonction de la distance de déplacement.

