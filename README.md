Les ressources rassemblées ici constituent la base de connaissance du socle que nous proposons 1) une sensibilisation aux enjeux adressés 2) une formation, un apprentissage à la maitrise des ressources proposées 3) une acculturation à l'utilisation du socle via des kits de prise en main.bDans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository
- Faisant des issues

# Enjeux de la transformation numérique (sensibilisation)
### Un "nouveau monde" logiciel a émergé
Ces 10 dernières années la puissance d'intermédiation du numérique a dévoré une part croissante des activités humaines. Transport, banque, finance, sociabilité, hotellerie, logistique, sécurité, identité, culture, divertissement... deviennent numériques.  Les causes d'un tel changement ne sont pas seulement technologiques mais ont trait aux organisations, périmètres de responsabilités et normes sous-jacentes (y compris culturelles) à la production numérique. C'est un changement de paradigme complet, un ["nouveau monde logiciel"](https://pi.interieur.rie.gouv.fr/nouveau-monde-logiciel/).

### Le service public est mis au défi
Dans ce nouveau cadre, certains produits/services deviennent des « normes de fait »: les décisions les concernant, leurs caractéristiques, impactent des millions d'utilisateurs ce qui pose des [défis importants aux organisations publiques](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.3-defi_service_public.md). Pour rester au service de leurs usagers et agents, en particulier sur leurs missions régaliennes, ces dernières doivent se doter de moyens techniques et organisationnels (production, opération, maintenance, ...) et des normes techniques et non-techniques (neutralité, RGPD, accessibilité,...) du "nouveau monde" numérique.

### Un socle pour remettre "l'usager au centre"
Pour réussir un projet de transformation au service des usagers, la production du numérique public doit être organisée ["en mode produit"](https://6695516.fs1.hubspotusercontent-na1.net/hubfs/6695516/Culture_Produit_Web_Extrait.pdf?__hstc=154216807.d3e24310b08a19eb0fbdb060971025e2.1671555363753.1671555363753.1675700990863.2&__hssc=154216807.2.1675700990863&__hsfp=1771427427&hsCtaTracking=3562120f-8ddc-4973-8c94-6fc9bd6753e2%7C5eb7f077-d1f7-422e-9a12-ab4e2311abe6) (évolutivité, disponibilité) en incluant les développeurs, usagers trop souvent oubliés. La voie que nous privilégions pour cela emprunte aux technologies ["cloud native"](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.2-technologies-cloud-native.md) (conteneurisation, API, microservices) et aux approches [DevSecOps](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.1-approche_devsecops.md) (culture de responsabilités partagées). 

Comme expliqué dans le [cadre de cohérence technique Cloud Pi Native (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native), l'offre Cloud Pi Native vise à "industrialiser" une telle approche pour la mettre en place au sein d'un flux de production continue, intégré et optimisé (lean), suffisament ouvert pour pouvoir évoluer en continu (agile). Le modèle-socle d'une usine logicielle "lean-agile". 


# Parcours d'apprentissage (formation)
Nous souhaitons faciliter l'action de l'ensemble des acteurs désireux de contribuer à la transformation numérique du service public en répondant à ces questions 1) quels sont les principes directeurs et modèles d'organisations nécessaires à l'utilisation du socle que nous proposons? 2) Quels sont les concepts et les prérequis sous jacents pour l'utiliser? 3) Quel est le degré de préparation/maturité de mon équipe?

### Ecosystème et cadre du socle
Comme dans toute transformation industrielle découlant d'innovation(s) majeure(s), les responsabilités des acteurs en place sont profondément modifiées. En nous appuyant sur la doctrine [cloud au centre de l'Etat](https://www-lemagit-fr.cdn.ampproject.org/c/s/www.lemagit.fr/actualites/365531732/Cloud-souverain-la-DINUM-contextualise-les-exigences-de-la-France?amp=1), nous proposons un [modèle opérationnel](https://github.com/Yoarmi/dso-formation/blob/patch-1/2-modele_organisation.md) pour comprendre l'articulation des différents périmètre de responsabilité et tirer pleinement parti du socle cloud Pi native. 

Nous vous invitons à prendre connaissance des principes sous-jacents exposés dans le [cadre de cohérence technique Cloud Pi Native (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native) et à y contribuer. De ces principes découleront les exigences technologiques, organisationnelles, bonnes pratiques, processus... préconisés pour livrer des produits numériques à l'état de l'art et les gérer tout au long de leur cycle de vie.

### Parcours, par périmètre de responsabilité
Les parcours d'apprentissage s'adressent aux populations concernées par 4 grands périmètres de responsabilités:
- « [Qualité des produits numériques](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.1-parcours-produit.md) » : personnes qui élaborent de nouveaux produits numériques et/ou assurent la gestion de leur cycle de vie. Ils sont responsables de leur développement, mise en production, MCO/évolution, migration, etc. Ce sont les développeurs, opérateurs de produits, les architectes solution, … 
- « [Fiabilité des services & systèmes (SRE)](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.2-parcours_systeme.md) » : personnes qui assurent l’intégrité des services et systèmes nécessaires aux équipes de développement et d'opération des produits numériques, tout au long de leur cycle de vie: pipelines de livraison DevSecOps, services d’hébergement, génération d’environnements, etc. Ce sont les system teams, les équipes d’ingénierie de fiabilité des sites (SRE, Site Reliability Engineering), les forges, les opérateurs de plateformes (IaaS, PaaS, XaaS, ...)...
- « [Intégrité des projets](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.3-parcours_projet.md) » : personnes qui pilotent les équipes de développement ou de gestion des opérations. Elles sont responsables du cadrage des projets, de la bonne utilisation et du suivi des ressources (humaines et techniques), des orientations à prendre pour la menée d'un projet. Il s'agit des équipes de pilotage/chefferie de projets ou de programmes, de MOE ou d'unités de conception, de bureaux d'étude, etc.
- « [Pertinence de la décision stratégique](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.4-parcours_strategie.md) » : personnes qui prennent des décisions, se portent garantes de l’engagement des organisations sur des sujets touchant au numérique. Ce périmètre comprend également les personnes chargées de les conseiller quand à la stratégie à adopter, de fournir des recommandations, de délivrer des mandats ou de réaliser des arbitrages concernant les finalités, moyens et modes d’organisation. Il s’agit de la décision stratégique, du pilotage et de la gouvernance des organisations, des directions générales ou des directions de stratégie métiers, achats, RH, etc.

### Diagnostic du degré de maturité
Nous proposons un "diagnostic" de l'appropriation des connaissances et compétences des équipes utilisatrices. En fonction des informations receuillies, ce diagnostic permet de définir la formation et l'accompagnement des équipes, par périmètre de responsabilité, dans l'appropriation du socle et l'appréhension de son contexte (organisationnel et technique).
 
 
# Premier contact avec Cloud Pi Native et prise en main (acculturation)
Nous pensons que toute personne désireuse de contribuer à la transformation numérique du service public (agent, citoyen, industriel du numérique, représentant d'institutions publiques... ) doit pouvoir rapidement tester le socle et se familliariser avec son utilisation. Pour cela, nous mettons à disposition les souches logicielles et la documentation du socle, mais également des kits de démarrage: tutoriels, formations "hands-on" (par la pratique) et bacs à sable (sandbox). 

### Contextes d'utilisation de Cloud Pi Native
Nous distinguons deux contextes d'utilisation particuliers de l'offre pour lesquels nous renvoyons à des ressources spécifiques:
- Contexte interministériel: pour l'utilisation au sein d'un ministère nous renvoyons au [catalogue de services](https://pi.interieur.rie.gouv.fr/home-dnum/cloud-%cf%80/qui-sommes-nous/cloud-native/) et au [cadre de cohérence technique (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native);
- Partenaires industriels et communauté open source: l’offre est mise à disposition en open source pour favoriser l'appropriation des technologies « Cloud Native » et l’émergence de standards du numérique public interopérables avec la production industrielle. La section ["comment contribuer?"](https://github.com/Yoarmi/dso-formation/blob/patch-1/4-contribuer.md) vous oriente à travers des communautés rassemblées par une ambition d'innovation et de transformation du service public.

### Guides et tutoriels
Afin de tirer le meilleur parti des guides, kit, et outils proposés, nous conseillons de s'être préalablement familiarisé avec les concepts présentés dans parcours de formation. Ceci afin de permettre la prise en main des composantes de l'offre avec tout l'autonomie possible: 
- [Guide technique » : pour la prise en main du socle technique](https://github.com/dnum-mi/dso-socle);
- [Guide technique » : pour la prise en main de la console](https://github.com/dnum-mi/dso-console).
- https://github.com/dnum-mi/gitops-tutorial



