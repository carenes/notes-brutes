# Dialogu'IST - Recherche reproductible
http://renatis.cnrs.fr/spip.php?rubrique107

## Introduction de l’atelier et retour sur l’engagement de l’Aix-Marseille Université (AMU)
**Fabien Borget, Aix-Marseille Université, Enseignant-Chercheur**

* Atelier Dialogu'IST ajouté au catalogue des formations du CNRS !
* Intégrité scientifique : augmentation presque exponentielle des rétractations.
* Contexte pousse-t-il les chercheurs aux limites de l'éthique ? Rôle du Publish or perish ?
* Archives ouvertes : ArXiv
* Loi pour une République numérique : redonner du sens à la recherche, concept qui bouleverse les pratiques et oblige à les repenser. Mise en œuvre : exemple de la feuille de route du CNRS.
* Aix-Marseille université est en train de se doter d'une maison de la donnée
* La moitié des publications du CNRS est encore en accès fermé, pas mal de travail d'ici 2020.
* Mise en œuvre pour les données : principes FAIR
* Enjeux : infrastructures à créer pour le stockage, quels coûts, quels formats pérennes, etc.
* Revenir à une vraie intégrité scientifique, créer un contre-pouvoir contre les éditeurs.
* Evolution des usages : l'évaluation des chercheurs est intimement liée à ces questions.
* Faire vivre la science ouverte, notamment par l'innovation


## Contexte et définitions de la Recherche Reproductible, Sabrina Granger, Urfist Bordeaux
**"Reproductibilité de la recherche, la crise et ses vertus"**

* Recherche reproductible et science ouverte ne sont pas des synonymes.
* RR : définition qui remonte aux années 90, colloque de géophysicien. L'article est une vitrine imparfaite du travail de recherche.
* Notion qui connaît un changement de paradigme, avec la SO.
* Objectifs : transparence de la recherche, mise à disposition du public, accessibilité, collaboration.

> Transparency in experimental methodology, observation, and collection of data.
> Public availability and reusability of scientific data.
> Public accessibility and transparency of scientific communication.
> Using web-based tools to facilitate scientific collaboration
< Gezelter, Dan. 2016. « What, exactly, is Open Science? | The OpenScience Project ». http://www.openscience.org/blog/?p=269

* Sabina Leonelli : philosophie des sciences
* UCL : feuille de route science ouverte et recherche reproductible. Humanités : RR dans le sens de forte attention portée à la méthode, puisque la reproductibilité ne s'applique pas telle quelle aux LSHS.
https://www.ucl.ac.uk/research/sites/research/files/ucl_statement_on_transparency_in_research_november_20191.pdf
* Jupyter notebooks : très bon outil, mais pour l'instant les carnets étudiés ne sont pas exploitables, car il manque une méthodologie
* Fraudes : souvent un problème de maîtrise des méthodes, pas une volonté de frauder. La méthode appliquée aux données peut faire varier les résultats.
* Recherche reproductible vs résultats positifs. Etudes de réplication ou résultats négatifs sont souvent publiés dans des revues de rang moindre. Ne paie pas pour l'évaluation
* Attentes des chercheurs : meilleure compréhension des stats, meilleur accompagnement, study design
* Problème avec les stats pour les disciplines qui les utilisent : appel pour que la formation ne soit pas destinée qu'aux doctorants
* Question : est-ce que les bib français doivent devenir des développeurs et apprendre R, Python, etc ?
* Expertise : connaître le contexte de production de la donnée et les problèmes rencontrés. L'expert est aussi celui qui peut agir avec une certaine économie de moyens. Laisser aux ingénieurs ce qui est aux ingénieurs
* Expertise dans nos propres domaines : cataloguer le code ? créer des métadonnées spécifiques ?
* Besoin d'experts et de généralistes : point de vue complémentaire de celui de l'expert
* Nouvelles compétences : parallèle avec la médiation culturelle
* Horizon d'attente : en fonction des disciplines, on a des attendus. Conformisme disciplinaire. Biais d'orientation (?).

## Le R des données FAIR, un atout en premier lieu pour les chercheurs : retour d'expérience sur les aspects à la fois techniques et psychologiques de la mise à disposition des données de la recherche  
**Daniel Jacob, INRA Bordeaux, Plateforme Métabolome, Ingénieur de Recherche**

* N'est pas un enthousiaste du FAIR
* Travail sur les données depuis 10 ans, labellisation. Ont renoncé aux labels, roue sans fin. Qualité aujourd'hui est faite selon leurs référentiels, en fonction de ce qui est utile pour eux.
* Donnée : n'est pas purement numérique, on ne peut pas faire des stats avec toutes les données. Images, données spectrales, qui derrière demandent de l'expertise, du croisement d'autres données, avec un savoir-faire qui prend du temps.
* Données FAIR, reproductible compliant : ce sera difficile de les contester. Ne répond pas à la question de l'éthique.
* On ne fait rien ?
* Passer par le DMP : le DMP n'est pas un outil neuf pour certaines disciplines, on le redécouvre. DMP pour les plateformes ?

## Retour d’expérience d’une communauté, le GBIF (Global BiodiversityInformationFacility, gbif.fr)
**Anne-Sophie Archambeau,responsable du point nodal France, Muséum National d'Histoire Naturelle**

* Programme intergouvernemental, OCDE, 2001
* Constat : manque de données brutes
* 59 pays participants, 38 organisations associées
* But : accès libre et ouvert aux données de biodiversité
* Rendre accessible les données, pouvoir les utiliser, mettre sous les bons formats (FAIR avant FAIR)
* Données de spécimen, séquences génétiques. 1 milliard de données
* Données fournies par des machines : télédétection (arbres reconnaissables, grands troupeaux)
* Données brutes extraites de la littérature
* Point nodal du GBIF France : missions sont d'aider les chercheurs à connecter les données en utilisant les bons standards et protocoles, formation
* GBIF France : appui au Sud
* En France, Museums français, CNRS, INRA, INPN (?)
* Pas de DMP, mais aide à tous les niveaux du cycle des données : nettoyage, standards. Package R GBIF
* Processus : licences sur chaque jeu (avant 2016, pas forcément de licence. Travail de rétroaction). Si pas de licence, la loi du pays s'applique.
* Standards : darwin core et ABCD, EML
* DOI : à chaque nouveau jeu. Les jeux téléchargés ont aussi un DOI : permet de mieux suivre les citations.
* Data paper : un DOI. Travail avec Pensoft. Quand ils ont rempli toutes les informations pour un dépôt, ont presque un data paper clé en main. Motivation pour les dépôts.
* Le GBIF est-il FAIR ? Contact de la GOFAIR initiative : à 90% oui. Difficultés autour du I et du R.
* A chaque jeu de données sur le site, lien vers publis associées.
* GBIF labellisé par le Core Trust Seal et FAIRsharing
* Formations : Open Badges. Deux niveaux
* Travail avec Yvan Le Bras
* GBIF : plus science ouverte que FAIR, sauf données sensibles. Floutage des données sensibles, ou mise en ligne des seules métadonnées (accès aux données sur contact).
* Traduction du portail : boum d’utilisations
* Propriété des données : producteur. GBIF aide à connecter.
* PNSO + loi biodiversité : a boosté les travaux.
* GBIF self assessment : aide pour les DMP
* Etalab : ne marche pas au niveau international. Donc licences CC.
* Sciences participatives : de nombreux jeux. Sciences participatives : pas tellement plus d'erreur
* DOI par téléchargement : quand on fait une extraction de données du GBIF, on recrée un jeu de données, donc DOI.

## Comment enseigner et sensibiliser les étudiants à la gestion et réutilisation des données – Retour d’expérience
**Véronique Ginouvès, AMU- CNRS, UMR 3125, Ingénieure de Recherche**

Master dans le département Histoire et humanités
https://formations.univ-amu.fr/ME5HHC-PRHHC5AC.html

* VG participera au DU de Montpellier
* Responsable : Agnès Robin, juriste à Montpellier
* Institut de la science des données, en intégrant la dimension de la gestion des données
* Comprendre l'environnement (gouvernance et questions juridiques), outils d'analyse (TDM, sécurisation, fouille), ouverture (DMP, stockage, diffusion et valorisation)

## Mooc « Recherche reproductible : principes méthodologiques pour une science transparente », Retour
**Laurence Farhi, Inria, Ingénieure pédagogique pour le Learning Lab**

* Future session : incorporation des SHS
* Avec Sabrina Granger, Laurent Romary, etc.
* Session en mars, ouverte sur un an renouvelable
* Contenu : reproductibilité de la recherche sur les SHS, encodage de textes en TEI, sources et ressources bibliographiques (utilisation des sources comme un outil de transparence)
* Formation proposée à des ED.
* Prise en compte possible du MOOC par la formation professionnelle

## Conclusion, Fabien Borget
* FAIR : attention au risque marketing, en faire une réelle avancée conceptuelle
