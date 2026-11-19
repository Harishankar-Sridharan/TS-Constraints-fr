# Retard maximal

Cette contrainte vous permet de définir le **délai maximum autorisé** au-delà de la fin de la fenêtre horaire d'une visite.

Le **Pénalité de retard** la contrainte doit être utilisée en même temps.

**Format :** HH:MM ou HH:MM:SS

**Dépend de :**

* Heure d'ouverture
* Heure de fermeture
* Pénalité par heure de retard

**Incompatible avec :**

* Tolérance de retard

**Exemple**

Si la fenêtre horaire de visite d'un client se termine à **17:00** et le **Retard maximal** est défini à **00:10**, il est permis à la ressource d'arriver jusqu'à **10 minutes de retard**, c'est-à-dire pas plus tard que **17:10**.

Toute arrivée au-delà de **17:10** ne sera pas acceptée, et les retards dans cette limite seront pénalisés selon la **Pénalité par heure de retard** .
