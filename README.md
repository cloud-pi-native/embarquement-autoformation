Les ressources rassemblées ici constituent une base de connaissances permettre aux équipes clientes d'acquérir rapidement un maximum d'autonomie sur [l'offre "Cloud Pi Native"](https://dnum-mi.github.io/). Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository
- Faisant des issues

# Ressources mises à disposition dans cette section

## Quels accélérateurs?
Les "clients" souhaitant comprendre et consommer l’offre Cloud Pi Native, pourront bénéficier d'accélérateurs:
- **Des ressources d'autoformation** organisées par [niveau de maturité](./plan-formation) (i.e. type de questions); 
- **De l'accompagnement (réservé aux clients ministériels)** organisé par [étapes](./accompagnement.md) (embarquement) ;

Hypothèse 1: l'alignement des `niveaux de maturité` des ressources proposées et des `étapes d'embarquement` rend l'offre de formation plus intelligible ce qui facilite sa prise en main.

Hypothèse 2: le type de parcours et de ressources proposés correspond au type de responsabilités des utilisateurs. On distingue:
> - **Sur le numérique et les enjeux de transformation:** à destination de tous, notamment aux personnes responsables du choix de l'offre de service pour un portefeuille de projets numériques `(décisionnaires/gouvernance)`;
> - **Sur le "cloud native", les technologies et approches promues par ce nouveau paradigme:** destinée en particulier aux personnes responsables de la structuration du plan projet et son suivi`(pilotage/MOE)`;
> - **Spécifiques à Cloud Pi Native:** documentation de l'offre destinée aux équipes techniques qui l'utilisent pour leur produits/systèmes `("techniques"/produits et systèmes)`.


## Comment utiliser ces ressources?

Les ressources peuvent etre utilisées de deux manières:
1) **Pour embarquer rapidement une équipe projet:** sélection des ressources essentielles pour compléter l'étape ;
2) **Pour se former individuellement:** parcours adaptés au niveau de maturité et au périmètre de responsabilité. 


![alt_text](images/accompagnement.jpg)




# Embarquer rapidement une équipe: ressources essentielles et étapes

## A qui s'adresser?
Le dispositif d'accompagnement proposé par le programme Cloud Pi Native est animé par deux équipes :
- `L'équipe "adoption"` qui, dans les 3 premières étapes, renseigne sur l'offre et oriente sur les ressources de formation; 
- `La "service team"` qui accompagne au lancement du projet à partir de l'étape 3 (réservée aux clients ministériels). 
L'effort étant plus important, `**à partir de l'étape 3, l'accompagnement est conditionné à la vérification de prérequis techniques stricts**`, car nécessaires à la réussite du projet (cf. [liste des prérequis](https://github.com/cloud-pi-native/documentation)).


### Etape 1: juger de l'opportunité de l'offre Cloud Pi Native, argumenter son besoin

>**Objectif et étapes clefs**: L'équipe sait évaluer et argumenter la pertinence (ou non) à orienter son projet vers l'offre Cloud Pi Native
>- Solliciter le programme Cloud Pi Native
>- Prendre connaissance des éléments nécessaires à la compréhension de l'offre ([support de sensibilisation aux enjeux](./sensibilisation.md), [page de présentation](https://dnum-mi.github.io/), [CCT Cloud Native](./cloud-pi-native/CCT-Cloud-Native)...)
>- Compléter le diagnostic flash permettant de préqualifier son besoin (en autonomie ou dans le cadre d'un entretien)

>**Livrable**: ["diagnostic flash" (préqualification)](./diagnostic-prequalification.md)

>**Critères go/no go:** l'offre de service est pertinente pour le besoin exprimé
<details>
 
 <summary> Ressources essentielles </summary>
  
- Enjeux du "nouveau monde logiciel" (Cloud, DevOps, mode produit,...) pour la transformations du numérique public
- L'impact du Cloud Native: technologies, méthodes, mode d'organisation...
- Comprendre la valeur apportée par l'offre Cloud Pi Native
 
[Voir les contenus d'autoformation pour l'étape 1](./sensibilisation.md)
 
</details>


### Etape 2: structurer un plan projet, se préparer pour consommer l'offre

>**Objectif et étapes clefs**: L'équipe sait à quoi l'engage le respect des normes du CCT Cloud Native et s'organise pour consommer l'offre
>- Procéder au "maturity check" (voir section correspondante dans le [modèle de plan projet](./modele_plan_projet.md) et les [exemples existants](https://software.af.mil/wp-content/uploads/2019/12/DoD-Enterprise-DevSecOps-Maturity-Review-v1.6.docx)) pour évaluer le degré de préparation de son projet: vérification des prérequis organisationnels (compétences, roles, ...) et techniques (complexité, technologies, ...), compréhension du cadre de normes, évaluation des éventuels besoins de formation...
>- Consulter les ressources d'autoformation mise à disposition (voir sections correspondantes dans le [plan de formation](./plan_formation.md))
>- Completer, autant que possible, le draft de plan projet
</details>
 
>**Livrable:** [plan projet](./modele_plan_projet.md)

>**Critères go/no go:** le projet/l'équipe sont suffisamment prets pour programmer un entretien avec les équipes d'accompagnement technique 
<details>
 <summary> Ressources essentielles </summary>
  
- Comprendre comment les grands acteurs du numériques ont tirés parti des nouvelles opportunités (cloud, kubernetes, DevSecOps,...)
- Comprendre les concepts technologiques de conteneurisation et d'orchestration (kubernetes)
- Comprendre les différents services de l'offre Cloud Pi Native et leur interet à chaque étape du cycle de vie d'un produit
 
[Voir les contenus d'autoformation pour l'étape 2](./formation_step2.md)
 
</details>

### Etape3: lancer son projet, construire dans un environnement sandbox "Cloud native"
>**Objectif et étapes clefs**: L'équipe s'est organisée et exercée à prendre en main des technologies cloud native. Elle a ensuite réalisé un "Hello world" avec les éléments de l'offre, puis mis en place son usine logicielle dans un environnement bac à sable pour construire sont projet (découverte et mise en place de la chaine primaire).

>- Entretien avec l'équipe d'accompagnement technique: passage en revue des prerequis, prise de connaissance des contexte métier et technique, évaluation des ressources à provisionner,... détermination d'une roadmap d'accompagnement
>- Demandes d'ouverture des accès à la console Cloud Pi Native ([formulaire Démarches Simplifiées](https://www.demarches-simplifiees.fr/commencer/cloud-pi-native)) (valant engagement à respecter le cadre de normes) et des canaux d'aides
>- Prise en main de l'offre: réalisation d'un "hello world", construction de son usine logicielle, déploiement d'un POC déployé dans l'environnement "bac à sable", construction d'un MVP du produit

>**Livrable:** MVP dans l'environnement bac à sable (console + SecNumCloud)

>**Critères go/no go:** les tests réalisés sur une version suffisemment représentative du produit attestent que le cadre de normes est respecté
<details>
 <summary> Ressources essentielles </summary>
  
- Mesurer l'impact de ces nouvelles opportunités sur la production logicielle: usines logicielles, organisations agiles, périmètres de responsabilités...
- Monter une équipe produit et élaborer un plan de formation pour utiliser les outils Cloud Native
- Lancer un projet dans Cloud Pi Native, du "hello world" (chaine primaire) jusqu'au MVP

 [Voir les contenus d'autoformation pour l'étape3](./formation_step3.md)
  
</details>

### Etape 4: passer en production, appréhender le Cloud souverain "Pi"
>**Objectif et étapes clefs**: L'équipe construit son projet et le déploie dans l'environnement du Cloud Pi souverain, dans le respect du cadre de normes imposé (découverte et mise en place de la chaine secondaire).

>- Réaliser une [demande d'hébergement sur le Cloud Pi](https://resana.numerique.gouv.fr/public/document/consulter/7054535)
>- Provisionner ses ressources, accéder à l'usine logicielle et les déployer sur le Cloud Pi
>- Déployer son produit (codes infra et applicatif) sur l'environnement de production

>**Livrable:** produit dans l'environnement de production

>**Critères go/no go:** les métriques d'observabilité et les rapports sur le produit attestent de sa conformité aux standards de qualité et de sécurité
<details>
 <summary> Ressources essentielles </summary>
  
- Assurer la sécurité et la qualité dans "le nouveau monde logiciel" (zéro-trust)
- Concevoir un produit Clodu Native et gérer son cycle de vie de A à Z (sécurité k8s)
- Contruire un projet avec Cloud Pi Native: exigences/CCT, sécurité, ... jusqu'à la production (chaine secondaire)

 [Voir les contenus d'autoformation pour l'étape 4](./formation_step4.md)
 
</details>


### Etape 5: atteindre les meilleurs standards, évoluer en production 
>**Objectif et étapes clefs**: L'équipe construit, opére et fait évoluer ses produits en autonomie. Les produits livrés en production sont conformes aux meilleurs standards de qualité et de sécurité. Elle a mis en place des bonnes pratiques et les monitore pour s'assurer de leur continuité.

>- Mettre en place les bonnes pratiques et les moyens de leur suivi
>- Assurer la continuité de service et des bonnes pratiques lors des évolutions du produit 
<details>
 <summary> Ressources essentielles </summary>
  
- Manager pour rester autonome et performant sur la durée (anti-patterns, mode produit, cloud-agile...)
- Utiliser les technologies du CNCF Landscape et les charts Helms / Operators
- Assurer la disponibilité et la continuité en production, garder les options ouvertes sur les transitions futures
  
[Voir les contenus d'autoformation pour l'étape 5](./formation_step5.md)
  
</details>


# Se former individuellement: périmètres de responsabilité et parcours

Toute personne désireuse de se former à titre individuel est priée de prendre connaissance du [support de sensibilisation aux enjeux](./0-sensibilisation.md), point de départ du plan de formation, communs aux différents parcours. 

Passée l'étape de sensibilisation (commune à tous), des parcours de formation ont été structurés en [**niveau de "maturité"**](./plan-formation.md) par périmètre de responsabilité. Les ressources adressent la maitrise de connaissances et de pratiques de 3 types:
1) [**"Culture générale"**](./parcours-culture-generale.md) : adressées à tous, notamment aux personnes responsables de l'orientation de projets numériques vers une offre  de service donnée pour comprendre les spécificités du "nouveau monde logiciel". On les regroupe sous le titre `gouvernance/décisionnaire`: elles sont responsables de la pertinence des décisions stratégiques ce qui recouvre, plus largement, les personnes chargées de les conseiller: pilotage et gouvernance des organisations, directions générales ou métiers, stratégie d'achat, RH, etc.

2) [**"Culture cloud native"**](./parcours-culture-cloudnative.md): notamment destinées aux personnes responsables de la structuration d'un plan projet (compétences, roles, organisation, technologies, ..) et son suivi (consommation budgetaire, UO, librables, ...), pour saisir les opportunités des technologies "cloud native". On les regroupe sous le titre de `Pilotage MOE` : personnes qui pilotent des équipes assurant le développement ou les opérations sur les produits. Elles sont responsables de l'intégrité des projets (cadrage, bonne utilisation et suivi des ressources, orientations techniques...): pilotage/chefferie de projets/programmes, responsables d'unités de conception, de bureaux d'étude, etc.

3) [**"A MODIFIER Spécifiques à Cloud pi native"**](https://github.com/cloud-pi-native/documentation): destinées aux équipes techniques responsables de l'utilisation de l'offre pour construire, opérer et gérer des produits tout au long de leur cycle de vie. C'est la documentation destinée aux `équipes produit` qui élaborent de nouveaux produits numériques et/ou assurent la gestion tout au long du cycle de vie. Elles sont responsables de la qualité des produits. Selon la taille et le d'organisation, ce périmètre peut recouvrir des personnes responsables de la `fiabilité des services & systèmes` (plateformes de services, pipelines de livraison DevSecOps, services d’hébergement, environnements, réseaux, etc.).
4) 
Les équipes d'accompagnement du programme programme Cloud Pi Native peuvent aussi conseiller des **parcours de formation spécifiques** en fonction des besoins et de la maturité de l'équipe projet.


