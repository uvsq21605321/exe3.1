# exe3.1

# Q1:Cette classe respecte-t-elle SRP?Pourquoi?
Non, car la classe Employe posséde deux responsabilites: calculeSalaire() et afficherCoordonnees().
# Q2:Que se passe-t-il si la méthode de calcul du salaire change?
si la méthode du salaire change le service de l'affichage sera aussi impacter et les coordonees seront changer

# Q3:Que se passe-t-il si l'affichage est remplacé par le stockage dans un fichier CSV?
si l'affichage est remplacé par le stockage y aura aucun changement et la SRP reste toujours inrespectable

# Q4: Proposition:
créer des sous classes une pour l'affichage et l'autre pour le calcul de salaire.
