# Jours d'ouverture 1 à 10

**Jours d'ouverture 1**

Cette contrainte énumère tous les jours de visite possibles (jusqu'à 64) pendant lesquels la fenêtre temporelle définie par **Heure d'ouverture 1** et **Heure de fermeture 1** s'applique.\
**Format :** numérique ou date.

Vous pouvez spécifier ces jours individuellement (par ex. : 1,4), sous forme de plage (par ex. : 1–4), en tant qu'entiers (1 à 64), ou en utilisant des formats de date (par ex. : 14/05/2016 ⇒ 17/07/2016).

**Exemple 1 :**\
**Jours d'ouverture 1 = 1,2,5** (ou **14/05/2016, 15/05/2016, 18/05/2016**)\
Cela signifie que la visite ne peut avoir lieu que les jours 1, 2 et 5 dans le calendrier (ou le 14/05/2016, le 15/05/2016 et le 18/05/2016) à l'intérieur de la fenêtre temporelle définie par **Heure d'ouverture 1** et **Heure de fermeture 1**.

**Exemple 2 :**\
**Jours d'ouverture 1 = 1–5** (ou **14/05/2016 ⇒ 18/05/2016**)\
Cela signifie que la visite peut avoir lieu n'importe quel jour de 1 à 5 (ou entre le 14/05/2016 et le 18/05/2016) dans la fenêtre temporelle définie par **Heure d'ouverture 1** et **Heure de fermeture 1**.

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

**Jours d'ouverture 2**

Cette contrainte définit l'ensemble des jours d'ouverture (jusqu'à 64) pendant lesquels la fenêtre temporelle spécifiée par **Heure d'ouverture 2** et **Heure de fermeture 2** s'applique.\
Ces jours peuvent être listés individuellement ou sous forme de plage, et suivent le même format utilisé dans **Jours d'ouverture 1**.

**Exemple 1 :**\
Le client peut recevoir une livraison le :

* **Lundi** entre **07:00 et 17:00**, et
* **Mercredi** entre **09:00 et 18:00**.

**Configuration**:

* Heure d'ouverture 1 = 07:00:00
* Heure de fermeture 1 = 17:00:00
* Jours d'ouverture 1 = 1
* Heure d'ouverture 2 = 09:00:00
* Heure de fermeture 2 = 18:00:00
* Jours d'ouverture 2 = 3

**Exemple 2 :**\
Le client peut recevoir une livraison :

* De **Du lundi au vendredi** entre **07:00 et 17:00**, et
* Le **Samedi** entre **09:00 et 12:00**.

**Configuration**:

* Heure d'ouverture 1 = 07:00:00
* Heure de fermeture 1 = 17:00:00
* Jours d'ouverture 1 = 1–5
* Heure d'ouverture 2 = 09:00:00
* Heure de fermeture 2 = 12:00:00
* Jours d'ouverture 2 = 6

**Jours d'ouverture 3**

Cette contrainte énumère tous les jours d'ouverture (jusqu'à 64) pour lesquels la fenêtre temporelle définie par **Heure d'ouverture 3** et **Heure de fermeture 3** s'applique. Ces jours peuvent être spécifiés individuellement ou sous forme de plage, en utilisant le même format que **Jours d'ouverture 1**.

**Jours d'ouverture 4**

Cette contrainte spécifie tous les jours d'ouverture (jusqu'à 64) auxquels la fenêtre temporelle définie par **Heure d'ouverture 4** et **Heure de fermeture 4** s'applique. Ces jours peuvent être saisis individuellement ou sous forme de plage, en respectant le même format que **Jours d'ouverture 1**.
