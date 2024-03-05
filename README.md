# Diagramme de classe

![Classes](uml/classes.png)

## Vrai ou faux

Etant donné le diagramme de domaine ci-dessus, les assertions suivantes sont-elles vraies ou fausses ? 
- Etudiant est une classe d’association : **FAUX**
- Un étudiant peut participer à autant de cours qu’il veut : **VRAI**
- Plusieurs professeurs peuvent enseigner la même discipline : **FAUX**
- Un professeur peut enseigner plusieurs disciplines : **VRAI**
- Un cours peut être enseigner à 2 étudiants : **FAUX**
- Un cours peut être enseigner à 20 étudiants : **VRAI**

## Question ouverte

Représentez la même association avec la notation UML « petit losange » 

- Quelles informations perd-on par rapport au diagramme ci-dessus ?

**Réponse** : En remplaçant la classe d'association Cours par une classe "normale" et en faisant une association ternaire entre les classes,
on perd alors la contrainte qu'un Cours ne peut exister indépendamment d'une association entre Professeur et Discipline.

*Il faudrait rajouter une contrainte d'intégrité afin de forcer cet aspect plus tard.*
