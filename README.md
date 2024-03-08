# Résolution Automatique de Validité d'Expressions Logiques

Ce projet implémente un programme en Python permettant la résolution automatique de la validité d'expressions logiques en utilisant la logique propositionnelle. Le code utilise la bibliothèque sympy pour simplifier les expressions en forme normale conjonctive (CNF) et applique la résolution par résolvants pour déterminer si une formule logique donnée est valide.

# Algorithme de résolution
Début
    Ecrire la négation de F ;
    Mettre F sous forme d'un ensemble de clauses ;
    Tant que la clause vide n'est pas rencontrée et qu'il 
    existe des paires réductibles faire
  Début
    Chercher des clauses résolvantes ;
    Ajouter ce résultat à la liste des clauses ;
    Fintantque ;
  Si on trouve la clause vide alors F est valide
    sinon F est invalide
  Finsi ;
Fin ;

# Instructions d'utilisation
   1- Cloner le Repository:
  https://github.com/elrhilassi/Algorithme-de-r-solution-.git

   2-Exécuter le Programme:
  cd Algorithme-de-r-solution |
  python equation.py.py

# Exemple d'Utilisation : 

  Expression Non Valide:
    exp = B & (A | C)

  Expression Valide:
  exp = ~((~P | ~Z | R) & (~R) & P & (~T | Z) & T)


  


