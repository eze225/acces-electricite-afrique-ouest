# Accès à l'électricité en Afrique de l'Ouest (2000-2024)

**Question :** parmi 10 pays d'Afrique de l'Ouest, lesquels ont le plus
progressé dans l'accès à l'électricité depuis 2000 ?

## Données
- **Source :** Banque mondiale, World Development Indicators
- **Indicateur :** Access to electricity (% of population)
- **Pays :** Bénin, Burkina Faso, Côte d'Ivoire, Ghana, Guinée, Mali,
  Niger, Nigeria, Sénégal, Togo
- **Période :** 2000-2024

## Démarche
1. Chargement et sélection des colonnes utiles avec pandas
2. Filtrage des 10 pays
3. Vérification de la couverture : les données ne commencent pas la même
   année selon les pays (1990 pour le Nigeria, 1999 pour la Guinée).
   Pour comparer équitablement, l'analyse porte sur une période commune,
   2000-2024.
4. Réorganisation des données (années × pays) et visualisation
5. Calcul de la progression en points entre 2000 et 2024

## Principaux résultats
| Pays | 2000 | 2024 | Progression |
|---|---|---|---|
| Ghana | 43,7 % | 91,9 % | +48,2 pts |
| Sénégal | 37,7 % | 82,9 % | +45,2 pts |
| Togo | 17,0 % | 61,1 % | +44,1 pts |
| Mali | 9,6 % | 49,5 % | +39,9 pts |
| Guinée | 15,2 % | 53,8 % | +38,6 pts |
| Bénin | 21,5 % | 59,0 % | +37,5 pts |
| Burkina Faso | 9,1 % | 34,0 % | +24,9 pts |
| Côte d'Ivoire | 48,7 % | 72,9 % | +24,2 pts |
| Nigeria | 43,2 % | 62,5 % | +19,3 pts |
| Niger | 6,5 % | 21,3 % | +14,8 pts |

- Le **Ghana** a le plus progressé et atteint plus de 90 % en 2024.
- La **Côte d'Ivoire** avait le meilleur niveau des 10 pays en 2000,
  mais n'arrive qu'en 8e position pour la progression.
- Le **Niger** reste le pays le moins électrifié, avec environ 21 %.

## Pistes à explorer
Les données décrivent les évolutions, mais n'en donnent pas les causes.
Hypothèses à vérifier : la difficulté d'électrifier les zones rurales
une fois les villes raccordées, la croissance démographique, et l'effet
de la crise de 2002-2011 en Côte d'Ivoire.

## Outils
Python, pandas, matplotlib, JupyterLab

## Reproduire l'analyse
pip install -r requirements.txt
jupyter lab
Puis ouvrir `analyse_electricite.ipynb`.

## Auteur
Ezéchiel Kragba, étudiant en Master Big Data & IA, Abidjan
