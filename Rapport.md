
Séance 1
---------

Début d'écriture du code: les bases ainsi que les déplacements du véhicule ont été codés

Séance 2
---------

Modélisation du véhicule sur Inventor quelques petits problème ont été rencontré mais le model 3D incluant tout les cotes a pu être terminé

https://www.noelshack.com/2020-02-7-1578862744-ensemble3.jpg

Séance 3
------------

La véhicule a commencé à etre construit :
Les pièce de bois ont été coupé, les 3 roues et le moteur fixés.
Les moteurs ont été testé cependant ils ne fonctionnaient pas on a donc du refaire toutes les soudures des fils les reliants. Ils fonctionnent désormais.

Séance 4
-------------

Tout d'abord il a fallu racheter de la colle pour les moteurs qui s'étaient decollés. Après les avoir recollé, le montage électronique à été réalisé. Tous les branchements nécessairent au déplacement ont été fait cependant impossible de faire fonctionner la voiture. 
Premièrement impossible d'allumer et de transférer le code vers ma carte Arduino. J'ai d'abord pensé à un problème de câble puis après de nombreux essaie cela a fini par fonctionner. 
Ensuite une fois le code televerser les moteurs ne s'allument pas. Lorsque l'on branche la carte Arduino avec en entrée là batterie rien ne se passe. En revanche lorsque l'on utilise la carte Arduino pour alimenter sous 5V le pont H une Led s'allume et un son continue retenti. 
Il semblerai qu'il n'y ait pas assez de tension/courant car lorsque l'on essaie de faire tourner la roue. Cette dernière tourne mais très doucement. Je suppose donc que la puissance fourni par les piles n'est pas suffisante. D'après le schéma du cours le pont H relié aux roues doit être branché sur 12V or les 4 piles de 1.5V ne peuvent faire que du 6V max. Il faudra donc essayé en branchant de nouveau 4 autres piles branchés en série ou trouver d'autre pile plus puissante. 

https://image.noelshack.com/fichiers/2020/03/7/1579391680-p00118-234153.jpg
