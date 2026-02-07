** Caesar Cipher Tool - C Implementation **

_ Description:
 ce projet est une implémentation en Langage C du célèbre Chiffre de César. 
Il s'agit d'un outil de cryptographie symétrique qui permet de chiffrer un 
message en décalant chaque lettre d'un certain nombre de positions dans l'alphabet.


_ Fonctionnalités:
Chiffrement Dynamique : Supporte n'importe quelle clé de décalage entière.
Gestion de la Casse : Préserve les majuscules et les minuscules.
Sécurité des données : Utilisation de fgets() pour éviter les vulnérabilités de type Buffer Overflow.
Support ASCII : Utilisation de l'arithmétique modulaire pour une rotation fluide de A à Z.


_ Détails Techniques
L'outil repose sur l'algorithme suivant :
       C = (P + K) mod(26)
       Où :
       C --> est le caractère chiffré.
       P --> est la position du caractère original.
       K --> est la clé (le décalage).

       
 _Compétences Démontrées 
   En réalisant ce projet, j'ai mis en pratique :
       1- La Logique de Programmation : Manipulation des boucles for et des conditions if/else.
       2- La Cybersécurité : Introduction aux concepts de base du chiffrement et de la protection des entrées utilisateur.
       3- La Gestion de la Mémoire : Travail avec les tableaux de caractères (char arrays) en C.
