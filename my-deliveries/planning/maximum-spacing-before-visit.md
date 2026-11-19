# Espacement maximum avant visite

Cette contrainte définit le **écart de temps maximal autorisé** entre deux visites enchaînées.

**Format :** HH:MM

**Nom technique du champ :** `tsOrderBeforeMaxTimeSpacing`

**Dépend de :** Commence après

**Exemple :**

* La visite A et la visite B sont enchaînées.
* L'espacement maximal entre elles est défini sur `01:30:00`.

Dans ce cas, **La visite B doit commencer dans l'heure et demie qui suit la visite A**; sinon, la chaîne ne peut pas être planifiée.
