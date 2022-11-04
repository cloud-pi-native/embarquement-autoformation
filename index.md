# Parcours de formation


## Tronc commun
### Le "nouveau monde logiciel": cloud au centre, cloud native
- Le logiciel a dévoré le mondela 
- La culture utilisateur a évolué
- Le travail de développement a évolué 
- Le cloud au centre
- Les technologies "cloud native": API, microservices, conteneurs, kubernetes... 
- Les nouvelles approchses de production: DevOps, DevSecOps, mode produit..


### Fondamentaux et bonnes pratiques dans le nouveau monde logicel: parcours DevSecOps
- Définir et planifier: Le projet suit une méthodologie de développement agile, implémentée en Scrum, dans laquelle on débute avec la
définition des besoins et la planification des activités
- Développer: Le processus se poursuit avec une phase de développement dans laquelle le code est construit par des développeurs internes à l’administration,
mais aussi par des collaborateurs externes à partir de GitHub
- Validation du code: L’approche de collaborations sur le développement du code permet d’obtenir une bibliothèque centralisée et contrôlée par version. Les
développements et modifications effectuées peuvent indure des vulnérabilités. Il est donc essentiel de valider cette collaboration à travers une analyse rigoureuse. D’autres vulnérabilités sont à prendre en compte tels que la gestion des dépendances, les tests de sécurités, et la sécurisation des pipeline CI/CD
- Générer et tester: Lors de cette étape, la génération et la mise en production seront automatisées et normalisées à travers des pipelines de build. L’avantage de ces pipelines consiste à modifier le code de façon itérative rapide sans restriction d’échelle. D’autres avantages sont importants tels que la
possibilité de tester sa solution dans un environnement de test et l’automatisation de tests lors du déploiement
- Mise en production: Suite à la mise en production du code, il est essentiel de surveiller l’état de sécurité incluant la configuration, l’infrastructure, et les tests de pénétrations
- Exploitation et optimisation: Cette étape consiste à surveiller en continue l’évolution du code, prévoir les menaces, optimiser la qualité et la performance

### Présentation générale de l'offre Cloud Pi Native
- Documentation Cloud Pi Native
- Lien vers le catalogue du portail Cloud
- FAQ

### Guide pratique
L'objectif du guide pratique est de centraliser l’ensemble des ressources nécessaire à la montée en compétence des équipes technique, métier, et transverse en proposant des ressources de divers format et adaptées à toute l’organisation. Ce guide: 
- Fait le lien avec le catalogue de service MI
- Illustre les étapes du montage et de la gestion d'un projet
- Expose des ressourcesd'autoformation pour chaque étape



## Parcours spécifiques
### Parcours "équipes projet": développeurs, architectes solution, intégrateurs...
Ce parcours s'adresse aux personnes qui livrent du code applicatif. L'objectif est de leur permettre de s'appuyer sur les moyens d'une plateforme de livraison DevSecOps proposant des outils d'intégration et de déploiement au standard et à l’état de l’art.

Niveau 1 : Fondamentaux/adoption des pratiques : 
Dans ce niveau de maturité, vous apprenez les pratiques de bases qu’un développeur doit avoir pour utiliser l’offre DSO :
-à exprimer des epics en collaboration avec les métiers
-à bien gérer vos projets en maîtrisant un outil de collaboration et de développement logiciel, et un outil de versionning
- à faire des tests d’intégration lors de vos builds, des tests d’acceptance lors de vos déploiements, et de l’analyse dynamique de code dans vos environnements de production
- à maîtriser un outil de gestion de configuration pour faciliter vos déploiements
- les bases du monitoring (gestion basique des logs)
- les bonnes pratiques de la mise en service (feature toggles)

Niveau 2: Avancé/ maitriser la qualité jusqu'à la livraison
Dans ce niveau de maturité, l'objectif est la matrise du niveau de qualité du code de bout en en bout. Pour cela vous apprendrez :
- la conception d’une application en utilisant l’offre DSO
- à aller plus loin dans les tests du cycle de vie d’un logiciel (tests unitaires, tests fonctionnels, tests de performance)
- à maîtriser la conteneurisation et son orchestration
- à déployer vos codes applicatifs dans des environnements de tests
- à monitorer vos applications et à assurer de la haute disponibilité
- les concepts de déploiement « blue/green » et les mettrez en pratique

Niveau 3 : Expert/ Être autonome sur la chaine DevSescOps 
Dans ce niveau de maturité, vous montez en autonomie sur l’utilisation de l'ensemble la chaîne DevSecOps et apprenez :
- les concepts de l’architecture d’une application basé sur Cloud Pi Gen 2
- à automatiser vos différents tests
- à faire du développement piloté par les tests, des tests de non regression, des smoke tests et des tests d’intrusion
- à maîtriser un outil d’intégration et de déploiement continu ainsi qu’un outil de provisionning
- à faire du monitoring d’infrastructure et d’assurer un plan de reprise d’activité (DR) 
- les concepts de déploiement « canary releases » et vous les mettrez en pratique



### Parcours "gestionnaires de projet": direction de programme,chefs de projets, architectes d'entreprise...
Ce parcours s'adresse aux personnes qui pilotent les équipes de production du code applicatif. L'objectif est de comprendre les fondements, modes de travail et impacts d'une infrastructure DevSecOps sur une organisation de production. 
Description : Pilote des ressources de développement
Objectif : Disposer d’une offre claire, validée et résiliente d’un point de vue technique, permettant de limiter les risques

Niveau 1 : Fondamentaux/introduction au DevSecOps 
Dans ce niveau de maturité, vous apprenez les fondements du DevSecOps : 
- réaliser une étude de cas DevSecOps 
- les premeirs éléments de la transformation organisationnelle et la façon de travailler qu’emmène le DevSecOps 
- les premiers éléments du pilotage par le test et les métriques et mesures indispensables au pilotage de projet en mode DevSecOps 
- les concepts d’une architecture à couplage faible, avec des composants facilement réutilisables et des logiciels facilement testables 
- à définir les features de votre backlog

Niveau 2 : Avancé/travail en DevSecOps 
Dans ce niveau de maturité, vous apprenez comment travailler dans un cadre DevSecOps soit à  : 
- comprendre comment DevSecOps est guidé par des comportements tels que la collaboration et l'acceptation du changement. 
- concepts tels que l'infrastructure éphémère, qui met l'accent sur la construction rapide, puis la mise au rebut lorsque cette construction n'est plus nécessaire. 
- prioriser les features définies dans votre backlog 
- concevoir une application en utilisant l’offre DSO 
- Comment aller plus vite, utiliser l'automatisation et passer plus de temps à construire des fonctionnalités et moins de temps à déboguer lors des intégrations

Niveau 3 : Expert/Organisation en DevSecOps 
Dans ce niveau de maturité, vous comprendrez l’impact du DevSecOps sur l’organisation, la création de valeur et sa mesure dans une persepctive d’amélioration  continue : 
- comment la production d'un produit minimum viable vous permet de tester une hypothèse et d'obtenir un retour d'information précieux sur la livraison de ce que le client désire vraiment. 
- définir une organisation optimale pour les équipes DevSecOps. Vous passerez en revue une variété de perspectives sur DevSecOps et explorerez les idées fausses sur DevSecOps 
- les principes de l’architecture en microservice 
- le concept Behavior Driven Development et saurez en appliquer le cadre 
 à prendre des décisions basées sur des métriques et données factuelles



### Parcours "décideurs": direction métiers, sponspors et commanditaires, responsables politiques...
Description : Donne le mandat, les moyens et se porter garant de l’engagement
Objectif : Aligner l’offre avec la feuille de route, les doctrines et les orientations législatives. Améliorer l’image et réduire les risques au niveau politique publique

Niveau 1 : Fondamentaux 
Introduction au DevSecOps 
Ce niveau de maturité atteint, vous apprenez les fondements du DevSecOps : 
 à réaliser une étude de cas DevSecOps 
Vous toucherez aux premiers éléments de la transformation organisationnelle et la façon de travailler qu’emmène le DevSecOps 
 les premiers éléments du pilotage par le test et les métriques et mesures indispensables au pilotage de projet en mode DevSecOps 
 les concepts d’une architecture à couplage faible, avec des composants facilement réutilisables et des logiciels facilement testables 
 à définir les features de votre backlog

Niveau 2 : Avancé
Travailler en DevSecOps 
Ce niveau de maturité atteint, vous apprenez comment travailler dans un cadre DevSecOps : 
Vous verrez comment DevSecOps est guidé par des comportements tels que la collaboration et l'acceptation du changement. 
 à prioriser les features définies dans votre backlog 
 la conception d’une application en utilisant l’offre DSO 
 à aller plus vite, à utiliser l'automatisation et à passer plus de temps à construire des fonctionnalités et moins de temps à déboguer lors des intégrations

Niveau 3 : Expert
Organisation DevSecOps 
Ce niveau de maturité atteint, vous comprenez davantage l’impact du DevSecOps sur l’organisation, la création et la mesure de la valeur, et l’amélioration en continue : 
Vous découvrirez comment la production d'un produit minimum viable vous permet de tester une hypothèse et d'obtenir un retour d'information précieux sur la livraison de ce que le client désire vraiment. 
Vous découvrirez l'organisation optimale pour les équipes DevSecOps. Vous passerez en revue une variété de perspectives sur DevSecOps et explorerez les idées fausses sur DevSecOps. 
Vous comprendrez le concept Behavior Driven Development et saurez en appliquer le cadre 
 à prendre des décisions basées sur des métriques et données factuelles

