Les ressources rassemblées ici constituent une base de connaissances permettre aux équipes clientes d'acquérir rapidement un maximum d'autonomie sur l'offre cloud native portée par le Ministère de l'Intérieur s'appuyant un environnement du Cloud souverain Pi (offre "Cloud Pi Native"). Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository 
- Faisant des issues

# Que contient cette section?
**Un parcours d'embarquement/formation "pas à pas"**, destiné aux personnes ou organisations souhaitant comprendre et consommer l’offre, qui facilite l'appropriation de la **[documentation de l'offre Cloud Native](https://github.com/cloud-pi-native/documentation)** et la mise en oeuvre du [**plan de formation**](./plan-formation.md). 


# Pour quoi faire ?
- **Pour se former à titre individuel**: en consultant des ressources d'autoformation disponibles à chaque étape (voir le périmètre correspondant à ses responsabilités dans la section "se former à titre individuel");
- **Pour embarquer rapidement une équipe projet**: en consultant, à chaque étape du parcours, le "mode d'emploi" et la documentation nécessaire ainsi que les connaissances théoriques et pratiques nécessaires. 


# Parcours d'embarquement/autoformation

Le parcours comporte 5 étapes "d'embarquement", de la prise de connaissance de l'offre à l'utilisation en autonomie qui correspondent à des degrés de "maturité" (i.e. type de questions que les utilisateurs se posent).

![alt_text](images/accompagnement.jpg)

<details>

<summary> Hypothèses/principes de conception du parcours </summary>

- Respect de l'ordre chronologique : le `niveau de maturité` requis augmente au fur et à mesure des `étapes d'embarquement`, jusqu'à l'autonomie en production;
- Acessibilité : les premières étapes (comprendre l'offre et préparer un projet) ne nécessitent aucune connaissance théorique ou pratique préalables;
- Reconnaissance des acquis : plutot que des formations par métiers, dont les intitulés ne correspondent pas toujours à la réalité des missions exercées sur le terrain, nous distingons de façon macroscopique, des `périmètres de responsabilités`.

</details>

## Quelles démarches peuvent être accompagnées par le programme Cloud Pi Native?
Sous réserve d'éligibilité, les équipes du programme Cloud Pi Native accompagnent à :
- **La préqualification du besoin:** aide à la structuration de la démarche, analyse du besoin et de son adéquation avec l'offre (i.e. les composants existants ou figurant à la roadmap du programme);
- **La qualification technique:** aide à la structuration du plan projet, à la préparation de l'équipe, et, le cas échéant, à l'estimation de l'effort d'accompagnement technique à prévoir;
- **Assitance au lancement et suivi:** aide/conseil des équipes techniques clientes en charge du projet pour le lancement et/ou le suivi de leur projet;

| Cas |Organisation porteuse|Objectifs| Types d'accompagnement éligible|
|----| -------------- | --------------- | ------------------------ |
|1| Rattachée à un ministère | Déploiement, migration ou expérimentations sur le Cloud Pi | Préqualification, qualification, assistance au lancement et suivi |
|2| Rattachée à un ministère | Déploiement, migration ou expérimentations sur d'autres infrastructures | Préqualification, qualification, assistance au lancement à définir|
|3| Externe | Initiative partenariale | Préqualification |
|4| Externe | Expérimentation pour ses propres finalités | Pas d’accompagnement |

Les conditions d'accompagnement seront détaillées à chaque étape du parcours.

# Plan d'accompagnement et de formation

| | | | | | | | | |
|-|-|-|-|-|-|-|-|-|
|N° étape|Stade d'avancement du projet |Maturité de l'équipe|Ressources et mode d'emploi de cloud Pi Native|Accompagnement|Ressources d'autoformation Périmètre décision/stratégie|Ressources d'autoformation Périmètre pilotage MOE|Ressources d'autoformation Périmètre  réalisation technique  (produit ou système de production)|Checklist|
|1|Comprendre l'opportunité du Cloud Native pour son besoin|Quels sont les mutations/enjeux/risques actuels du numérique et quels sont les opportunités?  |- Consulter les supports de sensibilisation - Spécifier son besoin - Obtenir le soutien de sa démarche (sponsor)|- Prendre contact avec le programme Cloud Pi Native - RDV de préqualification avec l'équipe Adoption|Comprendre les enjeux du "nouveau monde logiciel" pour la transformation du numérique public|Opportunités du "nouveau monde numérique" : technologies "cloud native", méthodologies, approches et mode d'organisation, culture...|Opportunité d'un socle de production à l'état de l'art "Cloud Native" pour le développement et la gestion de produits numériques|Organisation/contexte métier, besoin, démarche/objectifs, type de projet et adéquation offre|
|2|Préparer son projet/produit "cloud native"|Sur quoi reposent les opportunités du cloud native et comment s'en saisir à son niveau?|- Lire le Cadre de cohérence Technique (CCT Cloud Native) - Définir son plan projet (cf. Checklist)|- Completer  le formulaire de demande d'accès à la console - RDV de qualification technique Adoption/Service team|Comprendre comment les grands acteurs du numériques/grandes organisation ont tirés parti des nouvelles opportunités|Comprendre les technologies, modes d'organisation et cultures portées par le cloud native|Comprendre les différents services d'un socle de production Cloud Native à chaque étape du cycle de vie d'un produit|Organisation de l'équipe et périmètre technique, prérequis, qualification technique du projet|
|3|Lancer son projet/produit dans un environnement de développement "Cloud native"|Comment se préparer pour mettre en place une offre cloud native, chacun à son niveau? |- Lire documentation de l'offre - S'exercer avec les tutoriels - Provisionner et déployer son environnement de développement "cloud native".|- Préparation de l'architecture projet - RDV de lancement avec la Service Team|Comprendre l'impact de ces nouvelles opportunités sur la gouvernance des organisations|Organiser et préparer une équipe produit pour mettre en place et utiliser des outils "cloud native"|Réaliser un premier "hello world", puis construire un MVP avec un socle de production Cloud Native|Préparation de l'équipe et de l'architecture projet, provisionnement et mise en place de l'environnement de dev., préparation des démarches pour la production|
|4|Passer en production, construire dans le respect de normes "Cloud Native"|Comment réaliser le potentiel du cloud native, dans le respect des des différentes normes (techniques, organisationelles, etc.)? |- Lire la documentation de l'offre - Provisionner et déployer son environnement de production "Cloud native" - Prise en main des outils d'observabilité|- S'intégrer aux processus nominaux (hébergement, homologation, certification, …) - Suivi technique avec la service team|Assurer la qualité et la sécurité au niveau des organisations dans le "nouveau monde logiciel"|S'organiser pour concevoir et gérer des produits de A à Z dans un cadre Cloud Native|Déployer en production, puis mettre en service un produit cloud native|Provisionnement et mise en place de l'environnement de production, respect des exigences du cadre normes, préparation des bonnes pratiques|
|5|Atteindre les meilleurs standards du "Cloud Native", évolution continue|Comment garantir en continu, l'intégration, le suivi et la pérénnité des bonnes pratiques tout en permettant la maitrise de standards en évolution permanente? | | |Manager un patrimoine numérique pour rester autonome et performant sur la durée|Tirer le plein potentiel et contribuer aux technologies du CNCF Landscape (dont charts helms/operators)|Assurer la disponibilité et la continuité, MCO/MCS, garder des options ouvertes sur les transitions futures| |


- **Stade d'avancement du projet**: avancement dans la démarche de consommation de l'offre et l'utilisation en autonomie;
- **Maturité de l'équipe**: macro-questions, auxquelles on apporte des ressources/niveaux de réponse différents selon la nature des responsabilités exercées;
Ressources et mode d'emploi de cloud Pi Native;
- **Ressources et mode d'emploi de cloud Pi Native**: les ressources et leur mode d'emploi/usage selon le stade d'avancement : sensibilisation, acculturation, expérimentation, mise en place, exploitation, … ;
- **Accompagnement**: ssous réserve d'éligibilité (voir section correspondante), assistance du programme Cloud Pi Native ; 
- **Ressources d’autoformation**:  ressources non-spécifiques à l’offre, nécessaires pour comprendre et utiliser les ressources spécifiques à Cloud Pi Native. Les distinctions entre responsabilités pourront être affinés selon les personas ou métiers) ;
- **Checklist**: questions et critères à valider avant de passer à l'étape suivante.




# Ressources d'autoformation: pour quel périmètre de responsabilités? 

Il est nécessaire d'identifier son périmètre parmi 3 types, selon la nature des responsabiltiés exercées: 

1) **Périmètre "technique"**: ressources spécifiques aux composants de l'offre Cloud Pi Native destinées aux équipes techniques responsables de l'utilisation de l'offre pour construire, opérer et gérer des produits numériques, tout au long de leur cycle de vie. Cela peut être:
    - Directement, pour développer et opérer des produits (équipe DevOps);
    - Indirectement, pour mettre en place et assurer la fiabilité des systèmes de production nécessaires (SRE, ingéniérie de plateforme).

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


# Mode d'emploi pour l'embarquement d'une équipe projet

## Etape 1: comprendre l'opportunité du Cloud Native

> **Objectifs et étapes clefs**: vous avez entendu parler de l'offre Cloud Pi Native et souhaitez-vous renseigner pour juger ou argumenter de son adéquation (ou non) avec votre besoin. Pour cela: 
> - Prenez connaissance la [page de présentation l'offre](https://dnum-mi.github.io/) et du [support de sensibilisation aux enjeux](./sensibilisation.md);
> - Appuyez-vous sur la [trame de préqualification](./diagnostic-prequalification.md) pour analyser votre besoin (contexte, objectifs, moyens ...) et décrire votre démarche;
> - Si vous êtes en recherche de sponsor, appuyez-vous sur la trame de préqualification pour construire un argumentaire;

>**Eligibles à un accompagnement**: prenez contact par mail avec le programme Cloud Pi Native pour faire connaitre votre démarche. Elle pourra être approfondie dans el cadre d'un entretien de préqualification.
> - Acteurs ministériels: assurez-vous, auprès de votre hiérarchie, que votre démarche s’inscrit bien dans un projet financé et soutenu ;
> - Acteurs externes: aucune démarche commerciale ne sera étudiée. Nous accompagnons les initiatives partenariales, à visée d'intérêt général ou de contribution à l'offre communautaire;


## Etape 2: préparer son projet "cloud native"
>**Objectif et étapes clefs**: vous avez établi l'adéquation de l'offre proposée avec votre besoin. Vous souhaitez maintenant savoir à quoi vous engage le fait de la consommer et comment vous y préparer. Pour cela: 
> - Consulter les [ressources d'autoformation de l'étape 2](./formation_step2.md) et le cadre de cohérences technique dans lequel s'inscrit l'offre ([CCT Cloud Native](https://github.com/cloud-pi-native/cct-cloud-native));
> - Appuyez-vous sur la [trame de qualification](./modele-plan-projet.md) pour élaborer votre plan projet et vous assurer de vérifier les prérequis organisationnels (compétences, roles, modèle de responsabilités...) techniques (complexité, technologies, ...), compréhension du cadre de normes, évaluation des éventuels besoins de formation...
> - Si vous devez faire des demandes de ressources d'infrastructures, prenez connaissance à cette étape des démarches à engager;

>**Eligibles à un accompagnement**: préparez votre plan projet.
> - Projet porté par un acteur/une organisation rattachée à un ministère : sollicitez un entretien de qualification technique du plan projet;
> - Initiative partenariale portée par un acteur externe : merci de communiquer votre plan projet au programme Cloud Pi Native, qui se réserve la possibilité de programmer un entretien de qualification (interet général ou pour la communauté);


## Etape 3: lancer son projet dans un environnement de développement "Cloud native"
>**Objectif et étapes clefs**: vous avez élaboré votre plan projet. Vous souhaitez maintenant utiliser l'offre pour lancer votre projet dans un environnement de développement. Pour cela:
> - Consultez les [ressources de formation de l'étape 3](./formation_step3.md)
> - Appuyez-vous sur la [documentation de l'offre](https://github.com/cloud-pi-native/documentation) pour:
>   - Vérifier les prérequis;
>   - Vous exercer et réaliser un "Hello world"
>   - Déployer un MVP en environnement de développement;

>**Eligibles à un accompagnement**: vous avez obtenu un entretien de qualification pour définir une roadmap d’accompagnement.
> - Projet porté par un acteur/une organisation rattachée à un ministère :  assurez-vous de présenter les prérequis et préparez vos questions/besoins en formation.
> - Projet à déployer sur le Cloud Pi :  assurez-vous d’avoir pris connaissance de la procédure de [demande d’hébergement]( https://pi.interieur.rie.gouv.fr/home-dnum/infrastructure-et-dev/hebergement-et-reseau/hebergement/)


## Etape 4: passer en production, construire dans le respect des normes "Cloud Native"
>**Objectif et étapes clefs**: vous avez réalisé une version suffisamment représentative de votre produit (MVP) en environnement de développement. Vous souhaitez maintenant déployer votre produit dans un environnement de production et vous assurer que le cadre de normes est respecté.
> - Provisionner vos ressources
> - Consulter les [ressources de formation de l'étape 4](./formation_step4.md)
> - Appuyez-vous sur la [documentation de l'offre](https://github.com/cloud-pi-native/documentation) pour déployer votre produit dans l’environnement de production;

>**Eligibles à un accompagnement**: 
>- Réaliser une [demande d'hébergement sur le Cloud Pi](https://resana.numerique.gouv.fr/public/document/consulter/7054535) (section à venir)


## Etape 5: atteindre les meilleurs standards du "Cloud Native", évoluer en continu
>**Objectif et étapes clefs**: L'équipe construit, opère et fait évoluer ses produits en autonomie, dans le respect des normes. L’équipes souhaite maintenant mettre en place l’ensemble des bonnes pratiques pour répondre aux meilleurs standards de qualité et de sécurité, tout en évoluant en continu.
>- Mettre en place les bonnes pratiques et les moyens de leur suivi
>- Assurer la continuité de service et des bonnes pratiques lors des évolutions du produit 

> **Ressources:** [évoluer en production](./formation_step5.md)





