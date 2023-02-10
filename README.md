Les ressources rassemblées ici constituent une introduction à l’offre que nous proposons 1) une sensibilisation aux enjeux adressés 2) des ressources de formation à destination des populations concernées 3) des guides et versions de démo pour prendre en main et s'acculturer. 

Dans une logique d’amélioration continue, vous pouvez proposer vos commentaires en:
- Faisant des pulls request sur le repository;
- Faisant des issues.

# Comprendre les enjeux de la transformation numérique
### Un "nouveau monde" logiciel a émergé
Ces dernières années la puissance d'intermédiation du numérique a dévoré une part croissante des activités humaines. Transport, banque, finance, sociabilité, hotellerie, logistique, sécurité, identité, culture, divertissement... deviennent numériques.  Les origines et les conséquences d'un tel changement ne sont pas seulement technologiques : elles touchent aux organisations, périmètres de responsabilités et normes sous-jacentes (y compris culturelles). C'est un changement de paradigme, un ["nouveau monde logiciel"](https://github.com/Yoarmi/dso-formation/blob/patch-1/1-enjeux_nouveau_monde.md). 

### Le service public mis au défi
Dans ce nouveau cadre, certains produits/services deviennent des « normes de fait »: les décisions les concernant, leurs caractéristiques, impactent des millions d'utilisateurs et posent des [défis importants aux organisations publiques](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.3-defi_service_public.md). Pour rester au service de leurs usagers et agents, en particulier sur leurs missions régaliennes, ces dernières doit se doter des moyens de maitriser les outils (de production, opération et maintenance) et les normes (techniques ou non: neutralité, RGPD, accessibilité,...) du "nouveau monde" numérique.

### Un socle technique et organisationel pour "remettre l'usager au centre"
Pour inclure au maximum les usagers, ce projet de transformation numérique implique de travailler en [mode produit](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.1-approche_devsecops.md). Mais Nous considérons qu'il doit également mieux inclure les développeurs, usagers trop souvent oubliés. La voie privilégiée que nous proposons pour répondre à cela repose sur [les approches DevSecOps](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.1-approche_devsecops.md) et les [technologies cloud native](https://github.com/Yoarmi/dso-formation/blob/patch-1/1.2-technologies-cloud-native.md) (conteneurisation, API, microservices, DevOps). Le socle proposé ici est la "matérialisation" de cette approche.


# Parcours de formation à destination des populations concernées
Nous souhaitons faciliter l'action de l'ensemble des acteurs désireux de contribuer à la transformation numérique du service public à travers deux questions 1) quels sont les principes directeurs et modèles d'organisations nécessaires à l'utilisation du socle que nous proposons? 2) quels sotn les concepts techniques sous jacents? 3) comment me former pour l'utiliser? 

### Cadre technique et écosystème du socle proposé
Nous vous invitons à prendre connaissance des principes et exigences exposés dans le [cadre de cohérence technique Cloud Pi Native (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native), découlant de la doctrine cloud au centre de l’Etat et permettant de tirer le plein bénéfice des principes du “cloud first”, du mode produit, du fonctionnement en équipe intégrée (DevSecOps) et de l’agilité.

Pour la mise en place, nous proposons un « [modèle organisationnel](https://github.com/Yoarmi/dso-formation/blob/patch-1/2-modele_organisation.md) » à l'écosystème des parties prenantes du socle : distribution des rôles, définition des périmètres de responsabilité, processus à mettre en place pour livrer et gérer des produits numériques tout au long de leur cycle de vie.

### Parcours de formation et concepts sous-jacents
Pour la formation, nous distinguons les populations concernées par 4 grands types de responsabilités:
- « [Produit numérique](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.1-parcours-produit.md) » : personnes qui élaborent de nouveaux produits numériques et/ou assurent la gestion de leur cycle de vie. Ils sont responsables de leur développement, mise en production, MCO/évolution, migration, etc. Ce sont les développeurs, les opérateurs, les architectes, … 
- « [Services & systèmes (SRE)](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.2-parcours_systeme.md) » : personnes qui assurent l’intégrité des services et systèmes nécessaires au développement et à l'opération des produits numériques, tout au long de leur cycle de vie: pipelines de livraison DevSecOps, services d’hébergement, génération d’environnements, etc. Ce sont les system teams, les équipes d’ingénierie de fiabilité des sites (SRE, Site Reliability Engineering), les forges, les opérateurs de plateformes (IaaS, PaaS, XaaS, ...).
- « [Projets et ressources opérationnelles](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.3-parcours_projet.md) » : personnes qui pilotent les équipes de développement ou de gestion des opérations. Ils sont responsable de la meilleure utilisation des ressources (humaines et techniques) pour la menée d'un projet. Il s'agit du pilotage/chefferie de projets/programmes/MOE ou d'unités de réalisation, bureau d'étude, etc.
- « [Décision/stratégie](https://github.com/Yoarmi/dso-formation/blob/patch-1/2.4-parcours_strategie.md) » : personnes qui prennent des décisions et se portent garantes de l’engagement des organisations sur des sujets touchant au numérique. Cela peut être aussi des personnes chargés de les conseiller, de donner des recommandations, délivrer des mandats ou réaliser des arbitrages concernant les finalités, moyens et modes d’organisation. Il s’agit de la décision stratégique, du pilotage/gouvernance des organisations, de direction générales ou de directions de la stratégie métiers, achats, RH, etc.
 
# Prise en main et acculturation à l'utilisation de l'offre
Nous mettons à disposition ici des souches logicielles, de la documentation, des formations "hands-on" (par la pratique). Nous pensons que toute personne désireuse de contribuer à la transformation numérique du service public (agent, citoyen, industriel du numérique, représentant d'institutions publiques... ) doit pouvoir expérimenter les outils mis à disposition pour la mener à bien.

### Kits de prise en main et documentation
Afin de tirer le meilleur parti des guides, kit, et outils proposés, nous conseillons de s'être préalablement familiarisé avec les concepts présentés dans parcours de formation. Ceci, afin de permettre la prise en main des composantes de l'offre avec un maximum d'autonomie: 
- [Guide technique » : pour la prise en main du socle technique](https://github.com/dnum-mi/dso-socle);
- [Guide technique » : pour la prise en main de la console](https://github.com/dnum-mi/dso-console).

### Contextes d'utilisation particuliers
Nous distinguons deux contextes d'utilisation particuliers de l'offre pour lesquels nous renvoyons à des ressources spécifiques:
- Contexte interministériel: pour l'utilisation au sein d'un ministère nous renvoyons au [catalogue de services](https://pi.minint.fr/home-dnum/cloud-%cf%80/qui-sommes-nous/cloud-native/) et au [cadre de cohérence technique (CCT)](https://github.com/dnum-mi/CCT-Cloud-Native);
- Contexte communautaire: l’offre est mise à disposition en open source pour favoriser l'appropriation des technologies « Cloud Native » et l’émergence de standards du numérique public. La section ["comment contribuer?"](https://github.com/Yoarmi/dso-formation/blob/patch-1/4-contribuer.md) vous oriente à travers des communautés open source visant l'innovation et la transformation du service public.

 
