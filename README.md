#  Caesar Cipher Tool - C Implementation

##  Description
Ce projet est une implémentation en **Langage C** du célèbre **Chiffre de César**. Il s'agit d'un outil de cryptographie symétrique qui permet de chiffrer un message en décalant chaque lettre d'un certain nombre de positions dans l'alphabet.


##  Fonctionnalités
* **Chiffrement Dynamique :** Supporte n'importe quelle clé de décalage entière.
* **Gestion de la Casse :** Préserve les majuscules et les minuscules.
* **Sécurité des données :** Utilisation de `fgets()` pour éviter les vulnérabilités de type **Buffer Overflow**.
* **Support ASCII :** Utilisation de l'arithmétique modulaire pour une rotation fluide de A à Z.

##  Détails Techniques
L'outil repose sur l'algorithme suivant :
           C = (P + K) mod(26)

##  Compétences Démontrées
1. **Logique de Programmation :** Manipulation des boucles `for` et des conditions.
2. **Cybersécurité :** Introduction aux concepts de base du chiffrement.
3. **Gestion de la Mémoire :** Travail avec les tableaux de caractères en C. 
