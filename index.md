# Parcours de formation


## Tronc commun
### Le "nouveau monde logiciel", un défi technologique, organisationnel et culturel

Les tendances globales du monde contemporain sont devenues extrèmement difficiles à appréhender. C'est le concept "VUCA": Volatil (les choses changent vite) Complex (en raison de la multiplicité des crises: économique, sanitaire, climatique), Uncertain (intéractions entre toutes ces crises) et Ambiguous (du fait de la complexité et de l’incertitude).

Une révolution numérique est en cours: l'expension du logiciel a redéfini des secteurs d'activités entiers (banque, assurance, hotellerie, service de voyage, taxi, réseaux sociaux, ...) et accélère les transformations du monde (Marc Andreessen "Why software is eating the world").

Un nouveau paradigme logiciel a émergé, celui des GAFA, qui permet de mettre à disposition rapidement, à l'échelle, des produits de haute qualité, de facon résiliente. Ce "nouveau monde logiciel" est défini par 3 ruptures: 
- Une rupture technologique: l'automatisation grandissante de la gestion des ressources informatiques et des réseaux ont rendu incontournable la maitrise du cloud et des technologies associés  dites "cloud native" (conteneurs, API, microservices, kubernetes...)
- Une rupture dans les modes d'organisation et les pratiques de production: le travail des développeurs (Dev) et des opérateurs (Ops) a évolué. De leur collaboration, devenue indispensable, sont nées de nouvelles approches de production (DevOps/DevSecOps)
- Une rupture culturelle: les attentes des consommateurs ont évolué (simplicité et ergonomie maximale, pas de mode d'emploi), les producteurs sont obsédés par le « zéro distance » avec le besoin utilisateur et le produit et placé au centre ("mode produit": feedback régulier, co-construction et évolution en continu)

Afin de remettre l'usager au centre, le service public cherche à maitriser ces ruptures. L'objectif poursuivi est de définir un outillage et une voie d'accès privilégiée permettant appréhender la complexité de ce "nouveau monde"(Lean - Startup - Agile  et cultiver la Tech).


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
Pourquoi cette offre? 
- le numérique au coeur des politiques publique ( LOPMI )
- Besoin de transformation majeur de la culture  « penser numérique »
- Des cycles de production long & friction, qualités se dégradant dans le temps
- Besoin accru de sécurité, d’élasticité et de réactivité 
- La croissance vs coût / impact environnemental non soutenable
- Absence d’un système de normes commun à l l’innovation et au développement de grosse solution. (impossibilité de croître)
- Les usagers « oubliés » de l’écosystème… les développeurs
- Des acteurs SIC dont la formation n’a pas évoluée, un marasme peu de perspectives

Présentation de l'offre:
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


### Parcours "SRE" (Site Reliability Engineering ou ingénierie de la fiabilité des sites) : responsables de la fourniture des services et de l'accomapgnement de l'offre cloud Pi Native...
Ce parcours d'adresse aux personnes responsables du déploiement, de la configuration et de la surveillance du code de l'offre de service Cloud Pi Native. L'objectif est d’assurer la maîtrise de la chaine de l’offre par les consommateurs.

Niveau 1 : Fondamentaux/garantir les environnements de développement : 
Dans ce niveau de maturité, vous apprenez les pratiques de bases qu’un SRE doit maîtriser pour le bon développement des fonctionnalités par les équipes projet via la maitrise des environnements de développement :
- les premiers éléments de l’architecture microservices
- Introduction aux différents outils nécessaires à remplir vos fonctions: versionning, gestion d’images, outils collaboratifs, etc.
- Réalisation de tests d’acceptance et d’intégration
- Bases du monitoring (gestion basique des logs)
- Bonnes pratiques de la mise en service (feature toggles) 

Niveau 2: Avancé/garantir la livraison de versions stables et sécurisées
Dans ce niveau de maturité, vous apprenez à garantir la stabilité et la sécurité des livraisons de code applicatifs sur la chaîne de service DSO. Pour cela vous apprendrez :
- conception d’une application en utilisant l’offre DSO
- maîtrise de la conteneurisation 
- Déployement de codes applicatifs dans des environnements de tests 
- Monitoring d'applications et assurance de la haute disponibilité
- Concepts de déploiement « blue/green » et mise en pratique
- Garantie du bon fonctionnement et la haute disponibilité de la plateforme 
- Réalisation de tests de performance sur la plateforme 

Niveau 3 : Expert/Garantir une continuité de production sur toute la chaine d’intégration et de déploiement
Dans ce niveau de maturité, vous apprenez à être autonome pour accompagner les équipes projet à la compréhension et à l'utilisation de l’offre de service, ainsi que pour mettre en oeuvre l'ensemble des bonnes pratiques:
- Concepts de l’architecture d’une application basé sur Cloud Pi Gen 2
- Automatisation de vos différents tests
- Développement piloté par les tests (TDD), des tests de non regression, des smoke tests et des tests d’intrusion
- Maitrise d'un outil d’intégration et de déploiement continu ainsi qu’un outil de provisionning
- Monitoring d’infrastructure et assurance d'un plan de reprise d’activité (DR) 
- Concepts de déploiement « canary releases » et vous les mettrez en pratique

### Parcours "gestionnaires de projet": direction de programme,chefs de projets, architectes d'entreprise...
Ce parcours s'adresse aux personnes qui pilotent les équipes de production du code applicatif. L'objectif est de comprendre les fondements, modes de travail et impacts d'une infrastructure DevSecOps sur une organisation de production. 
Description : Pilote des ressources de développement
Objectif : Disposer d’une offre claire, validée et résiliente d’un point de vue technique, permettant de limiter les risques

Niveau 1 : Fondamentaux/introduction au DevSecOps 
Dans ce niveau de maturité, vous apprenez les fondements du DevSecOps : 
- réaliser une étude de cas DevSecOps 
- les premiers éléments de la transformation organisationnelle et la façon de travailler qu’emmène le DevSecOps 
- les premiers éléments du pilotage par le test et les métriques et mesures indispensables au pilotage de projet en mode DevSecOps 
- les concepts d’une architecture à couplage faible, avec des composants facilement réutilisables et des logiciels facilement testables 
- à définir les features de votre backlog

Niveau 2 : Avancé/production en DevSecOps 
Dans ce niveau de maturité, vous apprenez comment travailler dans un cadre DevSecOps soit à  : 
- comprendre comment DevSecOps est guidé par des comportements tels que la collaboration et l'acceptation du changement. 
- concepts tels que l'infrastructure éphémère , qui met l'accent sur la construction rapide, puis la mise au rebut lorsque cette construction n'est plus nécessaire. 
- prioriser les features définies dans votre backlog 
- concevoir une application en utilisant l’offre DSO 
- Comment aller plus vite, utiliser l'automatisation et passer plus de temps à construire des fonctionnalités et moins de temps à déboguer lors des intégrations

Niveau 3 : Expert/organisation en DevSecOps 
Dans ce niveau de maturité, vous comprendrez l’impact du DevSecOps sur l’organisation, la création de valeur et sa mesure dans une persepctive d’amélioration  continue : 
- comment la production d'un produit minimum viable vous permet de tester une hypothèse et d'obtenir un retour d'information précieux sur la livraison de ce que le client désire vraiment. 
- définir une organisation optimale pour les équipes DevSecOps. Vous passerez en revue une variété de perspectives sur DevSecOps et explorerez les idées fausses sur DevSecOps 
- les principes de l’architecture en microservice 
- le concept Behavior Driven Development et saurez en appliquer le cadre 
 à prendre des décisions basées sur des métriques et données factuelles



### Parcours "décideurs": direction métiers, sponspors et commanditaires, responsables politiques...
Ce parcours d'adresse au personnes qui donnent mandat pour la production d'applicatifs et se portent garants des moyens et de l’engagement des organisations en ce sens. L'objectif est d'aligner une organisation DSO avec une feuille de route, des doctrines ou des orientations législatives pour réduire les risques à un niveau politique ou relations publiques.

Niveau 1 : Fondamentaux/introduction au DevSecOps 
Dans ce niveau de maturité, vous apprenez les fondements du DevSecOps : 
- réaliser une étude de cas DevSecOps 
- les premiers éléments de la transformation organisationnelle et la façon de travailler qu’emmène le DevSecOps 
- les premiers éléments du pilotage par le test et les métriques et mesures indispensables au pilotage de projet en mode DevSecOps 
- les concepts d’une architecture à couplage faible, avec des composants facilement réutilisables et des logiciels facilement testables 
- à définir les features de votre backlog

Niveau 2 : Avancé/production en DevSecOps 
Dans ce niveau de maturité, vous apprenez comment travailler dans un cadre DevSecOps soit à  : 
- comprendre comment DevSecOps est guidé par des comportements tels que la collaboration et l'acceptation du changement. 
- prioriser les features définies dans votre backlog 
- concevoir une application en utilisant l’offre DSO 
- Comment aller plus vite, utiliser l'automatisation et passer plus de temps à construire des fonctionnalités et moins de temps à déboguer lors des intégrations

Niveau 3 : Expert/organisation en DevSecOps 
Dans ce niveau de maturité, vous comprendrez l’impact du DevSecOps sur l’organisation, la création de valeur et sa mesure dans une persepctive d’amélioration  continue : 
- comment la production d'un produit minimum viable vous permet de tester une hypothèse et d'obtenir un retour d'information précieux sur la livraison de ce que le client désire vraiment. 
- définir une organisation optimale pour les équipes DevSecOps. Vous passerez en revue une variété de perspectives sur DevSecOps et explorerez les idées fausses sur DevSecOps 
- le concept Behavior Driven Development et saurez en appliquer le cadre 
- à prendre des décisions basées sur des métriques et données factuelles

