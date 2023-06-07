Les ressources rassemblées ici constituent une base de connaissances permettre aux équipes clientes d'acquérir rapidement un maximum d'autonomie sur [l'offre "Cloud Pi Native"](https://dnum-mi.github.io/). Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository
- Faisant des issues



# Quels accélérateurs sont mis à disposition? 
Un équipe "cliente" souhaitant comprendre et utiliser l’offre Cloud Pi Native pourra bénéficier d'accélérateurs:
- Un accompagnement facilitant l'embarquement, adapté à l'avancement de son/ses projet(s): c'est à dire au type d'objectifs/réalisations visés (voir les besoins, interlocuteurs et réalisations aux différents [stades d'avancement](./2.5-accompagnement_projet.md)) ;
- Des ressources de formation adpatées à son degré de maturité: c'est à dire au type de questions qu'elle se pose. Ces ressources sont organisées en un [plan de formation](./2.6-plan_formation.md) et sont de 3 types:
> 1) Générales, sur le numérique et les enjeux de transformation 
> 2) Relatives aux technologies "cloud native" 
> 3) Spécifiques à l'offre Cloud Pi Native;

# A qui s'adresser ?

## Interlocuteurs coté programme Cloud Pi Native
Le dispositif d'accompagnement proposé par le programme Cloud Pi Native est animé par deux équipes :
- `L'équipe "adoption"` qui renseigne sur l'offre et oriente sur les ressources de formation disponibles; 
- `La "service team"` qui accompagne à la prise en main et à l'embarquement des projets sur le plan technique.

A l'étape "lancer mon projet", un basculement intervient: l'effort étant plus important, **l'accompagnement est conditionné à la vérification de prérequis techniques stricts**, car nécessaires à la réussite du projet (liste des prérequis est disponible dans la [documentation](https://github.com/dnum-mi/dso-documentation/blob/209e5ffc0c1b1d042c8de4e7e53fc07530325e66/README.md)).

## Interlocuteurs coté équipe cliente
Les interlocuteurs en responsabilité coté client peuvent être différents selon l'étape du projet : 
- `Gouvernance/décisionnaire` : personnes se portant garantes de l’engagement d'une organisation à orienter un projet/produit ou un portefeuille vers une offre de service. Elles sont responsables de la pertinence des décisions stratégiques ce qui recouvre, plus largement, les personnes chargées de les conseiller: pilotage et  gouvernance des organisations, directions générales ou métiers, stratégie d'achat, RH, etc.
- `Pilote MOE` : personnes qui pilotent des équipes assurant le développement ou les opérations sur les produits. Elles sont responsables de l'intégrité des projets (cadrage, bonne utilisation et suivi des ressources, orientations techniques...): pilotage/chefferie de projets/programmes, responsables d'unités de conception, de bureaux d'étude, etc.
- `Equipe produit` : personnes qui élaborent de nouveaux produits numériques et en assurent la gestion tout au long du cycle de vie. Elles sont responsables de la qualité des produits. Selon la taille et le d'organisation, ce périmètre peut recouvrir des personnes responsables de la `fiabilité des services & systèmes` (plateformes de services, pipelines de livraison DevSecOps, services d’hébergement, environnements, réseaux, etc.).


# Comment ca se passe? embarquement pas à pas 

![alt_text](images/accompagnement.jpg)

### Etape 1: juger de l'opportunité de l'offre Cloud Pi Native, argumenter son besoin

>**Objectif et étapes clefs**: L'équipe sait évaluer et argumenter la pertinence (ou non) à orienter son projet vers l'offre Cloud Pi Native
>- Solliciter le programme Cloud Pi Native
>- Prendre connaissance des éléments nécessaires à la compréhension de l'offre ([support de sensibilisation au enjeux](./0-sensibilisation.md), [page de présentation](https://dnum-mi.github.io/), [CCT Cloud Native](https://github.com/dnum-mi/CCT-Cloud-Native)...)
>- Compléter le diagnostic flash permettant de préqualifier son besoin (en autonomie ou dans le cadre d'un entretien)

>**Livrable**: Support de [préqualification/"diagnostic flash"](./Diagnostic_flash-prequalification.md) complété

>**Go/no go?**: L'offre de service est pertinente pour le besoin exprimé
<details>
 
 <summary> Compétences requises </summary>
  
- Culture générale: enjeux du "nouveau monde logiciel" (Cloud, DevOps, mode produit,...) pour la transformations du numérique public
- Culture Cloud Native: l'impact du Cloud Native: technologies, méthodes, mode d'organisation...
- Spécifique Cloud Pi Native: comprendre la valeur apportée par l'offre Cloud Pi Native
 
[Voir les contenus de formation correspondants](./0-sensibilisation.md)
 
</details>


### Etape 2: structurer un plan projet, se préparer pour consommer l'offre

>**Objectif et étapes clefs**: L'équipe sait à quoi l'engage le respect des normes du CCT Cloud Native et s'organise pour consommer l'offre
>- Procéder au "maturity check" (voir section correspondante dans le [modèle de plan projet](./modele_plan_projet.md) et les [exemples existants](https://software.af.mil/wp-content/uploads/2019/12/DoD-Enterprise-DevSecOps-Maturity-Review-v1.6.docx)) pour évaluer le degré de préparation de son projet: vérification des prérequis organisationnels (compétences, roles, ...) et techniques (complexité, technologies, ...), compréhension du cadre de normes, évaluation des éventuels besoins de formation...
>- Consulter les ressources d'autoformation mise à disposition (voir sections correspondantes dans le [plan de formation](./2.6-plan_formation.md))
>- Completer, autant que possible, le draft de plan projet et le formulaire de demande d'accès à la console (valant engagement à respecter le cadre de normes)
</details>
 
>**Livrable**: draft de [plan projet](./modele_plan_projet.md)

>**Go/no go?**: Le projet/l'équipe sont suffisamment prets pour programmer un entretien avec les équipes d'accompagnement technique 
<details>
 <summary> Compétences requises </summary>
  
- Culture générale: Comprendre comment les grands acteurs du numériques ont tirés parti des nouvelles opportunités (cloud, kubernetes, DevSecOps,...)
- Culture Cloud Native: Comprendre les concepts technologiques de conteneurisation et d'orchestration (kubernetes)
- Spécifique Cloud Pi Native: Comprendre les différents services de l'offre Cloud Pi Native et leur interet à chaque étape du cycle de vie d'un produit
 
[Voir les contenus de formation correspondants](./0-formation_step2.md)
 
</details>

### Etape3: lancer son projet, construire dans un environnement "Cloud native"
>**Objectif et étapes clefs**: L'équipe s'est organisée et exercée à prendre en main des technologies cloud native. Elle a ensuite réalisé un "Hello world" avec les éléments de l'offre, puis mis en place son usine logicielle dans un environnement bac à sable pour construire sont projet (découverte et mise en place de la chaine primaire).

>- Entretien avec l'équipe d'accompagnement technique: passage en revue des prerequis, prise de connaissance des contexte métier et technique, évaluation des ressources à provisionner,... détermination d'une roadmap d'accompagnement
>- Ouverture des canaux d'aides et des accès à la console Cloud Pi Native ([formulaire Démarches Simplifiées](https://www.demarches-simplifiees.fr/commencer/cloud-pi-native))
>- Prise en main de l'offre: réalisation d'un "hello world", construction de son usine logicielle, déploiement d'un POC déployé dans l'environnement "bac à sable", construction d'un MVP du produit

>**Livrable** MVP dans l'environnement bac à sable

>**Go/no go?** les tests réalisés sur une version suffisemment représentative du produit attestent que le cadre de normes est respecté
<details>
 <summary> Compétences requises </summary>
  
- Culture générale: Mesurer l'impact de ces nouvelles opportunités sur la production logicielle: usines logicielles, organisations agiles, périmètres de responsabilités...
- Culture Cloud Native: Monter une équipe produit et élaborer un plan de formation pour utiliser les outils Cloud Native
- Spécifique Cloud Pi Native: Lancer un projet dans Cloud Pi Native, du "hello world" (chaine primaire) jusqu'au MVP

 [Voir les contenus de formation correspondants](./0-formation_step3.md)
  
</details>

### Etape 4: passer en production, appréhender le Cloud souverain "Pi"
>**Objectif et étapes clefs**: L'équipe construit son projet et le déploie dans l'environnement du Cloud Pi souverain, dans le respect du cadre de normes imposé (découverte et mise en place de la chaine secondaire).

>- Réaliser une [demande d'hébergement sur le Cloud Pi](https://resana.numerique.gouv.fr/public/document/consulter/7054535)
>- Provisionner ses ressources, accéder à l'usine logicielle et les déployer sur le Cloud Pi
>- Déployer son produit (codes infra et applicatif) sur l'environnement de production

>**Livrable** Produit dans l'environnement de production

>**Go/no go?** Les métriques d'observabilité et les rapports sur le produit attestent de sa conformité aux standards de qualité et de sécurité
<details>
 <summary> Compétences requises </summary>
  
- Culture générale: Assurer la sécurité et la qualité dans "le nouveau monde logiciel" (zéro-trust)
- Culture Cloud Native: Concevoir un produit Clodu Native et gérer son cycle de vie de A à Z (sécurité k8s)
- Spécifique Cloud Pi Native: Contruire un projet avec Cloud Pi Native: exigences/CCT, sécurité, ... jusqu'à la production (chaine secondaire)

 [Voir les contenus de formation correspondants](./0-formation_step4.md)
 
</details>


### Etape 5: atteindre les meilleurs standards, évoluer en production 
>**Objectif et étapes clefs**: L'équipe construit, opére et fait évoluer ses produits en autonomie. Les produits livrés en production sont conformes aux meilleurs standards de qualité et de sécurité. Elle a mis en place des bonnes pratiques et les monitore pour s'assurer de leur continuité.

>- Mettre en place les bonnes pratiques et les moyens de leur suivi
>- Assurer la continuité de service et des bonnes pratiques lors des évolutions du produit 
<details>
 <summary> Compétences requises </summary>
  
- Culture générale: Manager pour rester autonome et performant sur la durée (anti-patterns, mode produit, cloud-agile...)
- Culture Cloud Native: Utiliser les technologies du CNCF Landscape et les charts Helms / Operators
- Spécifique Cloud Pi Native: Assurer la disponibilité et la continuité en production, garder les options ouvertes sur les transitions futures
  
[Voir les contenus de formation correspondants](./0-formation_step5.md)
  
</details>


 
# Comment et quand me former? parcours génériques
Toute personne désireuse est priée de prendre connaissance du [support de sensibilisation aux enjeux](./0-sensibilisation.md), point de départ du plan de formation, communs aux différents parcours. 

Par la suite, les ressources mises à disposition sont organisées en [**3 parcours génériques**](./2.6-plan_formation.md). L'objectif est de permettre aux équipes clientes d'acquérir rapidement un maximum d'autonomie sur des réalisations de complexité croissante. Le niveau de maturité requis augmente avec l'avancement du projet et recouvre la maitrise de connaissances et de pratiques: 

1) [**"Culture générale"**](https://github.com/dnum-mi/dso-formation/blob/main/parcours-culture-generale.md) : ressources adressées à tous, notamment aux personnes responsables de l'orientation de projets numériques vers une offre  de service donnée, pour comprendre les spécificités du "nouveau monde logiciel"; 
2) [**"Culture cloud native"**](https://github.com/dnum-mi/dso-formation/blob/main/parcours-culture-cloudnative.md): ressources notamment destinée aux personnes responsables de la structuration d'un projet, des équipes et leur compétences, définir les orientations techniques... pour saisir les opportunités des technologies "cloud native".
3) [**"Spécifiques Cloud pi native"**](https://github.com/dnum-mi/dso-documentation/blob/master/README.md): documentation notamment destinés aux équipes techniques qui utilisent l'offre pour construire, opérer et gérer des produits tout au long de leur cycle de vie.


![alt_text](images/schema-accompagnement-formation.png)
Les équipes d'accompagnement du programme programme Cloud Pi Native peuvent conseiller des **parcours de formation spécifiques** en fonction des besoins et de la maturité de l'équipe projet.


