# Pénalité par heure de retard

Cette contrainte représente un **coût supplémentaire appliqué par heure de retard**. Elle donne à l'utilisateur un contrôle plus précis sur la manière dont les fenêtres temporelles de visite sont respectées. **Remarque :** Les contraintes liées à la tolérance doivent être utilisées avec prudence, car elles peuvent dominer le processus d'optimisation en faisant des retards la priorité principale d'optimisation.

**Format :** Numérique (entier ou décimal)

**Exemple :**\
Si vous êtes prêt à accepter des détours et une distance supplémentaire pour mieux respecter les fenêtres de livraison — par exemple, parcourir un extra de **70 km** pour éviter d'être **en retard de 5 minutes**— la pénalité peut être calculée comme suit :

* Coût par km = **0.5**
* Distance supplémentaire = **70 km**
* Facteur de conversion = **12** (60 minutes / 5 minutes)

Pénalité par heure de retard = **0,5 × 70 × 12 = 420**

Par conséquent, la valeur à saisir pour la **Pénalité par heure de retard** contrainte est **420**.

**Dépend de :**

* Heure d'ouverture
* Heure de fermeture

**Incompatible avec :**

* Tolérance de retard
