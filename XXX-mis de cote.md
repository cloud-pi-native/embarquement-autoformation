# Trame de préqualification d'un besoin

## Contexte de la demande
- Organisation de rattachement et application concernée (ministérielle? interministérielle?...)
- Type de projet et objectif visé? (développement d'une nouvelle application, migration d'une application déja en production, refonte, évolution, expérimentation ...)
- Quel est votre besoin actuel? 

## Cadre contractuel
- L'application concerné fait-elle déja l'objet d'un financement?
- Dans la négative, avez vous connaissance des sources de financement disponibles? Exemple: https://www.numerique.gouv.fr/services/guichet-financement-ftap-adoption-du-cloud-computing/
- Le porteur/sponsor/décideur/financeur est-il au courant de votre demande ? 
- Une équipe technique et des ressources sont elles dédiée à date? ou à terme?

## Elements de l'offre ayant retenu votre interet
- Comment avez vous eu connaissance de l'offre Cloud Pi Native et quelle en est votre compréhension actuelle? https://dnum-mi.github.io/
- Avez vous déja pris connaissance de ce que contient l'offre et des conditions pour bénéficier d'un accompagnement technique? https://github.com/cloud-pi-native/documentation
- Avez vous pris connaissance des éléments généraux contenus dans le cadre de cohérence technique (CCT Cloud native)? https://github.com/cloud-pi-native/cct-cloud-native

## Elements facultatifs (qui seront passé en revue lors de la qualification)
- Le cas échéant, par quels composants et services seriez-vous interessés?
- Quels sont les jalons et les deadlines associées? 
- Qui seront les interlocuteurs et quelles sont leurs responsabilités par rapport à l'objectif visé?


# Trame de qualification du plan projet

## Contexte métier de la demande
- Quelles missions et usage sont couverts par votre demande? (contexte métier, cas d'usage, fonctionnalités clef, criticité, ...)
- Le parcours d'accompagnment vous semble t-il compatible avec votre calendrier, impératifs, deadlines,  roadmap?

## Préparation de l'équipe
- Le modèle de responsabilité, les exigences, l'architecture... vous semblent-elles claires?
- L'accompagnement proposé par le programme Cloud Pi Native vous semble t-il clair? (nous en faisons pas "à la place de", mais accompagnons à faire)
- Les compétences, roles, processus... à mettre en place vous semble t-il clair?
- Y a t-il des sujets sur lesquels vous aurez des besoins de formation?
- Comment évaluriez vous la préparation de vos équipes? [exemples existants](https://software.af.mil/wp-content/uploads/2019/12/DoD-Enterprise-DevSecOps-Maturity-Review-v1.6.docx)

## Contexte technique du projet
- Les SI et applicatifs concernés sont-ils déja homologués? sur quel infrastructure? qu'est ce qui a déja été audité?
- Disposer vous de métriques caractérisant le périmètre concerné? (nombre de modules, de VM, dépendances, ...)
- Avous déja réalisé une estimation des ressources CPus, RAM, stockage... à provisionner? 
- Quels services auront-ils besoin de consommer?
- Disposer vus d'élément décrivant l'architecture actuelle? et l'architecture cible? 

## Fonctionnement de Cloud Pi Native 
- Le fonctionnement de la chaine de service vous semble t-il clair? (automatisation du lien entre la chaine primaire et secondaire : qu’est ce qui déclenche ? comment ça déploit ?)
- Cette séquence, la façon dont tout cela est chainées, vous semblet-il compatible avec les standards de votre organisation?
- le cas échéant, par quels composants et service seriez-vous interessés?
- Quels sont les jalons et les deadlines associées? 
- Qui seront les interlocuteurs et quelles sont leurs responsabilités par rapport à l'objectif visé?
- Le cas échéant sur quels sujets/composants souhaiteriez vous contribuer ? 

# En construction
- Intégrer les questions posé dans le cadre de l'examen d'une demande d'hébergement
- Matrice d'éligiblité type de projet/type d'hébergement (cf. CRiP, EDF, etc.)



# Pourquoi Cloud Pi Native? enjeux de transformation du numérique public
### Un "nouveau monde" logiciel a émergé
Ces 10 dernières années la puissance d'intermédiation du numérique a capté/dévoré une part croissante des activités humaines. Transport, banque, finance, sociabilité, hotellerie, logistique, sécurité, identité, culture, divertissement... deviennent numériques.  Les causes d'un tel changement ne sont pas seulement technologiques: elles ont trait aux organisations, responsabilités, normes (y compris culturelles) de la production numérique. C'est un changement de paradigme complet, un ["nouveau monde logiciel"](https://pi.interieur.rie.gouv.fr/nouveau-monde-logiciel/).

### Le service public est mis au défi
Dans ce nouveau cadre, certains produits/services deviennent des « normes de fait »: les décisions les concernant, leurs caractéristiques, impactent des millions d'utilisateurs ce qui pose des [défis importants aux organisations publiques](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.3-defis_service_public.md). Pour rester au service de leurs usagers et agents, en particulier sur leurs missions régaliennes, ces dernières doivent s'approprier les moyens techniques, organisationnels (production, opération, maintenance, ...) et les normes techniques ou non-techniques (neutralité, RGPD, accessibilité,...) du "nouveau monde" numérique. C'est à ces défis que visent à répondre les doctrines [cloud au centre de l'Etat](https://www-lemagit-fr.cdn.ampproject.org/c/s/www.lemagit.fr/actualites/365531732/Cloud-souverain-la-DINUM-contextualise-les-exigences-de-la-France?amp=1) et [cloud de confiance](https://www.ssi.gouv.fr/actualite/secnumcloud-evolue-et-passe-a-lheure-du-rgpd/).

### Remettre "l'usager au centre"
Pour réussir un projet de transformation au service des usagers, la production du numérique public doit être organisée ["en mode produit"](https://6695516.fs1.hubspotusercontent-na1.net/hubfs/6695516/Culture_Produit_Web_Extrait.pdf?__hstc=154216807.d3e24310b08a19eb0fbdb060971025e2.1671555363753.1671555363753.1675700990863.2&__hssc=154216807.2.1675700990863&__hsfp=1771427427&hsCtaTracking=3562120f-8ddc-4973-8c94-6fc9bd6753e2%7C5eb7f077-d1f7-422e-9a12-ab4e2311abe6) (évolutivité, disponibilité) en incluant les développeurs, usagers trop souvent oubliés. La voie que nous privilégions pour cela emprunte aux technologies ["cloud native"](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.2-technologies-cloud-native.md) (conteneurisation/orchestration, API, microservices) et aux approches [DevSecOps](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.1-approche_devsecops.md) (culture de responsabilités partagées). 


Comme expliqué dans le [cadre de cohérence technique Cloud Native (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native), l'offre Cloud Pi Native vise à "industrialiser" cette approche et l'implémenter dans un flux de production continue, intégré et optimisé (lean), suffisament ouvert pour pouvoir évoluer en continu (agile). Cloud Pi Native constitue donc un modèle-socle d'usine logicielle "lean-agile". 


# Compréhension de Cloud Pi Native
Nous souhaitons faciliter l'action de l'ensemble des acteurs désireux de contribuer à la transformation numérique du service public. Pour cela, nous répondons aux questions 1) quels sont les principes directeurs et modèles d'organisations nécessaires à l'utilisation du socle ? 2) Quels sont les prérequis théoriques (concepts) et pratiques pour l'utiliser? 3) Quel est le degré de préparation de mon équipe?

### Présentation de l'écosystème et socle technique "Cloud Native"
Comme dans toute transformation industrielle découlant d'innovation(s) majeure(s), les responsabilités des acteurs en place sont profondément modifiées. nous proposons un [modèle opérationnel](https://github.com/Yoarmi/dso-formation/blob/patch-1/2-modele_organisation.md) pour comprendre l'articulation des différents périmètres de responsabilité et tirer pleinement parti du socle cloud Pi native. 

Nous vous invitons à prendre connaissance des principes sous-jacents exposés dans le [cadre de cohérence technique Cloud Pi Native (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native) et à y contribuer. De ces principes découleront les exigences technologiques, organisationnelles, bonnes pratiques, processus... préconisés pour livrer des produits numériques à l'état de l'art et les gérer tout au long de leur cycle de vie.



### Apprentissage tout au long du cyle de vie du projet  
Avant de se lancer, un "diagnostic" est nécessaire pour définir les formations et l'accompagnement approprié. Nous proposons des outils pour permettre à l'équipe utilisatrice de se situer en termes de connaissances, de compétences et d'appropriation des outils pour tendre vers le plus d'autonomie possible. Cela passe par un dispositif d'accompagnement tout au long du cycle de vie du projet et à la mise en place d'un plan de formation.
 
 
# Prise en main de Cloud Pi Native
Nous pensons que toute personne désireuse de contribuer à la transformation numérique du service public (agent, citoyen, industriel du numérique, représentant d'institutions publiques... ) doit pouvoir rapidement tester le socle et se familliariser avec son utilisation. Pour cela, nous mettons à disposition les souches logicielles et la documentation du socle, mais également des kits de démarrage: tutoriels, formations "hands-on" (par la pratique) et bacs à sable (sandbox). 

### Contextes d'utilisation de Cloud Pi Native
- **Acteurs ministériels ("internes")**: à terme, l'offre Cloud Pi Native sera consommable avec le maximum d'autonomie depuis le réseau interministériel d'Etat via le [catalogue de services](https://pi.interieur.rie.gouv.fr/home-dnum/cloud-%cf%80/qui-sommes-nous/cloud-native/). Pour l'heure, elle est en co-construction en agilité avec ses partenaires-clients et le code du socle est disponible en open-source.
- **Autres utilisateurs ("externes")**: à date, l’offre est mise à disposition en open source pour favoriser l'appropriation des technologies « Cloud Native » et l’émergence de standards du numérique public interopérables avec la production externalisée. Les partenaires industriels et contributeurs open source portées par une ambition d'innovation et de transformation du service public sont libres de les consulter et proposer leurs retours.
- **Utilisation en expérimentation ("partenaires")**: que vous soyez acteur du service public, industriel ou contributeur de l'Open Source, vous pouvez nous faire part de vos propositions/demandes d'expérimentation via l'adresse cloudpinative-relations@interieur.gouv.fr. Nos équipes accompagnent exclusivement des expérimentations à but non-lucratif: elles n'examineront et ne répondront à AUCUNE sollicitation commerciale.

L'accompagnement est conditionné à un certains nombre de prérequis, au premeir rang desquels la nécessité d'avoir consulté et suivi les tutoriels mis à disposition.

### Documentation et tutoriels
Afin de tirer le meilleur parti des guides, kit, et outils proposés, nous conseillons de s'être préalablement familiarisé avec les concepts présentés dans les parcours de formation. Ceci afin de permettre la prise en main des composantes de l'offre avec tout l'autonomie possible: 
- [Prise en main du socle technique](https://github.com/dnum-mi/dso-socle);
- [Prise en main de la console](https://github.com/dnum-mi/dso-console);
- [Tutoriel pour le GitOps](https://github.com/dnum-mi/gitops-tutorial).


# Le "nouveau monde logiciel": un défi technologique, organisationnel et culturel

Les tendances globales du monde contemporain sont devenues extrèmement difficiles à appréhender. C'est le concept "VUCA": Volatil (les choses changent vite), Complex (en raison de la multiplicité des crises: économique, sanitaire, climatique), Uncertain (intéractions entre toutes ces crises) et Ambiguous (du fait de la complexité et de l’incertitude). 
https://en.wikipedia.org/wiki/Volatility,_uncertainty,_complexity_and_ambiguity 

La révolution numérique en cours accélère les transformations du monde en redéfinissant des secteurs d'activités entiers (information, banque, assurance, hotellerie, service de voyage, taxi, sociabilité, ...) au point de "dévorer le monde". 
Marc Andreessen, 2011, "Why software is eating the world", https://www.wsj.com/articles/SB10001424053111903480904576512250915629460


# Emergence d'un nouveau paradigme logiciel
De cette expension rapide, un nouveau paradigme logiciel a émergé. Né de l'Open Source et propulsé par les GAFA, il permet de mettre à disposition rapidement, à l'échelle, des produits de haute qualité, de facon résiliente. Ce "nouveau monde logiciel" est défini par 3 ruptures: 
- Une rupture technologique: l'automatisation grandissante de la gestion des ressources informatiques et des réseaux ont rendu incontournable la maitrise du cloud et des technologies associés  dites "cloud native" (conteneurs, API, microservices, kubernetes...)
- Une rupture dans les modes d'organisation et les pratiques de production: le travail des développeurs (Dev) et des opérateurs (Ops) a évolué. De leur collaboration, devenue indispensable, sont nées de nouvelles approches de production (DevOps/DevSecOps)
- Une rupture culturelle: les attentes des consommateurs ont évolué (simplicité et ergonomie maximale, pas de mode d'emploi), les producteurs sont obsédés par le « zéro distance » avec le besoin utilisateur et le produit est placé au centre ("mode produit": feedback régulier, co-construction et évolution en continu)

# Remettre l'usager au centre
Afin de remettre l'usager au centre, le service public cherche à maitriser ces ruptures. L'objectif poursuivi a travers la présente initiative est double 1) définir une voie d'accès privilégiée permettant d'appréhender la complexité de ce "nouveau monde" (Lean - Startup - Agile) 2) Construire et mettre à disposition le plus largement possible des "kits" permettant d'outiller une telle approche, tout en cultivant la Tech et ceux qui la font (tenir le rythme de l'évolution technologique).

# Les origines de l'offre Cloud Pi Native
- le numérique au coeur des politiques publique ( LOPMI )
- Besoin de transformation majeur de la culture  « penser numérique »
- Des cycles de production long & friction, qualités se dégradant dans le temps
- Besoin accru de sécurité, d’élasticité et de réactivité 
- La croissance vs coût/impact environnemental non soutenable
- Absence d’un système de normes commun à l’innovation et au développement de grosses solutions. (impossibilité de croître)
- Les développeurs, usagers « oubliés » de l’écosystème
- Difficultés et perspectives des acteurs SIC dont la formation n’a pas évoluée


# Fondamentaux et bonnes pratiques dans le nouveau monde logicel: l'approche DevSecOps
Le DevSecOps est une approche recouvrant des dimensions techniques (outils d'automatisation, infrastructures, plateformes,...) et organisationelles (roles, compétences, pratiques, ...) pour développer une culture de responsabilité partagé entre le développement, la sécurité et l'exploitation. https://www.youtube.com/watch?v=nrhxNNH5lt0

Le DevSecOps est un cycle dont les étapes peuvent être décomposées selon: 
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

Historiquement, il s'agissait d'intégrer le développement et l'exploitation mais toute responsabilité partagée (au premier chef la sécurité) a vocation à être intégrée. L'origine et la signification de l'approcheDevOps est à ce titre instructive.
https://publication.octo.com/fr/telechargement-livre-blanc-decouverte-devops

# Pour la majeure partie des transformations numériques échouent
https://www.hbrfrance.fr/chroniques-experts/2022/09/48917-voici-pourquoi-la-majeure-partie-des-transformations-numeriques-echouent/ 


# Parcours "qualité des produits numériques" 
Ce parcours s'adresse aux personnes qui élaborent de nouveaux produits numériques et/ou assurent la gestion de leur cycle de vie. Ils sont responsables de leur développement, mise en production, MCO/évolution.... du code applicatif. Ce sont les développeurs ou opérateurs de produits, les architectes produit, … 

L'objectif est de leur permettre de s'appuyer sur la chaine DevSecOps de l'offre Cloud Pi Native pour disposer d'outils d'intégration et de déploiement avec un niveau de qualité au standard/à l’état de l’art.

## Niveau 1 : Fondamentaux/adoption des pratiques : 
Dans ce niveau de maturité, vous apprenez les pratiques de bases qu’un développeur doit avoir pour utiliser l’offre Cloud Pi Native :
- A exprimer des epics en collaboration avec les métiers
- A bien gérer vos projets en maîtrisant un outil de collaboration et de développement logiciel, et un outil de versionning
- A faire des tests d’intégration lors de vos builds, des tests d’acceptance lors de vos déploiements, et de l’analyse dynamique de code dans vos environnements de production
- A maîtriser un outil de gestion de configuration pour faciliter vos déploiements
- Les bases du monitoring (gestion basique des logs)
- Les bonnes pratiques de la mise en service (feature toggles)

## Niveau 2: Avancé/ maitriser la qualité jusqu'à la livraison
Dans ce niveau de maturité, l'objectif est la matrise du niveau de qualité du code de bout en en bout. Pour cela vous apprendrez :
- La conception d’une application en utilisant l’offre Cloud Pi Native
- A aller plus loin dans les tests du cycle de vie d’un logiciel (tests unitaires, tests fonctionnels, tests de performance)
- A maîtriser la conteneurisation et son orchestration
- A déployer vos codes applicatifs dans des environnements de tests
- A monitorer vos applications et à assurer de la haute disponibilité
- Les concepts de déploiement « blue/green » et les mettrez en pratique

## Niveau 3 : Expert/ Être autonome sur la chaine DevSescOps 
Dans ce niveau de maturité, vous montez en autonomie sur l’utilisation de l'offre Cloud Pi Native et apprenez :
- Les concepts de l’architecture d’une application basé sur Cloud Pi Native
- A automatiser vos différents tests
- A faire du développement piloté par les tests, des tests de non regression, des smoke tests et des tests d’intrusion
- A maîtriser un outil d’intégration et de déploiement continu ainsi qu’un outil de provisionning
- A faire du monitoring d’infrastructure et d’assurer un plan de reprise d’activité (DR) 
- Les concepts de déploiement « canary releases » et vous les mettrez en pratique


# Parcours "fiabilité des services & systèmes (SRE)"
Ce parcours d'adresse aux personnes qui assurent l’intégrité des services et systèmes nécessaires aux équipes responsables des produits numériques, tout au long de leur cycle de vie: pipelines de livraison DevSecOps, services d’hébergement, génération d’environnements, etc. Ce sont les system teams, les équipes d’ingénierie de fiabilité des sites (SRE, Site Reliability Engineering), les forges, les opérateurs de plateformes (IaaS, PaaS, XaaS, ...).

L'objectif est de s’assurer de l'intégrité de la plateforme Cloud Pi Native, afin que les services de l'offre puissent être utilisés par les consommateurs (équipes produit) de facon fiable et sécurisée.

## Niveau 1 : Fondamentaux/garantir les environnements de développement : 
Dans ce niveau de maturité, vous apprenez les pratiques de bases qu’un SRE doit maîtriser pour le bon développement des fonctionnalités par les équipes produit via la maitrise des environnements de développement :
- Les premiers éléments de l’architecture microservices
- Introduction aux différents outils nécessaires pour remplir vos fonctions: versionning, gestion d’images, outils collaboratifs, etc.
- Réalisation de tests d’acceptance et d’intégration
- Bases du monitoring (gestion basique des logs)
- Bonnes pratiques de la mise en service (feature toggles) 

## Niveau 2: Avancé/garantir la livraison de versions stables et sécurisées
Dans ce niveau de maturité, vous apprenez à garantir la stabilité et la sécurité des livraisons de code applicatifs sur la plateforme Cloud Pi Native. Pour cela vous apprendrez :
- La conception d’une application en utilisant l’offre Cloud Pi Native
- La maîtrise de la conteneurisation 
- Le déployement de codes applicatifs dans des environnements de tests 
- Le monitoring d'applications et assurance de la haute disponibilité
- Les concepts de déploiement « blue/green » et mise en pratique
- La garantie du bon fonctionnement et la haute disponibilité de la plateforme 
- La réalisation de tests de performance sur la plateforme 

## Niveau 3 : Expert/Garantir une continuité de production sur toute la chaine d’intégration et de déploiement
Dans ce niveau de maturité, vous apprenez à être autonome pour accompagner les équipes projet à la compréhension et à l'utilisation de l’offre de service, ainsi que pour mettre en oeuvre l'ensemble des bonnes pratiques:
- Les concepts de l’architecture d’une application basé sur Cloud Pi Native
- L'automatisation de vos différents tests
- Le développement piloté par les tests (TDD), des tests de non regression, des smoke tests et des tests d’intrusion
- La maitrise d'un outil d’intégration et de déploiement continu ainsi qu’un outil de provisionning
- Le monitoring d’infrastructure et assurance d'un plan de reprise d’activité (DR) 
- Les concepts de déploiement « canary releases » et vous les mettrez en pratique


# Parcours "intégrité des projets"
Ce parcours s'adresse aux personnes responsables de l'intégrité d'un projet: cadrage des projets, approvisionnement des ressources (humaines et techniques), sollicitation des sponsors et appuis stratégique, respect des méthodes et du cadre de travail, gestion contractuelle et budgétaire, obtention et mise en oeuvre des financements... inhérente à la menée d'un projet. Il s'agit du pilotage/chefferie de projets/programmes, de MOE ou d'unités de réalisation, bureau d'étude, etc.

L'objectif est de comprendre les fondements, les modes de travail et les impacts de l'offre Cloud Pi Native sur l'organisation de production logicielle en disposant d’une offre claire, validée et résiliente d’un point de vue technique, afin de limiter les risques de niveau projet.

## Niveau 1 : Fondamentaux/introduction au DevSecOps 
Dans ce niveau, vous apprenez les principes sous-jacents à l'offre Cloud Pi Native : 
- Réaliser une étude de cas DevSecOps 
- Les premiers éléments de la transformation organisationnelle et la façon de travailler qu’emmène le DevSecOps 
- Les premiers éléments du pilotage par le test et les métriques et mesures indispensables au pilotage de projet en mode DevSecOps 
- Les concepts d’une architecture à couplage faible, avec des composants facilement réutilisables et des logiciels facilement testables 
- A définir les features de votre backlog

## Niveau 2 : Avancé/production en DevSecOps 
Dans ce niveau de maturité, vous apprenez comment travailler dans le modèle opérationnel de l'offre Cloud Pi Native soit à  : 
- Comprendre comment DevSecOps est guidé par des comportements tels que la collaboration et l'acceptation du changement
- Des concepts tels que l'infrastructure éphémère , qui met l'accent sur la construction rapide, puis la mise au rebut lorsque cette construction n'est plus nécessaire
- A prioriser les features définies dans votre backlog 
- A concevoir une application en utilisant l’offre Cloud Pi Native 
- Comment aller plus vite, utiliser l'automatisation et passer plus de temps à construire des fonctionnalités et moins de temps à déboguer lors des intégrations

## Niveau 3 : Expert/organisation en DevSecOps 
Dans ce niveau de maturité, vous comprennez l’impact de l'utilisation des outils et du modèle opérationnel de Cloud Pi Native sur l’organisation, la création de valeur et sa mesure dans une persepctive d’amélioration  continue : 
- Comment la production d'un produit minimum viable vous permet de tester une hypothèse et d'obtenir un retour d'information précieux sur la livraison de ce que le client désire vraiment. 
- Définir une organisation optimale pour les équipes DevSecOps. Vous passerez en revue une variété de perspectives sur DevSecOps et explorerez les idées fausses sur DevSecOps 
- Les principes de l’architecture en microservice 
- Le concept de Behavior Driven Development et saurez en appliquer le cadre 
- A prendre des décisions basées sur des métriques et données les plus factuelles possibles




# Parcours "pertinence de la décision stratégique"
Ce parcours s'adresse aux personnes qui prennent des décisions, se portent garantes de l’engagement des organisations sur des sujets touchant au numérique. Ce périmètre comprend aussi les personnes chargées de les conseiller quand à la stratégie à adopter, de donner des recommandations, délivrer des mandats ou réaliser des arbitrages concernant les finalités, moyens et modes d’organisation. Il s’agit de la décision stratégique, du pilotage et de la gouvernance des organisations, des directions générales ou des directions de la stratégie métiers, achats, RH, etc.

L'objectif est d'aligner une organisation avec 1) le modèle opérationnel de Cloud Pi Native 2) une feuille de route, des doctrines ou des orientations législatives reltives au numérique public pour réduire les risques (au niveau politique ou relations publiques).

## Niveau 1 : Fondamentaux/introduction au DevSecOps 
Dans ce niveau de maturité, vous apprenez les fondements du modèle opérationnel de Cloud Pi Native : 
- Réaliser une étude de cas DevSecOps
- Les premiers éléments de la transformation organisationnelle et la façon de travailler qu’emmène le DevSecOps
- Les premiers éléments du pilotage par le test et les métriques et mesures indispensables au pilotage de projet en mode DevSecOps 
- Les concepts d’une architecture à couplage faible, avec des composants facilement réutilisables et des logiciels facilement testables 
- A définir les features de votre backlog

## Niveau 2 : Avancé/production en DevSecOps 
Dans ce niveau de maturité, vous apprenez comment travailler dans le cadre du modèle opérationnel proposé par Cloud Pi Native  : 
- Comprendre comment le DevSecOps est guidé par des comportements tels que la collaboration et l'acceptation du changement
- Prioriser les features définies dans votre backlog 
- Concevoir une application en utilisant l’offre DSO 
- Comment aller plus vite, utiliser l'automatisation et passer plus de temps à construire des fonctionnalités et moins de temps à déboguer lors des intégrations

## Niveau 3 : Expert/organisation en DevSecOps 
Dans ce niveau de maturité, vous comprennez l’impact du modèle opérationnel de Cloud Pi Native sur votre organisation, la création de valeur et sa mesure dans une perspective d’amélioration  continue : 
- Comment la production d'un produit minimum viable vous permet de tester une hypothèse et d'obtenir un retour d'information précieux sur la livraison de ce que le client désire vraiment. 
- Définir une organisation optimale pour les équipes DevSecOps. Vous passerez en revue une variété de perspectives sur DevSecOps et explorerez les idées fausses sur DevSecOps 
- Le concept de Behavior Driven Development et saurez en appliquer le cadre 
- A prendre des décisions basées sur des métriques et données les plus factuelles possibles


