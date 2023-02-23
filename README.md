Les ressources rassemblées ici constituent une introduction à l’offre que nous proposons 1) une sensibilisation aux enjeux adressés 2) des ressources de formation à destination des populations concernées 3) des kits de démarrage pour prendre en main et s'acculturer. 

Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository;
- Faisant des issues.

# Enjeux de la transformation numérique (sensibilisation)
### Un "nouveau monde" logiciel a émergé
Ces dernières années la puissance d'intermédiation du numérique a dévoré une part croissante des activités humaines. Transport, banque, finance, sociabilité, hotellerie, logistique, sécurité, identité, culture, divertissement... deviennent numériques.  Les origines et les conséquences d'un tel changement ne sont pas seulement technologiques : elles touchent aux organisations, périmètres de responsabilités et normes sous-jacentes (y compris culturelles). C'est un changement de paradigme, un ["nouveau monde logiciel"](https://github.com/Yoarmi/dso-formation/blob/patch-1/1-enjeux_nouveau_monde.md). 

### Le service public est mis au défi
Dans ce nouveau cadre, certains produits/services deviennent des « normes de fait »: les décisions les concernant, leurs caractéristiques, impactent des millions d'utilisateurs ce qui pose des [défis importants aux organisations publiques](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.3-defi_service_public.md). Pour rester au service de leurs usagers et agents, en particulier sur leurs missions régaliennes, ces dernières doit se doter des moyens de maitriser les outils (de production, opération et maintenance) et les normes (techniques ou non: neutralité, RGPD, accessibilité,...) du "nouveau monde" numérique.

### Un socle pour remettre "l'usager au centre"
Pour réussir ce projet de transformation au service des usagers, le numérique public doit fonctionner ["en mode produit"](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.1-approche_devsecops.md) (évolution continue) en incluant les développeurs, usagers trop souvent oubliés. La voie privilégiée que nous proposons pour cela emprunte aux technologies ["cloud native"](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.2-technologies-cloud-native.md) (conteneurisation, API, microservices) et aux approches [DevSecOps](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.1-approche_devsecops.md) (culture de responsabilités partagées). 

Le socle proposé ici vise à "industrialiser" cette approche pour la mettre en place au sein d'un flux de production continue, intégré et optimisé (lean), capable d'évoluer en continu (agile). Le socle est en quelques sortes une "usine" lean-agile. 


# Parcours d'apprentissage (formation)
Nous souhaitons faciliter l'action de l'ensemble des acteurs désireux de contribuer à la transformation numérique du service public à travers deux questions 1) quels sont les principes directeurs et modèles d'organisations nécessaires à l'utilisation du socle que nous proposons? 2) Quels sont les concepts et les prérequis sous jacents pour l'utiliser? 3) Quel est le degré de préparation/maturité de mon équipe?

### Ecosystème et cadre du socle
Comme dans toute transformation industrielle découlant d'innovation(s) majeure(s), les périmètres de responsabilité existants sont affectés. En nous appuyant sur la doctrine "cloud au centre de l'Etat", nous tentons donc de défnir un [modèle opérationnel](https://github.com/Yoarmi/dso-formation/blob/patch-1/2-modele_organisation.md) permettant de tirer le plein parti de notre socle technique. Nous vous invitons à prendre connaissance des principes et exigences sous-jacents, qui sont exposés dans le [cadre de cohérence technique Cloud Pi Native (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native). De ces principes découleront les technologies, bonnes pratiques, organisations, processus... préconisés pour livrer et gérer des produits numériques tout au long de leur cycle de vie.

### Parcours, par périmètre de responsabilité
Pour la formation, nous distinguons les populations concernées par 4 grands périmètres de responsabilités:
- « [Qualité des produits numériques](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.1-parcours-produit.md) » : personnes qui élaborent de nouveaux produits numériques et/ou assurent la gestion de leur cycle de vie. Ils sont responsables de leur développement, mise en production, MCO/évolution, migration, etc. Ce sont les développeurs ou opérateurs de produits, les architectes, … 
- « [Fiabilité des services & systèmes (SRE)](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.2-parcours_systeme.md) » : personnes qui assurent l’intégrité des services et systèmes nécessaires au développement et à l'opération des produits numériques, tout au long de leur cycle de vie: pipelines de livraison DevSecOps, services d’hébergement, génération d’environnements, etc. Ce sont les system teams, les équipes d’ingénierie de fiabilité des sites (SRE, Site Reliability Engineering), les forges, les opérateurs de plateformes (IaaS, PaaS, XaaS, ...).
- « [Intégrité des projets](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.3-parcours_projet.md) » : personnes qui pilotent les équipes de développement ou de gestion des opérations. Elles sont responsables du cadrage des projets, de la meilleure utilisation des ressources (humaines et techniques) pour la menée d'un projet. Il s'agit du pilotage/chefferie de projets/programmes, de MOE ou d'unités de réalisation, bureau d'étude, etc.
- « [Pertinence de la décision stratégique](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.4-parcours_strategie.md) » : personnes qui prennent des décisions, se portent garantes de l’engagement des organisations sur des sujets touchant au numérique. Cepérimètre comprend aussi les personnes chargées de les conseiller quand à la stratégie à adopter, de donner des recommandations, délivrer des mandats ou réaliser des arbitrages concernant les finalités, moyens et modes d’organisation. Il s’agit de la décision stratégique, du pilotage/gouvernance des organisations, de directions générales ou de directions de la stratégie métiers, achats, RH, etc.

### Diagnostic du degré de maturité
Nous proposons un "diagnostic" de l'appropriation des connaissances et compétences des équipes utilisatrices. En fonction du périmètre de responsabilité et des résultats, ce diagnostic permet de définir la formation et l'accompagnement des équipes dans l'appropriation du socle et l'appréhension de son contexte (organisationnel et technique).
 
 
# Tutoriels et prise en main du socle (acculturation)
Nous mettons à disposition ici des souches logicielles, de la documentation, des formations "hands-on" (par la pratique). Nous pensons que toute personne désireuse de contribuer à la transformation numérique du service public (agent, citoyen, industriel du numérique, représentant d'institutions publiques... ) doit pouvoir expérimenter les outils mis à sa disposition.

### Kits de démarrage
Afin de tirer le meilleur parti des guides, kit, et outils proposés, nous conseillons de s'être préalablement familiarisé avec les concepts présentés dans parcours de formation. Ceci, afin de permettre la prise en main des composantes de l'offre avec un maximum d'autonomie: 
- [Guide technique » : pour la prise en main du socle technique](https://github.com/dnum-mi/dso-socle);
- [Guide technique » : pour la prise en main de la console](https://github.com/dnum-mi/dso-console).

### Contextes d'utilisation particuliers
Nous distinguons deux contextes d'utilisation particuliers de l'offre pour lesquels nous renvoyons à des ressources spécifiques:
- Contexte interministériel: pour l'utilisation au sein d'un ministère nous renvoyons au [catalogue de services](https://pi.minint.fr/home-dnum/cloud-%cf%80/qui-sommes-nous/cloud-native/) et au [cadre de cohérence technique (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native);
- Contexte communautaire: l’offre est mise à disposition en open source pour favoriser l'appropriation des technologies « Cloud Native » et l’émergence de standards du numérique public. La section ["comment contribuer?"](https://github.com/Yoarmi/dso-formation/blob/patch-1/4-contribuer.md) vous oriente à travers des communautés open source visant l'innovation et la transformation du service public.

 
