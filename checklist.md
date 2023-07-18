# Step 1 : Comprendre l'opportunité du Cloud Native pour son besoin
L’équipe a besoin de comprendre l'opportunité du Cloud Native pour son besoin. La checklist permet l'analyse de la pertinence/adéquation du besoin avec l'offre de service proposée et/ou la roadmap du programme Cloud Pi native (à venir: matrice d'éligibilité). Eligible à un accompagnement : la checklist permet de préparer le RDV de préqualification de la demande (adéquation avec l’offre et/ou le programme) et la légitimité de passer en qualification technique.

## Contexte métier et besoin motivant la demande
-	Quel est le périmètre applicatif concerné (contexte métier/missions) ?
-	Quelle est l’organisation responsable du périmètre applicatif, quelles sont ses missions ?
-	Quelle sont les besoins/motivations pour l’utilisation des éléments de l’offre ? (lesquels ?)
-	Quel est le type de demande (move2cloud, nouveau projet, expérimentation, migration...) ?

## Cadre organisationnel et démarche de consommation de l’offre
-	Quel est la position/le rôle de l’émetteur de la demande ?
-	Dans quel cadre la démarche est-elle soutenue/financée ? (projet, programme, expérimentation…)
-	Le sponsor/responsable hiérarchique sont-ils informés de la démarche ? comment soutient-il la démarche ? (mise à disposition de personnels, budget, 
-	Des équipes sont-elles dédiées ? Si oui, composition des équipes impliquées (nombre de personnes, statut, rôles et compétences…) ?

## Adéquation avec l’offre Cloud Pi Native (si elle est possible sur la base des infos à disposition)
-	Le besoins/motivations sous-jacents ont-ils déjà été qualifiés et quantifiés ? (Irritants, verrous techniques, efforts/travaux à fournir…). 
-	Si oui, sur quels points l’offre Cloud Pi Native a-t-elle été identifié comme apportant de la valeur ? Des points de convergence/des contributions à l’offre et sa raodmap ont-ils déjà été identifiés ? 
-	Quels sont les risques et contraintes à se lancer ? (criticité des applications, contraintes calendaires, disponibilité des équipes…) Quels sont les risques à ne pas se lancer dans le Cloud Native ?


# Step 2 : Préparer son projet/produit "cloud native"
L’équipe a besoin de préparer son projet/produit "cloud native" avant de se lancer. La checklist permet de comprendre sur quoi reposent les opportunités du cloud native, quels sont les prérequis pour s’en saisir et préparer un plan projet pour le lancement.
Eligibible à un accompagnement :  la checklist permet de préparer le RDV de qualification technique permettant d’estimer l’effort technique d’appropriation de l’offre et l’accompagnement nécessaire à la réussite du projet.

## Qualification du périmètre organisationnel et fonctionnel
-	Quelles sont les grandes fonctionnalités concernées ? Disposez vous de métriques concernant leur utilisation? 
-	Quel sont les utilisateurs de votre application (usagers, agents, ...)
-	Est-ce une application RIE ou Hors RIE ?
-	L'équipe est elle autonome dans la gestion de son tenant/ses VM ?
-	Les developpements sont il fait sur une usine logicielle en dehors ou au sein du ministere de l'intérieur ?
-	Etes-vous, ou votre équipe famillier avec Kubernetes ?
-	Si oui, avez-vous dejà créé des manifest Kubernetes ?
-	Utilisez vous des outils de communication d’équipe projet ?
-	Réaliser vous des tests de couverture, de performance, de sécurité de code à chaque commit ou deploiement ?
-	Quel est l'organisation de votre équipe de developpement ?
-	Combien de personne constitue l'équipe ? Quel est leur profil (testeur, UX, Dev, techlead, ops …)?

## Qualification du périmètre technique
-	Combien de tiers/services /microservice votre application dispose t-elle ?
-	Quels sont les technologies utilisées par votre application ? Frontend, backend, base de donnée, autres ?
-	Quelles sont les volumetries de ressources pour votre projet ? Volumétrie réseau, stockage,…
-	Combien de ligne de code a l'application ?
-	Quel est l'hébergement utilisé à ce jour ?
-	Utilisez vous une usine logiciel dédié, de la Forge ?
-	Votre dépôt de code source est il accessible depuis le RIE ?
-	Quel sont les environnements utilisés actuellement ? Et ceux souhaitez ?
-	Comment le déploiement de l'application est elle réalisé dans vos environnements de stagging ? 
-	Comment le déploiement de l'application est-il réalisé dans vos environnements de production ?
-	Quel système de supervision applicative utilisez vous ?
-	Votre application est elle fortement couplée ou interconnectée avec le SI ? Quelles données consomme-t-elle ? Au travers de quoi (api, webservice …)
-	Utilisez vous des affinités de sessions ?
-	Les SI et applicatifs concernés sont-ils déja homologués? sur quelle infrastructure? qu'est ce qui a déja été audité?
-	Avous déja réalisé une estimation des ressources CPus, RAM, stockage... à provisionner?

## Prérequis techniques impératifs pour le lancement
-	Utiliser vous la viariabilisation sein de votre projet ? Les secrets sont ils stockés dans un coffre fort (ex. Vault) ?
-	Existe-t-il des besoins de chiffrement des données spécifiques ?
-	L’application est elle stateless ?
-	Les images sont elles rootless (non root) ? Si oui, il y a-t-il une raison particuliere ?
-	Les images sont elles standardisé & certifiés par un tiers (redhat, ou autres) ?
-	Utilisez vous un gestionnaire de code source ? Lequel ?
-	L'application est elle déployé sur des serveurs ou conteneurisé (docker) ?

# Step 3 : Lancer son projet/produit dans un environnement de développement "Cloud native"
Comment se préparer et mettre en place une offre cloud native, chacun à son niveau? La checklist permet d'évaluer le degré de préparation de l'équipe au lancement du projet.

## Préparation de l’équipe porteuse
-	Compréhension des composants de l'offre et des engagements : le CCT Cloud Native et la documentation de l’offre ont-ils été consultés ? Les points d’interrogations ont-ils été soulevés au sein de l’équipe pour les adresser ?
-	Avez-vous, à ce stade, identifié des besoins en formation ? en clarification des exigences, modèle de responsabilités, d’architecture, prérequis…  à respecter ? 
-	Environnements de développement mise en place (cluster k8s, repository, socle technique et console)
-	Déploiement du code applicatifs et code décrivant l'infrastructure
-	Vous etes vous renseigné sur les différentes démarches qui seront à engager pour consommer l’offre « en production » ? (demande d’hébergement, homologation, certificats, …)

# Step 4 : Passer en production, construire dans le respect des normes "Cloud Native"
Comment réaliser le potentiel du cloud native, dans le respect des différentes normes (techniques, organisationnelles, etc.)? 


# Step 5 : Atteindre les meilleurs standards du "Cloud Native", évolution continue
Comment garantir en continu, l'intégration, le suivi et la pérénnité des bonnes pratiques tout en permettant la maitrise de standards en évolution permanente?
