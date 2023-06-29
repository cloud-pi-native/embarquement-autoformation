Les ressources rassemblées ici constituent une base de connaissances permettre aux équipes clientes d'acquérir rapidement un maximum d'autonomie sur l'offre cloud native portée par le Ministère de l'Intérieur s'appuyant un environnement du Cloud souverain Pi (offre "Cloud Pi Native"). Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository 
- Faisant des issues

# Que contient cette section?
**Un parcours de prise en main "pas à pas"**, destiné aux personnes ou organisations souhaitant comprendre et consommer l’offre, qui facilite:
- l'appropriation de la **[documentation de l'offre Cloud Native](https://github.com/cloud-pi-native/documentation)**
- la consultation des [**ressources d'autoformation**](./plan-formation.md). 


# Pour quoi faire ?
- **Pour se former à titre individuel**: en consultant des ressources d'autoformation disponibles à chaque étape (voir le périmètre correspondant à ses responsabilités dans la section "se former à titre individuel");
- **Pour embarquer rapidement une équipe projet**: en consultant, à chaque étape du parcours, la sélection d'éléments de [documentation de l'offre](https://github.com/cloud-pi-native/documentation), de connaissances théoriques et pratiques nécessaires à la prise en main. 


# Etapes du parcours d'embarquement/autoformation

Le parcours comporte 5 étapes "d'embarquement", de la prise de connaissance de l'offre à l'utilisation en autonomie. Pour l'autoformation, ces 5 étapes correspondent à des degrés de "maturité" (i.e. type de questions que les utilisateurs se posent).

![alt_text](images/accompagnement.jpg)

<details>

<summary> Hypothèses/principes de conception du parcours </summary>

- Respect de l'ordre chronologique : le `niveau de maturité` requis augmente au fur et à mesure des `étapes d'embarquement`, jusqu'à l'autonomie en production;
- Acessibilité : les premières étapes (comprendre l'offre et préparer un projet) ne nécessitent aucune connaissance théorique ou pratique préalables;
- Reconnaissance des acquis : plutot que des formations par métiers, dont les intitulés ne correspondent pas toujours à la réalité des missions exercées sur le terrain, nous distingons de façon macroscopique, des `périmètres de responsabilités`.

</details>

# Se former à titre individuel: quel est mon périmètre? 

Pour se former à titre individuel, il est nécessaire d'identifier le périmètre correspondant aux responsabiltiés que l'on exerce: 

1) **Périmètre "technique"**: ressources spécifiques aux composants de l'offre Cloud Pi Native destinées aux équipes techniques responsables de l'utilisation de l'offre pour construire, opérer et gérer des produits numériques, tout au long de leur cycle de vie. 

<details>

<summary> Exemples </summary>

Responsables de la qualité des produits/SI. Selon la taille et de l'organisation, ce périmètre peut recouvrir des personnes responsables de la fiabilité des services & des systèmes (plateformes de services, pipelines de livraison DevSecOps, services d’hébergement, environnements, réseaux, etc.). Exemples: développeurs, opérateurs, DevOps, SRE, architectes solution, etc.

</details>

2) **Périmètre "pilotage MOE"**: ressources relatives au "cloud native" notamment destinées aux personnes responsables de la structuration d'un projet (compétences, roles, organisation, technologies, ..) son organisation et son suivi (consommation budgetaire, UO, livrables, ...), pour saisir les opportunités du paradigme "cloud native".  

<details>

<summary> Exemples </summary>

Responsables de l'intégrité des équipes assurant le développement ou les opérations sur les produits et de l'intégrité des projets (cadrage, bonne utilisation et suivi des ressources, orientations techniques...). Exemples:  pilotage/chefferie de projets/programmes, responsables d'unités de conception, de bureaux d'étude, MOE, etc.

</details>

3) **Périmètre "gouvernance/décisionnaire"**: ressources de culture générale sur les enjeux du numérique, adressées à tous mais particulièrement aux personnes responsables de l'orientation de projets numériques vers une offre  de service donnée pour comprendre les spécificités du "nouveau monde logiciel". 

<details>

<summary> Exemples </summary>

Responsables de la pertinence des décisions stratégiques ce qui recouvre, plus largement, les personnes chargées de les conseiller. Exemples: pilotage et gouvernance des organisations, directions générales ou métiers, stratégie d'achat, stratégie RH, etc.

</details>

*Les équipes d'accompagnement du programme programme Cloud Pi Native peuvent aussi conseiller des ressources spécifiques en fonction des besoins et de la maturité de l'équipe projet.*


# Utilisation pour l'embarquement d'une équipe projet

## Quelles démarches sont accompagnées par le programme Cloud Pi Native?

| Cas |Organisation porteuse|Démarche| Eligible à un accompagnement sur |
|----| -------------- | --------------- | ------------------------ |
|1| Organisation rattachée à un ministère | Déploiement ou migration d’un projet sur le Cloud Pi | Préqualification, qualification, appui au lancement et suivi |
|2| Organisation rattachée à un ministère | Expérimentation de l’usine logicielle sur d'autres infra | Préqualification, qualification, appui au lancement à définir|
|3| Organisation externe | Expérimentation pour initiative partenariale | Préqualification |
|4| Organisation externe | Expérimentation en autonomie | Pas d’accompagnement |

L'accompagnement par les équipes du programme Cloud Pi Native consiste en:
- Préqualification: aide à la structuration de la démarche et analyse de son adéquation avec l'offre (les composants: existants, inscrits ou à inscrire à la roadmap du programme);
- Qualification: aide à la structuration du plan projet et, le cas échéant, estimation de l'effort technique et d'accompagnement à prévoir;
- Accompagnement "technique" pour le lancement et le suivi du projet: aide/conseil des équipes techniques clientes en charge du projet;

Les conditions d'accompagnement seront détaillées à chaque étape du parcours.

## Etape 1: argumenter l'opportunité du Cloud Native, analyser son besoin

> **Objectifs et étapes clefs**: vous avez entendu parler de l'offre Cloud Pi Native et souhaitez-vous renseigner pour juger ou argumenter de son adéquation (ou non) avec votre besoin. Pour cela: 
> - Prenez connaissance la [page de présentation l'offre](https://dnum-mi.github.io/) et du [support de sensibilisation aux enjeux](./sensibilisation.md);
> - Appuyez-vous sur la [trame de préqualification](./diagnostic-prequalification.md) pour analyser votre besoin (contexte, objectifs, moyens ...) et décrire votre démarche;
> - Si vous êtes en recherche de sponsor, appuyez-vous sur la trame de préqualification pour construire un argumentaire;

>**Eligibles à un accompagnement**: prenez contact par mail avec le programme Cloud Pi Native pour faire connaitre votre démarche et programmer un entretien de préqualification.
> - Acteurs ministériels: assurez-vous, auprès de votre hiérarchie, que votre démarche s’inscrit bien dans un projet financé et soutenu ;
> - Acteurs externes: aucune démarche commerciale ne sera étudiée. Nous accompagnons les initiatives partenariales, à visée d'intérêt général ou de contribution à l'offre communautaire;


## Etape 2: structurer son plan projet, se préparer
>**Objectif et étapes clefs**: vous avez établi de l'adéquation de l'offre proposée avec votre besoin. Vous souhaitez maintenant savoir à quoi vous engage le fait de la consommer et comment vous y préparer. Pour cela: 
> - Consulter les [ressources d'autoformation de l'étape 2](./formation_step2.md) et le cadre de cohérences technique dans lequel s'inscrit l'offre ([CCT Cloud Native](https://github.com/cloud-pi-native/cct-cloud-native));
> - Appuyez-vous sur la [trame de qualification](./modele-plan-projet.md) pour élaborer votre plan projet et vous assurer de vérifier les prérequis organisationnels (compétences, roles, modèle de responsabilités...) techniques (complexité, technologies, ...), compréhension du cadre de normes, évaluation des éventuels besoins de formation...
> - Si vous devez faire des demandes de ressources d'infrastructures, prenez connaissance des démarches à engager;

>**Eligibles à un accompagnement**: appuyez-vous sur la trame de qualification pour préparer votre plan projet.
> - Projet porté par un acteur/une organisation rattachée à un ministère :  sollicitez un entretien de qualification technique;
> - Initiative partenariale portée par un acteur externe : merci de communiquer votre plan projet au programme Cloud Pi Native, qui se réserve la possibilité de programmer un entretien de qualification;


## Etape3: lancer son projet dans un environnement de développement "Cloud native", expérimenter
>**Objectif et étapes clefs**: vous avez élaboré votre plan projet. Vous souhaitez maintenant utiliser l'offre pour lancer votre projet dans un environnement de développement. Pour cela:
> - Consultez les [ressources de formation de l'étape 3](./formation_step3.md)
> - Appuyez-vous sur la [documentation de l'offre](https://github.com/cloud-pi-native/documentation) pour:
>   - Vérifier les prérequis;
>   - Réaliser un "Hello world"
>   - Déployer un MVP dans l'environnement de développement;

>**Eligibles à un accompagnement**: vous avez obtenu un entretien de qualification pour définir une roadmap d’accompagnement.
> - Projet porté par un acteur/une organisation rattachée à un ministère :  assurez-vous de présenter les prérequis et préparez vos questions/besoins en formation.
> - Projet à déployer sur le Cloud Pi :  assurez-vous d’avoir pris connaissance de la procédure de [demande d’hébergement]( https://pi.interieur.rie.gouv.fr/home-dnum/infrastructure-et-dev/hebergement-et-reseau/hebergement/)


## Etape 4: passer en production, construire dans le respect des normes
>**Objectif et étapes clefs**: vous avez réalisé une version suffisamment représentative de votre produit (MVP) en environnement de développement. Vous souhaitez maintenant déployer votre produit dans un environnement de production et vous assurer que le cadre de normes est respecté.
>- Provisionner vos ressources
> - Consulter les [ressources de formation de l'étape 4](./formation_step4.md)
> - Appuyez-vous sur la [documentation de l'offre](https://github.com/cloud-pi-native/documentation) pour déployer votre produit dans l’environnement de production;

>**Eligibles à un accompagnement**: 
>- Réaliser une [demande d'hébergement sur le Cloud Pi](https://resana.numerique.gouv.fr/public/document/consulter/7054535) (section à venir)


## Etape 5: atteindre les meilleurs standards, évoluer en continu
>**Objectif et étapes clefs**: L'équipe construit, opère et fait évoluer ses produits en autonomie, dans le respect des normes. L’équipes souhaite maintenant mettre en place l’ensemble des bonnes pratiques pour répondre aux meilleurs standards de qualité et de sécurité, tout en évoluant en continu.

>- Mettre en place les bonnes pratiques et les moyens de leur suivi

>- Assurer la continuité de service et des bonnes pratiques lors des évolutions du produit 

> **Ressources:** [évoluer en production](./formation_step5.md)





