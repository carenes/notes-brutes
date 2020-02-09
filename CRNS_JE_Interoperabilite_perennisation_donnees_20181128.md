# Interopérabilité et pérennisation des données 

[TOC]

## Ouverture de la journée par le groupe de travail inter-réseaux "Atelier Données"

## Introduction par Catherine Clerc (responsable de la Plateforme des Réseaux – Mission pour les Initiatives transverses et interdisciplinaires (MITI)

Enjeux de la qualité de la donnée
*Principes FAIR : accompagner la qualité de la donnée*

Tous les métiers techniques sont impliqués dans la réflexion en cours sur la qualité de la donnée (cycle de vie, traitement, archivage...)

*Diffusion de la culture FAIR* dans les labos

## Présentation par le Grand témoin de la journée Volker Beckmann, Directeur adjoint scientifique en charge du domaine "Calcul et données" de l'Institut national de physique nucléaire et de physique des particules (IN2P3) sur les enjeux des principes FAIR (15 min.)

Thématique données importante

Open science : open access + open data + open infrastructures

Créer la fonction de data steward et généraliser le recours au DMP pour les projets

L'open data commence avec une bonne connaissance des données.

* F : métadonnées, DOI, ORCID
* A : portail de données
* I : métadonnées, interfaces, DMP
* R : logiciel, expertise, documentation et publications

### 3 points clés :
- métadonnées lisibles par les machines
- trusted repositories
- incentives et motivations


-------


## 9h30 - 10h45 Session 1 : Quelles formes de pérennisation pour quels types de données ?

Présidente de séance : Caroline Martin (Atelier Données, réseau MEDICI)

## Traçabilité des activités de recherche dans les unités de recherche, Alain Rivet (Centre de Recherches sur les Macromolécules Végétales)

Déferlante d'octets, ère du big data (LHC 40.000 gigas / an , Very large telescope)
Données uniques : banquise, archéo à Palmyre

Evaluation par les pairs montre de plus en plus ses limites.
Scandales Stapel et Voinnet

### Risques
Incapacité à apporter la justification d'un résultat. De moins en moins d'encadrants dans les labos, pression forte sur les chercheurs. Probabilité d'erreurs importante et impact de plus en plus fort.

### Quelle réponse ?
Charte de déontologie des métiers de la recherche. Signature d'une attestation depuis 2016.

Enquête DIST 2015
Enquêtes produisent-elles des données ? OUi, 67%. Avez-vous des données ? Non, 67%

### Guide mis en place par le réseau Qualité en recherche
http://qualite-en-recherche.cnrs.fr/spip.php?article315
Recommandations : plans de classement avec nommage des fichiers, fiches projets qui associe les différentes étapes : réuions, CR, jalons du projet, cahiers de labos et archives numériques
Communication de ces documents aux nouveaux entrants dans le labo : feuille de route du labo, par exemple

Garantir la traçabilité et la robustesse des résultats
Capitaliser les savoirs et savoir-faire
Respecter les dispositions réglementaires

### Réponse organisationnelle
Démarche qualité en unité de recherche (ISO 9001)

Multi-compétences : chercheurs, documentalistes, informaticiens, qualiticiens

Question : la vision qualité colle-t-elle à des pratiques où le DMP et la norme ISO 9001 vont être considérées comme des paperasseries supplémentaires.
Réponse : s'organiser, se tourner vers des référentiels. Montrer les exemples de scandales : si on vous demande de ressortir vos données, comment ferez-vous ?

Question : est-ce qu'on ne devrait pas confier cette gestion rigoureuse de la donnée à des personnels dont l'organisation et la métadonnée sont le métier ?
Réponse : sensibiliser les gens

## Retour d'expériences sur la publication de données en biologie, Pierre Poulain (Institut Jacques Monod, UMR7592, CNRS et Université Paris Diderot)

Croit à l'open science, à la reproductibilité, concrètement comment on fait ?

Publications : tableaux de données, paramètres de simulation, programmes informatiques, données massives

Site web perso ou du labo : pas adéquat pour les données

Tableaux de données : liste de 3000 séquences de protéines. DOI sur Plos One. Publication en pdf, mais bon...

Fichiers de paramètres : "recette de cuisine" pour obtenir les résultats. Figshare : bonne expérience, accessibilité, licences choisies

Figshare : 2011, Marc Hahnel (doctorant), racheté par Digital science (Overleaf, Altmetrics), propriétaire de Holzbricnk, lui-même dans le groupe Springer Nature
Voir : Figshare and the FAIR data principles

Elsevier se présente maintenant comme une société d'analyse de données....

Tableau de données : jeu de données déposé sur Zenodo, DOI, téléchargement. (Zenodo : OpenAIRE + CERN). Zenodo ++ pour lui

Code informatique : code source accessible. D'abord sur Github, mais pas de garantie de pérennité, donc dépôt sur Zenodo.

Software Heritage : projet de l'Inria. Identifiant unique. Projets sur Github sont aspirés automatiquement sur ce site.

Données massives en biologie, "omiques" : séquençage haut débit (ADN/ARN), Gene expression omnibus (GEO), Sequence read archive (SRA). Protéomique, spectrométrie de masse : proteomics identifications (PRIDE).
Pas d'info sur le fait que les données sont FAIR sur ces sites, à creuser

Questions sur les dépôts : supplementary data de PLOS vont automatiquement dans Figshare. Confiance en Zenodo parce que projet européen.

## Les principes FAIR appliqués aux sauvegardes sur le long terme, Marie-Claude Quidoz (Centre d'Ecologie Fonctionnelle et Evolutive)

### Contexte
Concentration sur données qui ont un intérêt pour la communauté, qui ne sont pas associées à une publication, qui doivent être archivées

### Archivage
15 ans

But : réutilisation des données, donc FAIR pour que la réutilisation soit possible par humain ou machine

Sauvegarde de données sur bandes : mais illisibles 25 ans plus tard...

Sauvegarde dans un format qui n'est pas totalement interopérable, sur Zenodo notamment : sql par exemple, qu'il va falloir relire avec certaines versions de logiciels (infos essentielles à mettre dans un readme)

Autre exemple sur datadryad : information pour les être humains et pour la communauté. Info qui peut être récupérée, mais difficilement exploitable.

Problèmes des logiciels qui n'existent plus et qui rendent impossibles la réutilisation des données.

### 4 risques
* obsolescence matérielle,
* obsolescence logicielle,
* perte du format de fichier,
* perte de la signification du contenu.

### Quelles réponses ?
- règle du 3-2-1 : 3 copies sur 2 supports différents, dont 1 dans un lieu distant
- étiqueter avec soin
- tester de façon régulière
- suivre les évolutions technos et migrer les fichiers sur un autre support
- inclure cette réflexion dès le départ dans le DMP, politique de sauvegarde à long terme, temps & budget

Privilégier un logiciel largement utilisé, avec sources publiées, et enregistrement sous un format pérenne.
Anticiper les possibilités de sortie du logiciel en termes de coût et de temps/homme
Durée de vie d'un logiciel est toujours inférieure à la durée de vie des infos

Privilégier des formats : publiés, largement utilisés, normalisés
Format durable (CINES) : archivage pérenne. PDF, CSV/TSV/TXT, TIG/GeoTIFF, etc...
Voir FACILE CINES

Eviter la perte de sens
Utiliser des métadonnées adapatées à la thématique : ISO 19115, EML
Utiliser des ontologies (ou les créer) pour définir de façon précise et sans ambiguïté ses données
Sauvegarde dans un format machine lisible : CSV on the web, JSON_LD (web sémantique)

### Solution, l'entrepôt de données
Sans sensibilisation des déposants, les risques persistent. Déposer sur entrepôt ne garantit pas la pérennisation des données

Enorme travail à faire pour sensibiliser sur la question de la pérennisation des données

*Joke : pourquoi met-on un identifiant pérenne sur une ressource qui n'est pas pérenne ?*

Question : ce n'est pas le boulot du CINES d'assurer la pérennisation ?
Réponse : entrepôt doit être créé avec des règles précises

Question : maîtrise des supports par le CNES depuis plus de 25 ans. Travail très lourd sur les bandes qui se démagnétisent

Question : le xml n'a pas été cité comme format pérenne
Réponse : ne va peut-être pas duré longtemps
Question : xml ok si associé au xsd (balises associées au sémantique)

## Pérennisation de logiciels de la recherche, le projet PRESOFT : Preservation for REsearch SOFTware ou Pourquoi et comment FAIR un SMP ?, Teresa Gomez-Diaz (Laboratoire d'Informatique Gaspard-Monge) et Geneviève Romier (Centre de Calcul de l'IN2P3)

Les logiciels sont des données, donc les principes s'y applique
On peut faire des SMP, software management plans, comme on fait des DMP

Outil qui permet de concentrer toutes les infos qui concernent un logiciel de la recherche. Ne pas confondre avec un plan de développement de logiciel (il sera référencé dans le SMP)

### Projet Presoft, IN2P3
Procédure et modèle : cycle de vie du logiciel (travail préparatoire, prototype, projets/finacements, développement, utilisation, diffusion (résultats scientifiques, publications), etc.

### Modèle intégré dans DMP opidor
Avantage de DMP opidor : pérennité, màj permanente possible

Proposition de projet qui peut être dans une proposition de projets.


-------


## 11h15 - 12h30 Session 2 : Méthodes et outils, quelle alliance pour réussir les projets de valorisation des données en SHS ?

Président de séance : Stéphane Renault (Atelier Données, réseau MEDICI)

## FAIR en linguistique de la langue orale : objectifs, méthode et outils, Loïc Liégeois  (Laboratoire de Linguistique Formelle, UP7), Carole Etienne (Interactions, Corpus, Apprentissages, Représentations) et Christophe Parisse (Modèles, Dynamiques, Corpus)

### Consortium CORLI (corpus, langues et interactions)
Fédérer les labos, partager les bonnes pratiques
Partenariats : CLARIN, DARIAH, consortium TEI

FAIR en linguistique

### Findability
Plusieurs types de métadonnées :
- situation : pro/privé, face à face/distance
- locuteurs adulte/enfant, natif/non natif
- enregistrement: format diffusion / analyse
- modes de citation
- conditions accès : diffusion, anonymisation
- annotations / transcription : nature et convention
- formats de fichiers de transcriptions

### Accessibility
- Tradition d'archivage depuis 2000
- Temps long pour constituer les corpus : recherches de terrain, etc
- Annotations : une à plusieurs heures pour une minute d'enregistrement
- Vérification du processus : conservation
- Constituer des corpus à réutiliser

### Interoperability
- Explorer les mêmes données : analyses syntaxiques, prosodiques, sur une même donnée
- Contraster le même objet d'étude dans une autre perspective : écrit/oral, enfant/adulte, etc
    - identifier,
    - etc
- solutions pour les métadonnées et solutions pour les annotations
- jeu commun de métadonnées : appli personnalisée (avec equipex ortolang) : fichier TEI/ODD

### Reusability
- Licence
- Teimeta


## Les périodiques du Muséum à l’heure du tout-numérique, Emmanuel Côtez, Anne Mabille et Chloë Chester (Muséum d'Histoire Naturelle)

Périodiques Museum
Taxonomie

Publications en pdf/a

Références du 19e siècle toujours cités aujourd'hui. Comment rendre les données disponibles aujourd'hui et réutilisables par des machines ?

Identifiants : DOI et LSID (id pour publis et espèces)
GIBI (Global Impact Biodiversity Initiative) : base de données biodiversité
Standards et vocabulaires dans le domaine : Dublin core

DOI des articles du Museum : bioone.org
Portail de diffusion : http://sciencepress.mnhn.fr

Rétro-numérisation, archives en ligne

Désormais, publications en flux continu, plus d'abonnement

Idée : cibler les bases de données de la recherche...
Point à régler, comment faire ?

## Produire et diffuser des métadonnées thématiques pour l’archéologie : entre savoir-FAIR et pratique collaborative, Blandine Nouvel (Centre Camille Jullian) et Miled Rousset (Maison de l'Orient et de la Méditerrannée Jean Pouilloux)

Réservoir de métadonnées pour l'archéo pour partage et réutilisation

### Thésaurus PACTOLS
PACTOLS : peuples, anthroponymes, chronologie, etc.
Servait à l'indexation du catalogue des bibliothèques du réseau Frantiq. Enrichissement. Migration sur Opentheso. Ouverture du thésaurus

### Workflow collaboratif
Propositions, contrôles & validation, insertion, corrections et enrichissements, accompagnement et formation

### Thésaurus et FAIR
* FA : applications (propriétaire, site web, PHP-MySQL), fonctionnalités (recherches par mots-clés et termes thésaurus)
* I : applications (Opentheso), fonctionnalités (norme ISO 25964, SKOS, JsonLD, Turtle import/export libres)
* R : applications (Opentheso), fonctionnalités (URI : Ark, Handle, Alignements, Licence ODbL)

### Alignement thésaurus avec le linked open data
Versement dans Wikidata : URI : Ark
Interconnectable avec autres bases. Vocabulaires liés : Géonames, Rameau, MESH, ...

### Interopérabilité d'Opentheso
API pour interconnecter avec SIGB Koha (catalogue de Frantiq : les catalogueurs récupèrent les mots-clés), édition scientifique (chaîne Métopes XML-TEI), Programme de valorisation du patrimoine (OmékaS), Système d'enregistrements de terrain (ArSol, EDArc)

Question : Wikidata ?
Rép : alignement automatique, puis contacts

## Les principes FAIR appliqués aux données archéologiques produites par l’Inrap : état de la réflexion et des projets en cours, Emmanuelle Bryas, Camille Colin, Anne Moreau et Christophe Tufféry (Institut National de Recherches Archéologiques Préventives)

### Cycle de vie des données à l'INRAP : produits et solutions
- Création : EDArc (système d'enregistrement de terrain). Outil sur tablette, principes d'interopérabilité technique et sémantique (xml, thesaurus PACTOLS, etc). Autre exemple : catalogue de données spatiales, CAVIAR...
- Traitement : DOLIA, référencement, description et localisation des ressources (rapports d'opérations d'archéo préventive, consultable en ligne pour certains, Unimarc, PID Ark)

### Mise en place d'un DMP pour les opérations d'archéo préventive

Rapports d'opération versés au CINES : description en Dublin Core + notices bibliographiques en Unimarc. Reprise de la chaîne de productions de leurs fichiers

Programme européen ARIADNE : appariement CIDOC CRM (ontologie de l'information relative au patrimoine culturel)

* F: CIDOC CRM
* A : Dolia, Caviar, CINES
* I : EDArc, QGis
* R : CIDOC CRM


-------


## 14h00 - 15h30 Session 3 : Les principes FAIR, une nouvelle opportunité pour améliorer ses pratiques en matière de gestion de données ?

Président de séance : Maurice Libes (Atelier Données, réseau RESINFO)

## Observatoire Virtuel et FAIR, des principes fondamentaux à la pratique, André Schaaff (Observatoire Astronomique de Strasbourg), Laurent Bourgès (Observatoire des Sciences de l'Univers de Grenoble), Karin Dassas (Institut d'Astrophysique Spatiale), Jean-Michel Glorian (Institut de Recherche en Astrophysique et Planétologie), Jean-Charles Meunier (Laboratoire d'Astrophysique de Marseille), Michèle Sanguillon (Laboratoire Univers et Particules de Montpellier) et Pierre Le Sidaner (Observatoire de Paris)

Astronomie, grande productrice de données

Collecteurs d'ondes radio SKA : production annuelle de données 300 Peta

Réutilisation des données : nombre de publications basées sur les observations directes de Hubble sont dépassées par le nombre de publis postérieures

### Observatoire virtuel
OV, ou International virtual observatory alliance IVOA
Consortium, protocoles, standards d'interopérabilité avec W3C.
En France, une vingtaine de partenaires.
Projet référencé par FAIRsharing

Chercheurs et ingénieurs collaborent depuis le départ du projet

Registre des ressources en OAI-PMH. Protcoles : choix de SOAP, obsolescence, et choix de REST.

OV très utilisé, mais les utilisateurs ne le voient pas

Définition claire et structurée du processus jusqu'à la validation d'un standard dans un temps raisonnable

* F : registre ("pages jaunes...")
* A : implémentation des standards et protocoles : données accessibles
* I : standards et protocoles ouverts
* R : standards sur la provenance, les descriptions. Effort de documentation des données

## Les documentalistes et la FAIRisation des données scientifiques : un travail d'équipe inter-métiers, Soizick Lesteven (Observatoire Astronomique de Strasbourg)

### Plusieurs services :
SIMBAD : BDD pour identification, nomenclature des objets astro
VIZIeR : collection de catalogues astro
ALADIN : atlas interactif du ciel
Info IDIC : nomenclature des objets (qui ont plusieurs noms)

34 personnes, chercheurs, documentalistes, informaticiens

Partenariats : RDA, Core trust seal (certifications data), EUDAT

Pour tout article, recherche des objets astro via Simbad, intégration des tables et autres données sur Aladin, maintien du dictionnaire de nomenclature, description des images du ciel pour Aladin

Standard spécifique en astro (Bibcode ?)

Valorisation des données : identif, sélection, vérif, identifications croisées, ...

* F : fiables, bien décrites
* A : accessibles par tous les serices CDS
* I : OV compatibles, donc interopérables
* R : utilisables par tout le monde

Question : trinôme docs/chercheurs/informaticiens indispensable ?
Réponse : Oui
Rires dans la salle

## Pérennisation et interopérabilité des données de l'Observatoire de Recherche Méditerranéen de l'Environnement, Juliette Fabre et Olivier Lobry (Observatoire des Sciences de l'Univers OREME)

Gestion de données très hétérogènes : développement d'outils et de méthodes aussi mutualisés que possibles

Formats propriétaires, non descriptifs, incohérences...

Quelle chaîne ?

### Structuration
Sortir les données des fichiers, mise sous formats ouverts, nettoyage, modélisation en bases de données relationnelles ou serveurs cartographiqes (très long)

### Description
Dates, valeurs
Réutilisabilité, interopérabilité sémantique
Descriptions dans tables SQL
Intégration dans standards et thesaurus

### Liaison des données
Wikidata, IGN, etc

### Diffusion
Accessibilité, interopérabilité technique/syntaxique
Standards de l'OGC
Licences ouvertes Etalab ou CC
Données numériques diffusées en CSV : ouvert mais pas standardisé.
Données cartographiques : GeoServer

### Cataloguer, identifier
Accessibilité, trouvabilité
Métadonnées : protocoles et standarrs ouverts
Norme ISO 19115 / directive Inspire (norme + directive données géographiques)
Pas de dictionnaire de données (ISO 19110), catalogage pas encore moissonné
PIDs : DOI. Obligation morale : permettre à l'utilisateur de retrouver les données dans leur état initial
Autres formats : EML

Question : versioning sur les données, idem sur les scripts. Comment on fait si on a un DOI sur un objet qui peut évoluer

Question : data papers ?
Réponse : non, mais

## Make your data great (again), Daniel Jacob (Institut National de la Recherche Agronomique)

Capturer les données le plus en amont possible, dès que la donnée est disponible

*Comment encourager les producteurs de données à investir du temps et de l'énergie ? Ça marche pas...
Inciter plutôt que contraindre* : proposer des services qui leur soient utiles en leur permettant de gagner en efficacité

Travail avec chercheur sur fichier xls basique, récupération dans un data explorer, puis proposition de templates sur R, etc. Derrière, Web API

Mettre en place guides de bonne pratique, apporter une assistance, *promouvoir le CSV, qui est une marche vers le linked data. CSV : donnée brute, et on s'en débrouille sans parler de FAIR au chercheur.*

Pour métadonnées, demander un autre CSV de descriptions

FAIR : repose aussi sur le code
Transparence sur le code : préparation des données, collecte, etc.

Question : proposer des outils qui simplifient le travail. L'archivage, c'est sympa parce que ça permet de travailler à plusieurs, etc.


## OpenData pour la simulation et les expérimentations au LEGI, Gabriel Moreau, Antoine Mathieu, Cyrille Bonamy, Joël Sommeria, Julien Chauchat (Laboratoire des Ecoulements Géophysiques et Industriels)

Publication d'une archive sur Zenodo, proposer un accès distant OPeNDAP, partager et utiliser des scripts (Jupyter Notebook + OPeNDAP)

Coriolis : plateforme de données : 1 To de données par jour, avec manipulations non reproductibles (budget de manipulation énorme)

Data : zip sur Zenodo, mais limité à 50Go. Pour utilisateur final, il faut télécharger l'archive et travailler sur son PC

Création d'outil : project-meta
Déclaration de métadonnées au format YAML, Dublin Core
Script génère automatiquement les txt : license, readme, authors, copyright

Niveau 2 : OPeNDAP, Data Access Protocol
Utilisateur final fait un téléchargement partiel
Pas de PID, obligation d'avoir son propre serveur

Scripts Python sur Notebook Jupyter : possibilité de partages de ces scripts


-------


## 16h00 - 17h30 Session 4 : Synthèse de la journée

Présidente de séance : Emmanuelle Morlock (Atelier Données, réseau RENATIS)

## Présentation de RDA France, par Francis André (Direction de l'Information Scientifique et Technique du CNRS) (10 min.)

Acteurs de la recherche doivent se partager les données
Forum international, créé en 2013
Propositions de recommandations soumises à la communauté, puis labellisés (fonctionnement similaire W3C)

GT : 18 mois
Groupes d'intérêt : pas de limite temporelle

FAIR : lisible en machine

*"Evaluez votre degré de fairitude..."*

## Conclusion par Volker Beckmann, Grand témoin, Directeur adjoint scientifique en charge du domaine "Calcul et données" de l'Institut national de physique nucléaire et de physique des particules (IN2P3)

### Recommandations pour la traçabilité
Quels sont les entrepôts de confiance pour nous ? Dépôts des éditeurs ou académiques
Standards pour données FAIR, sinon difficile à rattraper ensuite
Défis technologiques pour décrire des données FAIR
Conserver les données de la biodiversité pour les espèces en voie de disparition. Du PDF à xml.
Défis à long terme : infrastructures
Standards et formats ouverts, etc.
ODAM : solutions faciles pour petites expériences

### Défi pour le FAIR data n'est pas technique, mais politique et juridique

Communautés scientifiques : travailler sur les formats/standards/recommandations interopérables. Connecter les données avec les autres communautés. S'accorder sur des recommandations de haut niveau, pas une par institut

Clés RH : motivations, collaborations, réseaux, interdisciplinarité

### Incentives
Motiver les communautés pour changer leur culture des données
Carrière scientifique : donner aux données FAIR une importance en tant que publications

Pour le ministère : données FAIR et Open science n'est pas gratuit...


-------


## Discussion

Agnès Robin, MCF Montpellier, projet Common data : gestion par les chercheurs de leurs données
Approche technique en ce qui concerne les plateformes : quels sont les contrats derrière ? Est-ce que les solutions qui permettent de garantir l'auctorialité ?

Données de santé : agrégation des données, espace des données temporelles et spatiales (ex d'un cas de paludisme d'un enfant de 5 ans dans un hameau : risque d'identification possible, publier un jeu avec granularité plus large pour le lieu)
