# Step 1 : Qualifier son besoin, analyser l'opportunité du Cloud Native
L’équipe a besoin de comprendre l'opportunité du Cloud Native pour son besoin. La checklist permet l'analyse de la pertinence/adéquation du besoin avec l'offre de service proposée et/ou la roadmap du programme Cloud Pi native (à venir: matrice d'éligibilité). Eligible à un accompagnement : la checklist permet de préparer le RDV de préqualification de la demande (adéquation avec l’offre et/ou le programme) et la légitimité de passer en qualification technique.

## Contexte métier et besoin motivant la demande
-	Quel est le périmètre applicatif concerné (contexte métier/missions) ?
-	Quelle est l’organisation responsable du périmètre applicatif, quelles sont ses missions ?
-	Quelle sont les besoins/motivations pour l’utilisation des éléments de l’offre ? (lesquels ?)
-	Quel est le type de demande: migration vers le cloud (move2cloud), nouveau projet "cloud  native", expérimentation de la chaine de livraison DevSecOps,... ?

## Cadre organisationnel et démarche de consommation de l’offre
-	Quel est la position/le rôle de l’émetteur de la demande ?
-	Dans quel cadre la démarche est-elle soutenue/financée ? (projet, programme, budget de fonctionnement ou expérimentation…)
-	Les sponsors/responsables hiérarchiques sont-ils informés de la démarche ? comment soutiennent-il la démarche ? (mise à disposition de personnels, budget, ressources...)
-	Des équipes sont-elles dédiées ? Si oui, composition des équipes impliquées (nombre de personnes, statut, rôles et compétences…) ?

## Adéquation avec l’offre Cloud Pi Native (sur la base des infos à disposition)
-	Le besoins/motivations sous-jacents ont-ils déjà été qualifiés et quantifiés ? (Irritants, verrous techniques, efforts/travaux à fournir…). 
-	Si oui, sur quels points l’offre Cloud Pi Native a-t-elle été identifié comme apportant de la valeur ? Des points de convergence/des contributions à l’offre et sa raodmap ont-ils déjà été identifiés ? 
-	Quels sont les risques et contraintes à se lancer ? (criticité des applications, contraintes calendaires, disponibilité des équipes…) Quels sont les risques à ne pas se lancer dans le Cloud Native ?

## Vous souhaitez être accompagnés par le programme Cloud Pi Native
- Avez vous pris connaissance de la [politique d'accompagnement](https://github.com/cloud-pi-native/embarquement-autoformation/blob/main/eligibilite.md) et de l'accompagnement auquel votre démarche est éligible?
- Le cas échéant, avez vous pris contact avec le programme pour planifier un RDV de préqualification (cloudpinative-relations@interieur.gouv.fr)? 

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
-	Réalisez vous des tests de couverture, de performance, de sécurité de code à chaque commit ou deploiement ?
-	Quel est l'organisation de votre équipe de developpement ?
-	Combien de personne constitue l'équipe ? Quel est leur profil (testeur, UX, Dev, techlead, ops …)?

## Qualification du périmètre technique
-	Combien de tiers/services/microservice votre application dispose t-elle ?
-	Quels sont les technologies utilisées par votre application ? Frontend, backend, base de donnée, autres ?
-	Quels sont les technologies utilisées par votre application en termes de base de données et stockage ? PosgreSQL, Opensearch, MongoDB, S3, NFS, etc.
-	Comment sont dimensionnées les ressources actuelles de votre application ? 
- Avous déja réalisé une estimation des ressources CPus, RAM, stockage... à provisionner pour votre projet/produit?
-	Quel est l'hébergement utilisé à ce jour ?
-	Utilisez vous une usine logicielle dédiée? Une Forge? laquelle?
-	Votre dépôt de code source est il accessible depuis le RIE ou internet ?
-	Quel sont les environnements utilisés actuellement ? Et ceux souhaitez ?
-	Comment le déploiement de l'application est elle réalisé dans vos environnements de stagging ? 
-	Comment le déploiement de l'application est-il réalisé dans vos environnements de production ?
-	Quel système de supervision applicative utilisez vous ?
-	Votre application est elle fortement couplée ou interconnectée avec le SI ? Quelles données consomme-t-elle ? Au travers de quoi (api, webservice …)
-	Utilisez vous des affinités de sessions ?
-	Les SI et applicatifs concernés sont-ils déja homologués? sur quelle infrastructure? qu'est ce qui a déja été audité?
-	Votre application est elle compatible avec les [12 facteurs](https://12factor.net/fr) établissant la qualité d'un logiciels "as-a-service"? 

## Prérequis techniques impératifs pour le lancement
- utilisez vous de la conteneurisation pour votre projet?
- Utilisez vous la viariabilisation sein de votre projet via variables d'environnement ? Comment gérez vous les secrets ?
- Existe-t-il des besoins de chiffrement des données spécifiques ?
- L’application est elle stateless ? (en dehors du stockage des données type bdd)
- Les images créées dans le cadre du projet sont elles rootless (non root) ? Si non, il y a-t-il une raison particuliere ?
- Les images sont elles standardisé / certifiés par un tiers (redhat, bitnami, etc.) ?
- Le Filesystem des images est il en lecture seule (utilisation de volume pour tous les besoins d'écriture)
- Utilisez vous un gestionnaire de code source ? Lequel ? Est il accessible depuis Internet ou le RIE ?
- Utilisez vous un repo de code pour le déploiement (manifests de déploiement)?
- Quels sont les services (URL) que vous allez exposer sur Internet / RIE / Intranet ?
- Connaissez vous les noms de domaines de votre application ? Tout environnements confondus

## vous souhaitez être accompagné
- Avez vous pris connaissance de la [politique d'accompagnement](https://github.com/cloud-pi-native/embarquement-autoformation/blob/main/eligibilite.md) et de l'accompagnement auquel votre démarche est éligible?
- Le cas échéant, avez vous pris contact avec le programme pour planifier un RDV de qualification technique avec un tech lead du programme (remplissage du [formulaire Démarche Simplifée](https://www.demarches-simplifiees.fr/commencer/cloud-pi-native))? 
-   Avez vous un architecte BACI identifié sur votre projet ?

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

## Réaliser les demandes nécessaires
- [Offre d’hébergement]( https://pi.interieur.rie.gouv.fr/home-dnum/infrastructure-et-dev/hebergement-et-reseau/hebergement/)
- [Demande d'hébergement sur le Cloud Pi](https://resana.numerique.gouv.fr/public/document/consulter/7054535) (section à venir)



# Step 5 : Atteindre les meilleurs standards du "Cloud Native", évolution continue
Comment garantir en continu, l'intégration, le suivi et la pérénnité des bonnes pratiques tout en permettant la maitrise de standards en évolution permanente?
