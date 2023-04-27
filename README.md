# projetRO
Projet pour le cours de Recherche opérationnelle : Projet “Exploitation agricole”

Problématique : 

Une compagnie agricole envisage de s'installer dans une certaine région. La
détermination exacte de l'emplacement (localisation, taille, forme, etc.) doit
être réalisée afin d'optimiser trois objectifs et de respecter différentes contraintes.

Voici les trois différents objectifs:
- la productivité du terrain;
- la proximité de zones habitées (afin de faciliter la vente de la production) ;
- la compacité du terrain (afin de diminuer les coûts d'exploitation);

De plus, les différentes contraintes doivent être respectées:
- Le budget de la compagnie est de 500.000 euros;
- Les terrains achetés doivent être inoccupés (pas d'habitation ni de route).

Afin de permettre l'optimisation des objectifs et le respect des contraintes, la
région est décrite par différents documents détaillés dans la Section 1.1.

Description de la région :

La région étudiée est découpée en une grille de parcelles de tailles identiques.
Trois fichiers décrivent cette région:

1. "Usage-map.txt": ce fichier comprend une description des routes (in-
diquées par la lettre "R") et des zones habitées (indiquées par la lettre
2. "Cost_map.txt" :
ce fichier comprend pour chaque parcelle, un entier
représentant le prix en dizaines de milliers d'euros de la parcelle;
3. "Production-map.txt" : ce fichier comprend pour chaque parcelle, un entier
représentant un indice de productivité de la parcelle.

Il est demandé de : 

- Modéliser le problème
- Réprésenter virtuellement le problème
- Approcher une résolution du problème et la création d’une frontière
Pareto optimale
- La sélection et la représentation d'une solution de notre frontière.
- Une étude de la stabilité de notre approche par rapport aux différentes
hypothèses et paramètres du problème. 
