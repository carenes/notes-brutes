# FAIRisation des entrepôts

Pascal Aventurier, IRD
Jean-Christophe Desconnets, IRD
Dimitri Szabo, INRA
Alexandre Mairot, Sciences Po
Jessie Galasso-Carbonnel, IRD


Cet atelier fait suite à celui sur dataverse à RDA France.

## Comment les entrepôts participent aux principes FAIR ?

Augmenter la découverte et réutilisation des données
Décrire les jeux de données avec une granularité suffisante et avec des pratiques normalisées pour données et métadonnées
Décrire les conditions de réutilisation et la provenance
Exploiter les données dans différents contexte
Définir des critères de qualité pour la gestion

Principes FAIR
Les entrepôts peuvent assurer certains niveaux d'accessibilité, mais peut-être pas tous

Rapport Turning FAIR into reality, 27 recommandations
Voir schéma p. 17 https://ec.europa.eu/info/sites/info/files/turning_fair_into_reality_1.pdf

FAIR et l'évaluation des entrepôts
- disciplines
- aires géo
Alignement international : EOSC, etc

Entrepôts peuvent assurer certains des principes, mais pas tous :
- non : F2, I2 et 3, R1 à 3

Certains entrepôts communiquent sur FAIR : exemple d'UNIPROT
F : url stable et métadonnées riches

Groupe RDA : FAIR data maturity model 
Voir le degré d'implémentation des principes FAIR

FAIR self-assessment tool 
https://www.ands-nectar-rds.org.au/fair-tool

Constellation FAIR touffue, est-ce que c'est trop ?
Voir : http://blogs.nature.com/scientificdata/2019/10/22/the-layered-cake/

Principes FAIR tout au long du cycle de vie de la donnée 

GBIF : http://www.gbif.fr/
Accessibilité libre et ouverte des données depuis 20 ans
Réponse à 90% sur les critères, difficultés sur le I et le R
Interopérabilité pose problème avec les autres types de données environnementales, génétiques, etc.
DOI sur les jeux de données, sur tous les téléchargements de données et sur les citations associées. Licences en place
Validation en cours avec Core Trust Seal

Didoména, EHESS
Solution interuniversitaire 
Impératifs contradictoires du FAIR : interopérabilité : base avec du dublin core est ok pour du web sémantique et RDF, mais ce qui est spécifique aux disciplines ne va plus pouvoir s'exprimer. 
Ethno-musicologues veulent un champ précis pour leur classification, médiévistes un autre, etc.

JC Desconnets : on peut aller au-delà du Dublin Core. Possible d'enrichir avec un autre standard. DC est chapeau. 

## Dataverse INRA

Slides : https://github.com/DS-INRA/JNSO-2019-Atelier-FAIR-Entrepots 
- Réflexion débute avec la directive PSI 2013
- Sept 2016 : charte
- Entrepôt
Outil dataverse, Harvard, open source, utilisé par le CIRAD, etc. 
Portail avec un ensemble de services : API, exports, rédaction de data papers, API
FAIR : 
- F+ : DOI, métadonnées poru l'identifiant, cherchable
- F- : métadonnées riches utilisant des vocabulaires
- A+ : données accessibles via DOI, via http, métadonnées toujours disponibles
- A- : données sous conditions et données déposées partiellement (manque une partie des fichiers, du code, etc)
- I+ : métadonnées standardisées et machine readable
- I- : format de fichiers ouverts et machine readable, vocabulaires avec URI (manques de l'outil et méconnaissance des personnes qui déposent qui ne connaissent pas les ontologies)
- R+ : licences disponibles
- R- : provenance des données, standards correspondant à la communauté
Espérances :)
- de FAIR à FAIR+ : ajout d'étapes supplémentaires comme la reproductibilité
- formats de fichier et documentation doivent être mis en début de chaîne, à intégrer globalement
Axes d'amélioration : formation des utilisateurs, curation
Curation : 
- intégration des utilisateurs : thésaurus, etc
- fournir un meilleur accès au contenu : les dépôts faits en autonomie sont parfois limités ou restreints par crainte ou par méconnaissance (publier le code n'est pas naturel)
- RGPD vu comme un frein à l'ouverture : anonymisation existe
EOSC Pillar 6.3 : y travailler dès maintenant
- moissonnage par B2FIND
- interopérabilité avec connecteur EOSC ETDR
- interopérabilité avec containers
- intégrer à l'environnement virtuel de recherche EVR D4SCIENCE

EUDAT : 
- projet européen, aujourd'hui dans EOSC Hub
- offre de services multiples : BE2FIND (outil de découverte, moissonnage OAI-PMH), BE2SAFE (environnement de stockage distribué, données répliquées sur différentes instances), BE2DROP (dropbox européenne), BE2SHARE (fork de dataverse), ITDR (plateforme d'archivage pérenne européenne, deux noeuds, CINES et Pays-Bas), BE2NOTE (annotations sur les data)

Dataverse :
- besoin de métadonnées important pour une communauté : paramétrable
- workflow paramétrable aussi
- description de publication des données accessibles : chercheurs eux-mêmes sont déposants
- facilité de déploiement 
- masse critique en France pour pouvoir faire des développements 
- groupe dataverse Europe créé autour de plusieurs universités

Manque des éléments comparatifs disponibles en ligne pour comparer. D'autres solutions comme eprints ou dspace sont complètement ignorées. Travaux du CoSO à prévoir...

## Entrepôt NESSTAR au CDSP, Sciences Po

http://nesstar.sciences-po.fr/webview/ 
- CDSP : un des trois diffuseurs de PROGEDO
- NESSTAR : logiciel de publications et d'analyse des données
- Gestion d'enquêtes
- Publier données et métadonnées
- Outil de découverte et de communication autour des données
- A travers NESSTAR, visibilité des données, mais il faut les commander par une application tierce
- Choix techniques sont de 2005
- Standard : DDI
- Vocabulaires contrôlés : CESSDA 
- Jeux de données vont tous aller sur dataverse : identifiant, questionnement sur l'ouverture de certaines données (mais beaucoup de données personnelles)

## Interopérabilité et principes FAIR / IRD

...
