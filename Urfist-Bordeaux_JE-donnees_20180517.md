# Urfist Bordeaux -  "Des outils pratiques pour gérer et valoriser vos données de recherche"

Matériel lors de la journée sur Zenodo : https://zenodo.org/record/1256735#.W99aFyeNw_U

[TOC]

> Les « données de la recherche  »  sont  définies  comme  des enregistrements factuels  (chiffres,  textes,  images  et  sons),  qui  sont  utilisés  comme  sources  principales  pour  la  recherche  scientifique  et  sont  généralement  reconnus  par  la  communauté  scientifique  comme  nécessaires  pour  valider  des  résultats  de  recherche.  Un  ensemble de données de recherche constitue une représentation systématique et partielle du sujet faisant l’objet de la recherche.  
> Ce terme ne s’applique pas aux éléments suivants : carnets de laboratoire,
> analyses préliminaires et projets de documents scientifiques, programmes de
> travaux futurs, examens par les pairs, communications personnelles avec des
> collègues  et  objets  matériels  (par  exemple,  les  échantillons  de  laboratoire,  les  souches  bactériennes  et  les  animaux  de  laboratoire  tels  que  les  souris).  
> L’accès à tous ces produits ou résultats de la recherche est régi par d’autres
> considérations que celles abordées ici.  
> Définition OCDE

## Yves Ducq, VP amélioration continue et documentation
Politique sur la science ouverte à l’UBM
**Création d’une plateforme de revues en OA**, création d’une archive ouverte institutionnelle. Financement IDEX.
Exploitation des données à travers de la bibliométrie. Action au niveau de l’université sur l’ensemble du cycle de vie des données pour avoir une action pérenne qui booste la recherche

Données de la recherche : bonne gestion permet de **booster la recherche**. La réutilisation va dans le sens d’un partage, mais aussi d’une accélération de la recherche. Passe par la FAIRisation.

## Frédéric Boutoulle, VP recherche

Contexte :

* Loi pour une république numérique
* Appel d’Amsterdam 2016
    * Plan avec 11 mesures annoncées
    * Libre accès publications et données.
* Responsabilité des établissements
    * Mieux faire connaître les travaux
    * Enjeux économiques, heuristiques et éthiques
    * Eviter de dupliquer des études
    * Tirer le meilleur profit de la cumulativité de ces résultats
    * Ethique : on a accès, on peut s’assurer de la reproductivité.

Loi LRM amène à considérer ses données comme administratives, dont la propriété relève de l’établissement : politique du FAIR.

Comment mettre en avant ces données ?
Création d’une UMS : Grenoble, [GRICAD](https://gricad.univ-grenoble-alpes.fr/), Infrastructure de calcul intensif et données.

Spécialistes de la donnée dans les différents services : recherche, SCD, labos, etc.

Le quidam chercheur ne connaît pas forcément cat-opidor, isidore, etc. Levier de la **formation** est essentiel pour les chercheurs qui ne sont pas forcément sensibilisés.

Mieux sensibiliser les EC mais aussi les **doctorants**. Depuis l’arrêté de 2016, on met l’accent sur la formation. Dans cette formation, insister sur une sensibilisation à la donnée de la recherche. On ne va pas faire des chercheurs des data scientists, mais on les amène à se poser les bonnes questions.

Nourrir une politique de site.

## Atelier métadonnées
Martine Barale, CIRAD
https://docs.google.com/document/d/15UjyF-aPgKixJBSGcqEXC9RLqOJgsYsUd4YxB1cLf68/edit

### CIRAD
**Obligation de dépôt depuis 1986**, archive ouverte ensuite.
[Publications & ressources](https://www.cirad.fr/publications-ressources)
AO : [Agritrop](http://agritrop.cirad.fr/)
Ouverture de l’entrepôt de données **dataverse.cirad.fr en 2018**

*Les objets manipulés sont différents, mais pour les métadonnées, on retrouve quelque chose qu’on connaît bien.*

[CoopIST](https://coop-ist.cirad.fr/)

Open data, une partie de l’[open science](https://www.fosteropenscience.eu/foster-taxonomy/open-science)

### Données
Données de recherche ouvertes
- capitaliser (qualité)
- encourager la collaboration, éviter la dispersion des efforts (efficacité)
- accélérer l’innovation (transfert)
- impliquer les citoyens et la société (transparence)

Doranum : plateforme d’autoformation

Ouverture des données : as open as possible, as closed as necessary

Nature et granularité
- observation : capturées en temps réelle, uniques, impossibles à reproduire. Conservées de façon pérenne
- expérimentales
- …


Quelles données concernées ? Toutes
- brutes
- traitées
- analysées

### Définitions

#### Dataset
Ensemble *cohérent*, formaté pour être communicable, interprétables et adaptés à un traitement informatisé.

**La problématique des données est fortement liée aux disciplines.**
Gestion des données : appui précis à des unités nécessite de connaître un minimum les données manipulées.

#### Gestion des données
**Choix du grain** des jeux de données :
- par discipline, nature des données
- par site, pays, workpackage

Prendre en compte :
- valeur scientifique et potentiel de réutilisation
- devenir envisagé : publications/entrepôt

#### FAIR
Principes du **FAIR** ont l’air simples, mais les données ne répondent pas toujours à ces principes
- Findable : métadonnées, identifiants
- Accessible : protocole standard
- Interoperable : standards, vocabulaires
- Reusable : licences

#### Décrire ses données
- **métadonnées** : différents standards (génériques comme le Dublin Core ; disciplinaires, comme EML, DDI)
- avec la **documentation associée** : méthodes, protocoles, plan échantillonnage (fichier .txt lisez-moi)
- dictionnaires des variables, unités de mesure, abréviations
- équipement utilisé, méthode de calibration, contrôles
- schéma de la base de données, fichiers de synthèse

Enjeu : **documentation complète du dataset**, qui assure sa réutilisation.

### Métadonnées
Produire les métadonnées au moment de la collecte ou de la création des données. Puis complétées tout au long du cycle de la vie des données

Métadonnées : éléments structurels (titre, résumé) et valeurs descriptives (licence, droit), administratives (auteur, format, accès)

#### Objectifs
- faciliter la **découverte** : description + identifiant (DOI)
- facilite la **gestion et l’archivage**
- facilite la **gestion des droits** : propriété intellectuelle + droits d’accès et d’utilisation
- facilité la **réutilisation** : information sur le contenu, information sur la structure du jeu, sur la qualité
- …

#### Standard
- plus efficace en matière de recherche
- modèle pour ne pas oublier des informations, champs sont remplis correctement

#### Standard / norme
- standard : *recommandations* produites par un groupe représentatif d’utilisateurs, qui produisent la liste des métadonnées nécessaires
- norme : *approuvé* par un organisme reconnu

#### Comment choisir un standard ?
- en fonction du type de ressources
- du domaine scientifique
- de l’entrepôt : proposent souvent un standard générique (ou spécifique pour entrepôt disciplinaire)
- des exigences de l’éditeur

**Un même dataset peut avoir deux standards de métadonnées** : souvent un standard générique pour les infos de base, et un standard plus pointu pour les métadonnées de contenu, ou disciplinaires

Explorer les entrepôts par disciplines : obligations par financeurs, éditeurs, etc.

[re3data](https://www.re3data.org/)
[fairsharing](https://fairsharing.org/)

#### Dublin core
[Dublin core](https://fr.wikipedia.org/wiki/Dublin_Core)
Norme ISO 15836
Standard basique, non disciplinaire
**15 éléments de base**.
Même norme pour les AO.

Inclut des recommandations pour la saisie de contenu. Par exemple, les formats de dates, etc.

Les 15 éléments ne sont pas à remplir obligatoirement. Au CIRAD, 5 seulement. Si trop de contraintes, on génère du rejet et de la non-utilisation. Si pas assez, l’entrepôt devient inexploitable. Trouver le bon équilibre.

#### Standards disciplinaires
 - Géolocalisation : iso 19115, directive européenne INSPIRE (2007)
 - Ecological metadata language (EML) : écologie
 - Darwin core : biodiversté
 - **Data documentation initiative (DDI)** pour les SHS [DDI alliance](https://www.ddialliance.org/)

*Répertoires pour trouver un standard*
- DCC digital curation centre : standards par thématiques, listes très fines [Standards de métadonnées](http://www.dcc.ac.uk/resources/metadata-standards)
- FAIRsharing
- RDA metadata directory

#### Si pas de standard
 - Rechercher par entrepôt pour la discipline et voir quels sont les standards utilisés pour des jeux de données proches
 - Vérifier si des articles n’ont pas été publiés sur des standards en cours de définition par la communauté
 - Explorer les sites des sociétés savantes
 - Rechercher les data papers de la discipline

### Bien décrire son jeu de données
- titre significatif
- description
- fichiez readme
- mots-clés

Exemple : [Zenodo](https://zenodo.org/record/1218724#.Wv1J5MguAdU)
*Zenodo : seulement du Dublin core*

### Plusieurs dépôts ?
- Problème de la *multiplication des DOI*
- Au CIRAD, dépôt dans dataverse.cirad.fr, puis signalement dans un autre entrepôt, avec lien. Discussions en cours, pas encore de décision prise

### Pérennité des données
- entrepôts garantissent une dizaine d'années

### Demo dataverse
- **mots clés** : vocabulaires par disciplines. Ex : http://aims.fao.org/vest-registry/vocabularies/agrovoc-multilingual-agricultural-thesaurus
- métadonnées supplémentaires par types disciplinaires après première étape de dépôt

### Répertoire d’entrepôts
[re3data]https://www.re3data.org/
Par disciplines : https://www.re3data.org/search?query=&subjects%5B%5D=20514%20Hematology,%20Oncology,%20Transfusion%20Medicine

## Restitution ateliers

### Atelier rédaction DMP, Nathalie Reymonet et Magalie Moysan
Prise en compte du choix opt in/out dans l’évaluation : non
Temps nécessaire à la rédaction d’un DMP : travail d’équipe

### Atelier entrepôts, Frédérique Bordignon
Choix d’entrepôt : repérer ses pairs + habitudes communautés
Recommandations des éditeurs, financeurs, établissements

Fonctionnalités attendues
- Besoin de partage et sécurité (DOI)
- automatiser les liens entre publications et sets de données (github zenodo)
- géolocaliser
- mettre un embargo
- espaces de stockages tiers…

Entrepôts : utilisation de l’API de *ScholeXplorer* (repérage de datasets à partir de DOI)

Modèle économique de ces entrepôts : institutions et éditeurs

Pas d’entrepôt à l’école des Ponts : utilisent entre Mendeley data et Zenodo en général. Sauf si contraintes disciplinaires fortes, exemple de la [IIASA](http://www.iiasa.ac.at/)
Zenodo bien configuré pour accueillir du code dans Github
Données de paramétrage pas acceptées par tous les types d’entrepôts.

Readme : description
DMP : stratégie et outil d’anticipation
Data paper : article

Readme : voir [4TU] (https://www.4tu.nl/en/)
Autre exemple :  http://researchdata.4tu.nl/fileadmin/editor_upload/pdf/README/Guidelines_for_creating_a_README_file.pdf

Voir aussi université de Cornell

## INIST

### Trois axes de travail
- *accès aux publications* : archives, ISTEX. Stats sur usages
- *textes et TDM* : bibliométrie, terminologies
- *données* : offre de service sur la valorisation des données (aide à la gestion : OPIDOR) et valorisation des bases de données (plus proche de ce qu’on a vu pour Huma-Num).

Données : 10 personnes dans chaque équipe

### Services :
 - DORA Num
 - Portail OPIDOR
 - DataCite
Voir : http://www.inist.fr/?CoReA-439

Convergence de DMP tool et DMP online : DMP roadmap

**DMP Opidor** : plans seront visibles, possibilité de les copier
Administrateurs : stats d’usage (via interface ou API)
*Nouvelle version pour l’été*

DMP est un document un peu statique. Idée : générer des active DMP, machine actionnable.

Perspectives DMP opidor : connexion d’API en projets. Research data alliance. Aller vers un modèle commun et structuré de DMP.

**DataCite**
Inist opère pour le CNRS, agence d’attribution de DOI.
Pour un client, fourniture de préfixe de DOI.
Assistance à la création.
86 centres de données servis via l’INIST, 58000 DOI attribués

**PID opidor**
Permanent identifier : création en masse de DOI
Génération de métadonnées associées à un jeu de données

FAIR
Si pas de licence sur une donnée, on ne peut PAS les réutiliser
Projet INIST dans ce cadre : accompagnement et conseil, mise à disposition d’outils, mise à disposition d’un outil d’aide à la décision, service de curation. 2019

**Services** pour le dépôt : conseil au dépôt, accompagnement au dépôt, outil d’aide à la décision, *assistance à la création d’entrepôt*

**Cat Opidor** : cartographie des services dédiés aux données

Valorisation bases de données : COREA [http://ccj-corea.cnrs.fr/], HISCANT Lorraine, CREM MSH Ginouves, Archimede Unistra

**Méta-catalogue de jeux de données en projet (2020)** : interrogation sur métadonnées d’enrichissement, proposition de métriques d’impact et d’usage (indicateurs pour évaluation scientifique)

TDM à l’inscrit : analyse de corpus textuels.
Voir projet européen : http://openminted.eu/

Ressources terminologiques : loterre.fr

### Bibliométrie
Activité historique liée aux publications.
Vers des **datametrics** ? Un FI des jeux de données ?

Labos non UMR peuvent demander un accompagnement de l’INIST. Tarifs différents.
