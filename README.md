# NFL Elite 2026 · Valorisation des 32 franchises

Application web autonome (un seul fichier `index.html`) et rapport interactif de 38 pages sur la valeur des franchises de la NFL en 2026.

Site : https://abdoulhamiddiallo.github.io/nfl-elite-2026/

## Ce que contient l'application

- **Accueil** : chiffres clés, podium consensus, top 10, carte des 32 franchises, trois baromètres comparés.
- **Rapport** : 38 pages au format 16/9 en huit chapitres et une annexe (Panorama, Classement, Économie, Finance, Transactions, Décennie, Stades et terrain, Comparaisons, Annexe), sommaire, vue d'ensemble, plein écran, navigation au clavier, export PDF.
- **Classement** : les 32 franchises selon quatre sources (consensus, Forbes, CNBC, Sportico) et treize mesures (valeur, revenus, résultat d'exploitation, EBITDA, croissance, multiple de revenus, marge, dette, multiplicateur 2015 à 2026, indice Elite), filtres par conférence et division.
- **Franchises** : 32 fiches détaillées avec logo et logotype officiels, vue satellite du stade (trois baromètres, finances 2025, trajectoire Forbes 2015 à 2026, propriété, stade, palmarès, saison 2025, lecture rédigée).
- **Économie** : revenus, rentabilité, corrélation valeur / revenus, multiples, dette, droits médias, cap salarial, comptes des Packers, origine des revenus de la ligue.
- **Finance** : valeur / EBITDA, structure du capital (fonds propres et dette), revenus nationaux et locaux, rendement annuel des propriétaires, projection 2030, valeur par siège, simulateur de rachat (prix d'une part, règles de la ligue, financement, retour sur résultat).
- **Transactions** : ventes de franchises de 1989 à 2026, parts minoritaires et capital-investissement depuis 2024, plus-value des propriétaires, règles de propriété.
- **Décennie** : dix ans de valorisations, multiplicateurs, carte de chaleur des rangs 2015 à 2026.
- **Stades** : galerie de vues satellites des 30 enceintes, capacités, régimes de propriété, projets de stades 2026 à 2031, calendrier international 2026, playoffs 2025 et palmarès.
- **Duel** : deux franchises face à face sur quatorze critères.
- **Données** : table complète triable, filtrable, export CSV.
- **Méthode** : périmètres des trois baromètres, construction du consensus et de l'indice Elite, sources et précautions.

## Sources

- Forbes, « The NFL's Most Valuable Teams 2026 » (9 septembre 2026) et éditions 2015 à 2025
- CNBC, « Official NFL Team Valuations 2026 » (9 septembre 2026)
- Sportico, « NFL Franchise Valuations 2026 » (12 août 2026)
- Images : logos et logotypes du projet nflverse, vues satellites et bilans à domicile du jeu de données Stadiums de greerreNFL ; les logos sont des marques de leurs propriétaires respectifs
- NFL Football Operations (cap salarial), Green Bay Packers Inc. (rapports financiers 2025 et 2026), NFL.com, Seahawks.com
- Front Office Sports, SportsPro, Sportcal, Fortune, Sports Media Watch, NPR, Pro Football Hall of Fame, Wikipédia

Les valeurs sont des estimations publiées par ces baromètres. Le consensus est la moyenne simple des trois. L'indice Elite est un score sur 100 propre à l'application : 40 % valeur consensus, 20 % revenus 2025, 15 % EBITDA, 10 % croissance sur un an, 15 % palmarès et saison 2025.

## Technique

- HTML, CSS et JavaScript sans dépendance, graphiques SVG générés dans le navigateur, logos, vues satellites et polices embarqués (WebP et WOFF2).
- Pages du rapport dimensionnées en unités de conteneur (cqw) pour rester lisibles du téléphone au plein écran.
- Thème sombre et thème clair, navigation par ancres (`#/rapport/12`, `#/franchises?equipe=DAL`).
- Aucune collecte de données, consultable hors ligne une fois chargée.

Édition arrêtée le 25 septembre 2026.
