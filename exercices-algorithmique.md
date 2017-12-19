# Compethance Exercices Algorithmique

##Intituler
**Donner les valeurs des varaibles A, B et C après exécution des instructions suivantes :**
VAR A, B, C : ENTIERS
A <- 7;
B <- 17;
A <- B;
B <- A+5;
C <- A+B;
C <- B-A;
FIN

**Résultat :**
A = 7
B = 17
A = 17
B = 17 + 5 = 22
C = A + B = 17 + 22 = 39
C = B - A = 22 - 17 = 5
=====================
**Donner les valeurs des varaibles A et  B après exécution des instructions suivantes :**
VAR A, B : ENTIERS
A <-6
B <-2
A <-B
B<-A
FIN

**Résultat :**
A = 6
B = 2
A = 2
B = A = 2
B = 2
=====================
**Ecrire un programme qui permet d'échanger les valeurs de 2 variables:**
VAR A, B ENTIERS
A <- 2
B <- 3
FIN

**Résultat :**
VAR temp ENTIER
A = 2
B = 3
temp = A = 2
temp = 2
A = B = 3
A = 3
B = temp = 2
B = 2

=====================
**Priorité des opérateurs**
A = 9 + 3*4
B = (9 + 3)*4*

**Résultat :**
A = 9 + 3*4 = 9 + 12 = 21
B =(9+3)*4 = 12*4 = 48

=====================
**Ecrire un algorithme qui permet d'effectuer la saisioe d'un nom, d'un prénom et d'afficher ensuite le nom complet**

**Résultat :**
VAR prenom, nom STR
prenom = LIRE("Ecrire Prenom :")
nom = LIRE("Ecrire nom :")
ECRIRE(nom + " " + prenom)

=====================
**Ecrire un algorithme qui demande un nombre entier à l'user, le test et affiche si il est supérieur à 12**

**Résultat :**
VAR n INT
n = LIRE("Entrer un entier :")
IF n > 12
    ECRIRE("Le nombre est " + n + ".")


=====================
**Le prix d'une clef USB dans un magasin spécialisé varie selon le volume acheté
* 5€ l'unité s'il en achète moins de 10
* 4€ l'unité s'il en achète entre 10 et 20
* 3€ l'unité s'il en achète plus de 20
**
**Résultat :**
var INT prixUnitaire, prixTotal, quantite

quantite = LIRE("Quelle quantité de clef USB voulez-vous acheter : ")

IF (quantite < 10)
    prixUnitaire := 5;
ELSE IF (10 <= quantite <= 20) // (10 <= quantite && quantite <= 20)
    prixUnitaire := 4;
ELSE IF (quantite > 20)
    prixUnitaire := 3;
ELSE
    AFFICHER("ERROR!")
prixTotal := prixUnitaire, * quantite

AFFICHER("Pour l'achat de " + quantite + " clef USB au prix unitaire de " + prixUnitaire + " le total à payer seras de " + prixTotal + " €.")

=====================
**Ecrire un algorithme qui demande à l'user un nombre compris enre 1 et 3 jusq'à ce que la réponse soit correcte**

**Résultat :**
VAR INT number 
VAR BOOL reason = True

while (reason)
    number = LIRE("Taper un entier entre 1 et 3") 
    IF number >= 1 && number <=3
        reason = False
        ECRIRE("réponse correcte")


=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**






=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**






=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**






=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**






=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**






=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**






=====================
**aaa**

**Résultat :**

=====================
**aaa**


**Résultat :**








