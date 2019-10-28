# Budget Iris 

Version simplifiée du projet RainbowViz pour tester

Visualisation du projet de loi de finance 2019 et comparaison avec 2018

## Historique

### 5 dec 2018 
Version initiale

### 7 dec 2018
- Tooltips
- Tabs de navigation
  
### 14 dec 2018
- Refactorisation du code
- Navigation par boutons
- légende
- Icone
- chargement des données par fichier

## Notes

### Commentaire code 
La visualisation utilise les données de data_plf_2019.json
d3.hierarchy(data) organise en fonction de la hierarchie des noeuds
Le champs size du modèle devient value et détermine la taille des cercle.
Le champs "color" du modèle détermine la couleur, il s'agit en fait du pourcentage de différence 2018/2019 en utilisant les échelles colorGreens, et colorReds (-100% à + 800%)
1000% représente une création ( les données utilisées sont à vérifier)
Les fonctions zoom et zoomto servent à ajuster le focus

### Todo (général rainbowviz)

- améliorer visualisation
  - liste + piechart
- Année donnée: comparer les différents documents ( notamment projet de loi de finance et loi de réglement)
- comparer entre années
  - comparer les arborescences de mission, programmes actions...
  - comparer les affectations entre années
  - 
