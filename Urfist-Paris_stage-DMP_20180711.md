# Stage DMP Urfist

## Définition
- Document qui décrit la façon dont les données seront obtenues, traitées, organisées, stockées, sécurisées, préservées, partagées au cours et à l'issue du projet. 
- Aide à la mise en place de bonnes pratiques de gestion à toutes les étapes du cycle de vie des données (création, traitement, analyse, préservation, partage, réutilisation, ...)
- Définition du jeu de données : ça n'a rien à voir avec la taille, mais plutôt avec la cohérence du contenu. C'est le chercheur qui définit la granularité. Un jeu de données = un DOI = une collection. Viser le niveau qui sera cité dans les publications. Autre façon de définir le grain : les auteurs, les personnes qui ont produit et qui sont d'accord pour la diffusion

## Le DMP et le projet
- Pas de grille unique 
- Responsabilité dans le projet : en quoi consiste le projet, qui sont les partenaires, quelle est la politique de gestion des données, qui est le responsable de la gestion des données ?
- Notion de workpackage pour les gros projets : un responsable par sous-projet
- Collecte des données : quelles données seront produites/utilisées au cours du projet (type, format, volume et accroissement), comment seront-elles produites et transformées
- Sauvegarde: comment, où, par qui
- Description: identifiant ? standards de métadonnées ? comment les métadonnées sont générées ?
- Archivage : plan pour l'archivage pérenne
- Ethique : données personnelles, sensibles, utilisées ? Quelle anonymisation ? 
- Propriété intellectuelle : qui va être propriétaire ? Quelle utilisation des données externes, produites par d'autres ?
- Accès et partage : qui ? comment ? dans quel délai ? quelle licence ?
- Ressources : quel financement ?

Plusieurs métiers doivent intervenir pour pouvoir remplir correctement un plan de gestion.

Voir : https://www.icpsr.umich.edu/icpsrweb/content/datamanagement/dmp/table.html

## Objectif du DMP
- Garantir des données fiables et bien gérées tout au long du projet, compréhensibles, disponbiles et préservées sur le long terme pour une réutilisation future. Voir : https://www.ukdataservice.ac.uk/manage-data/plan
- Identifier les risques : sécurité, préservation
- Identifier les responsabilités : qui va faire quoi ? Planifier les ressources et les compétences
- Donner accès à des données fiables : démarche FAIR

## Recherche spatiale
- Instruments coûteux, moyens répartis à l'international.
- Exemple mission Mars Global Surveyor : https://www.msss.com/mars_images/moc/mgssdmp.html
- DMP datant de 1995 : prévoit d'emblée un plan qui prévoit la réutilisation

## Intérêt des parties prenantes
- Financeurs tiennent à la réutilisation pour ne pas payer deux fois
- Organismes de recherche : reproductibilité de la recherche. Baker M. 1,500 scientists lift the lid on reproducibility. Nature News. 26 mai 2016;533(7604):452.
- Chercheurs : diminution du risque de perte des données, diminution des coûts
- Autres : plateformes scientifiques, revues (pour que les reviewers puissent vérifier)

*Reco : publier le DMP avec les données*

## Exigences des financeurs
- Ce sont eux qui imposent les DMP
- USA : NASA, NIH
- H2020

## Commission européenne
- politique d'OA pour publis et données
- H2020 : DMP obligatoire, désengagement possible si partenaire privé, données secret defense, etc.
- Article 29.3 du modèle de convention de subvention H2020
- Coûts : environ 5% du budget du projet consacré à la gestion des données. Assistance auprès d'OpenAIRE2020
- Financements liés à l'ouverture de données, mais pas de prise en charge des coûts de gestion

*Questions : les DMP pourraient être gérés autant par qualiticiens et IST, deux réseaux différents.*

## Versions du DMP
- Version finale de façon publique
- Les deux versions obligatoires : 6 mois, puis version finale
- Versions intermédiaires ne sont pas obligatoires, mais plutôt une façon de travailler

*Interlude juridique, personne n'est d'accord*

## Données FAIR
- Outil d'auto-évaluation : échelle 5 étoiles du CSIRO 5-stars

*Dataverse : fichier .xlsx est transformé automatiquement en .csv*

## Rélfexions en cours à l'INRA
- DMP générique d'unité ou d'infrastructure : intégration de politique de la tutelle. Spécifier standards, processus, protocoles utilisés. Reco et aides adaptées. Rédiger des DMP adaptés pour faire gagner du temps et de la qualité
- Différents types de DMP par usage selon les prestations réalisées par les plateformes. DMP par sources de données (big data, données d'enquêtes, données des observatoires). Par domaines de données. Voir https://www.scienceeurope.org/wp-content/uploads/2018/01/SE_Guidance_Document_RDMPs.pdf

## Comment rédiger ?
- Appliquer les principes du FAIR : https://www6.inra.fr/datapartage/Technologies/Principes-FAIR
- Dans les jeux de données, inclure : données qui n'ont rien donné, codes-sources, etc.
- Mécanismes d'interrogation standards à vérifier : SPARQL, SQL, APIs standards
- Lier les métadonnées avec des liens standards : métadonnées RelatedIdentifier, RelatedPublication, pour lier des DOI par exemple (transparent sur entrepôts)
- Réseau de compétences pour DMP : prévoir un coordinateur par DMP (souvent chercheur producteur), ingénieur -projet, informaticien, spécialistes de l'IST (standards, métadonnées, entrepôts, alignements avec référentiels existants), archivistes, juristes
- Grille de l'INRA est volontairement très fine, pour accompagner la rédaction
- Recommandations diffèrent : plan de 2-3 pages en principe, mais on trouve des plans de 80 pages

## DMP opidor
- Partage possible avec autres collaborateurs identifiés (administrateurs de l'organisme, utilisateurs, etc). DMP peut être public.

> Pour l'évaluation des projets, on reçoit des liens sur papier.

## Relecture de DMP
- Grilles communes en cours de développement : DART project
- Consignes pour relecteur : quelle est la problématique des données au sein du projet ? Questions de la réutilisation, quelles données seront ouvertes et comment ? Si données fermées, pourquoi ? Montrer comment les données seront réutilisables ?

Voir les GT de RDA

