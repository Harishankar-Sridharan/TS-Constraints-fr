# Temps travaillé 1 à 10

Le **Heure de début/fin 1 à 10** Les contraintes définissent jusqu'à quatre fenêtres horaires quotidiennes différentes pendant lesquelles une ressource est autorisée à commencer et terminer ses visites. Ces fenêtres horaires aident à contrôler quand une ressource peut effectuer des tâches au cours d'une journée de travail.

Chaque paire—**Heure de début** et **Heure de fin**—représente une période d'exploitation valide. Vous pouvez configurer jusqu'à quatre intervalles horaires distincts pour refléter des heures de travail variables, des équipes coupées ou des disponibilités particulières.

**Format :** HH:MM\
Vous pouvez définir entre une et quatre fenêtres horaires selon le nombre de périodes de travail que la ressource a dans une journée.



***

#### **Exemple 1 : fenêtre horaire unique**

La ressource travaille tous les jours de **08:00 à 17:00**.

* _Heure de début 1 = 08:00_
* _Heure de fin 1 = 17:00_

Cela signifie que la ressource peut effectuer des visites uniquement dans cette unique fenêtre horaire.

***

#### **Exemple 2 : équipe coupée**

**La ressource travaille en deux équipes**:

* Équipe du matin de **08:00 à 12:00**
* Équipe de l'après-midi de **14:00 à 18:00**

**Configuration**:

* _Heure de début 1 = 08:00_, _Heure de fin 1 = 12:00_
* _Heure de début 2 = 14:00_, _Heure de fin 2 = 18:00_

Le système ne programmera des visites que dans ces deux intervalles.

***

#### **Exemple 3 : trois périodes de travail distinctes**

**La ressource est disponible**:

* Tôt le matin de **06:00 à 08:00**
* À midi de **11:00 à 13:00**
* Le soir de **16:00 à 19:00**

**Configuration**:

* _Heure de début 1 = 06:00_, _Heure de fin 1 = 08:00_
* _Heure de début 2 = 11:00_, _Heure de fin 2 = 13:00_
* _Heure de début 3 = 16:00_, _Heure de fin 3 = 19:00_

Les visites ne seront planifiées que dans ces trois plages horaires.

***

#### **Exemple 4 : utilisation des quatre fenêtres horaires**

**La ressource a de courtes périodes de disponibilité variables tout au long de la journée :**

* **07:00–09:00**
* **10:00–12:00**
* **14:00–15:00**
* **17:00–19:00**

**Configuration**:

* _Heure de début 1 = 07:00_, _Heure de fin 1 = 09:00_
* _Heure de début 2 = 10:00_, _Heure de fin 2 = 12:00_
* _Heure de début 3 = 14:00_, _Heure de fin 3 = 15:00_
* _Heure de début 4 = 17:00_, _Heure de fin 4 = 19:00_

De la même manière, vous pouvez configurer les six autres plages horaires de travail.
