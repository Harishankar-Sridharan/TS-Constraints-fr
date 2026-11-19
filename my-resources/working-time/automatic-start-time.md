# Heure de début automatique

**Cette valeur détermine si l'heure de départ de la ressource doit être adaptée en fonction des heures d'ouverture de la première visite.**\
Lorsqu'elle est activée, elle aide à minimiser le temps d'attente inutile et améliore l'efficacité de l'itinéraire.

* Si **Désactivé**, la ressource commence à l'heure définie dans le **Temps de travail** contrainte, même si la première visite ouvre plus tard. Du temps d'attente peut survenir.
* Si **Activé**, l'heure de départ de la ressource est ajustée automatiquement en fonction de l'heure d'ouverture de la première visite pour réduire le temps d'attente.

La ressource ne peut jamais commencer plus tôt que son **Temps de travail**. Si l'heure de départ change, l'heure de fin se décale du même montant, sauf lorsque la **Contrainte de temps de travail quotidien** est également appliquée.

\
**Format :** Oui / Non

**Exemple**: Heure de départ automatique - Oui

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>
