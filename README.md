# Budget Iris / RainbowViz

Version simplifiée du projet RainbowViz pour tester

Visualisation du projet de loi de finance 2019 et comparaison avec 2018

## TODO 

- [x] ajouter les tooltips
- [x] faciliter la navigation
- [ ] Afficher des informations plus completes ( AE, chiffres précis, arborescence, crédits consommés ...)
- [ ] Compléter les données de différences ( plus de ligne)
- [ ] 

## Notes

### Todo (général)

- améliorer visualisation
  - liste + piechart
- Année donnée: comparer les différents documents ( notamment projet de loi de finance et loi de réglement)
- comparer entre années
  - comparer les arborescences de mission, programmes actions...
  - comparer les affectations entre années
  - 
### Traitements

import pandas
plf2018 = pandas.read_csv('PLFup2018.csv')

=query(A:U;"select A,C,E,G,sum(T) where A like N and C like O and E like P and G like Q  group by A,C,E,G ")
=query(A:Y;"select A,C,E,G,I, L,Y where A like M and D like P and F like R and H like T and J like V")