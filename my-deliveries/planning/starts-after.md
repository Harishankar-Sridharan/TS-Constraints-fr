# Commence après

Cette contrainte vous permet de **enchaîner des visites**, en garantissant que deux visites sont effectuées le **même jour par le même conducteur**.

La visite à laquelle cette contrainte est appliquée sera programmée **après la visite à laquelle elle est liée**. Si une visite de la chaîne ne peut être programmée, **aucune des visites de la chaîne ne sera placée**.

Si utilisée, la valeur doit correspondre au **ID client** de la visite avec laquelle enchaîner.

**Format :** Entier (correspondant à l’ID client)

**Exemple :**

* La visite A a l’ID client 101
* La visite B a cette contrainte réglée sur 101

Dans ce cas, la visite B sera programmée **après la visite A le même jour par le même conducteur**.

**Dépend de :** ID client\
**Incompatible avec :** Fréquence de visite
