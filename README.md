---
description: Plateforme de santé
---

# Cahier de charges

{% hint style="info" %}
Il vous est demandé de répondre partiellement à un appel d'offres.&#x20;

En tant que futur directeur technique, vous devrez réfléchir au domaine d'application et formuler des politiques et des stratégies garantissant la qualité de l'offre proposée.&#x20;

Il vous est également demandé de communiquer clairement cette stratégie par le biais de deux supports : oral et écrit.&#x20;

Vous n'avez peut-être pas entendu parler de certaines exigences décrites dans cet appel d'offres. Vous devrez donc **effectuer vos propres recherches**.&#x20;

Lors des sessions consacrées aux questions/réponses, vous pourrez, bien entendu, poser des questions à l'intervenant.&#x20;

Cet évaluation a donc les objectifs suivants :

* Apprendre et comprendre le vocabulaire associé au thème de la Qualité dans le domaine des technologies de l'information.
* Réfléchir et appliquer vos nouvelles connaissances à un exemple concret.
* S'entraîner à effectuer ses propres recherches
* S'entraîner à synthétiser et à communiquer sa stratégie
{% endhint %}

## Présentation générale

FeedMyHealth est une marque leader dans le domaine des soins aux patients, accréditée par le Ministère de la Santé, est largement reconnue par les professionnels de la santé pour sa qualité et sa fiabilité. Fondée en 1995, elle a fourni avec succès des services d'information à des hôpitaux dans toute la France et l'Europe.

## Description du projet

FeedMyHealth est une application mobile innovante qui permet aux utilisateurs de tenir un journal de leurs habitudes alimentaires et d'enregistrer les effets de leurs repas sur leur santé mentale et physique.

Il ne s'agit pas d'une application de régime. Elle existe pour aider les patients qui souffrent de maladies physiologiques et psychologiques liées à la nutrition.

L'objectif principal est de fournir un journal quotidien où les utilisateurs peuvent enregistrer leurs repas (pas les calories), ainsi que leurs sentiments, émotions ou autres sensations psychologiques et physiologiques qu'ils peuvent ressentir pendant et après un repas.

Grâce à l'IA, nos algorithmes sont capables de détecter des schémas qui peuvent conduire à des diagnostics de pathologies, ou révéler des tendances qui pourraient aider un psychologue ou un psychiatre à mieux traiter ses patients.

La plateforme se compose de 3 interfaces utilisateurs :

* L'application mobile (Android et iOS) : l'interface patient pour enregistrer les repas quotidiens, les émotions, etc.
* L'interface web du médecin : interface d'accès aux données enregistrées par les patients.
* L'interface administrative interne : pour une utilisation interne à FeedMyHealth.

Les composants de traitement des données et d'IA sont déjà en place et ne font pas partie de ce projet.

Vous devez concevoir la plateforme destinée aux utilisateurs, y compris :

* Trois interfaces fronts (2 basées sur le web, 1 application mobile)
* Les API qui servent les interfaces
* Le modèle de données et le stockage
* L'architecture de production



## Instructions aux soumissionnaires

{% hint style="info" %}
Vous jouerez le rôle d'une entreprise qui répond à cet appel d'offre. Constituez votre entreprise en formant un **groupe d'exactement quatre membres.**

Merci de renseigner les coordonnées de votre groupe sur cette feuille : [https://docs.google.com/spreadsheets/d/1A5bcnrcy\_7DlVCUYhr2O6zbjOCD943AcFtw6XwewO\_g/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1A5bcnrcy_7DlVCUYhr2O6zbjOCD943AcFtw6XwewO_g/edit?usp=sharing)
{% endhint %}

### Contenu et planning de l'appel d'offres

Le déroulement de l’appel d’offres est prévu selon le planning suivant :

| Date                    | Activité                       |
| ----------------------- | ------------------------------ |
| 12 mai 2025             | Ouverture de l'appel d'offres  |
| 12 mai 2025 - mi-séance | Session de question / réponses |
| 13 à 14 mai 2025        | Session de question / réponses |
| 15 mai 2025             | Soutenances                    |

### Processus d'évaluation des soumissionnaires

L'évaluation se fera en deux parties :

* Un rapport écrit (document PDF), contenant les sections suivantes :
  * Une section " à propos de nous " contenant le numéro du groupe et les noms des coéquipiers.
  * Un chapitre par exigence listée dans le chapitre suivant de l'appel d'offres
* Une présentation/défense d'une durée maximale de 15 minutes avec 10 minutes de questions (total 25 minutes).
  * La soutenance se fera devant le client, moi, l'intervenant
  * accompagnée de supports visuels à projeter via le vidéoprojecteur.
  * La présence et la contribution de toute l'équipe est obligatoire.

Le rapport écrit et la soutenance sera soumis le 15 mai 2025. Le créneau précis de votre groupe sera marqué une semaine avant la soutenance, dans le document suivant : [https://docs.google.com/spreadsheets/d/1Zdx9xEGzMMcR1m4bzxOuFuexKEIrL3WZLBEwuUxIbS4/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1Zdx9xEGzMMcR1m4bzxOuFuexKEIrL3WZLBEwuUxIbS4/edit?usp=sharing)

## Description des exigences

...

{% hint style="info" %}
Ici, nous disposons généralement d'une liste de critères pour les produits logiciels proprement dits. Pour les besoins de ce projet, nous laissons de côté la spécification technique et passons aux parties associées à la qualité.
{% endhint %}

...

### EG-21 : Modalités de travail

FeedMyHealth est une entreprise qui évolue rapidement et qui préfère réagir rapidement aux besoins changeants de ses clients ainsi qu'à l'évolution des conditions du marché et des paramètres juridiques.

Nous avons besoin d'une description de votre philosophie de développement (de préférence "Agile"), y compris une description de la manière dont nous collaborerons pour garantir un produit de haute qualité qui réponde à nos besoins dans les délais impartis.

### EG-22 : Architecture de conception

Ayant développé et entretenu des plateformes logicielles pendant de nombreuses années, FeedMyHealth est conscient qu'une bonne conception technique se traduit par un code facile à entretenir, à corriger et à faire évoluer. L'un des principaux objectifs est de fournir une solution facilement extensible avec peu de frais supplémentaires.

Nous vous demandons de décrire les architectures de conception standard que vous utiliserez lors du développement de nos applications. Il peut s'agir de l'un des modèles suivants, ou d'un autre s'il est correctement décrit et motivé :

* "Clean"
* "Onion"
* "Hexagonal"
* ...

Nous vous demandons de fournir une explication détaillée de la manière dont votre architecture se traduit par un code maintenable et évolutif, y compris au moins un exemple de code spécifique dans le langage de votre choix.



### EG-23 : Automatisation des processus de qualité

Nous exigeons un niveau d'évolution qui garantisse, dans la mesure du possible, un niveau de qualité constant pour tous les produits mis sur le marché.

Cela signifie qu'une régression est considérée comme inacceptable et doit être évitée à tout prix.

Veuillez décrire les processus que vous mettrez en œuvre pour vous assurer que tout nouveau code est conforme aux spécifications et qu'aucun nouveau bogue n'est introduit accidentellement dans la plate-forme.

Ces processus de validation devraient être automatisés.



{% hint style="info" %}
**Indice**

Vos procédures de développement devraient inclure au moins des tests unitaires et des tests d'intégration, automatisés par votre logiciel de version, et déclenchés par certains événements dans votre base de code (exemple, demande de fusion). Dans votre réponse, décrivez quels événements déclenchent quels processus et, idéalement, fournissez un exemple pratique en utilisant GitLab ou Github.

Plus d'information sur **l'intégration continue** (ou **CI**) [ici](https://docs.glassworks.tech/devops/ci/001-introduction).
{% endhint %}



### EG-24 : Architecture de production

L'infrastructure proposée doit être robuste et résister aux risques éventuels :

* défaillance de serveurs individuels
* défaillance d'un centre de données
* résistance aux DDoS ou aux pics d'utilisation

L'objectif principal est de fournir un temps de disponibilité de 99,99 % à nos utilisateurs.

Veuillez expliquer votre architecture de déploiement, en précisant notamment :

* le fournisseur de Cloud que vous comptez utiliser et les différents composants (machines virtuelles, load-balancers, etc) de votre architecture. Une conception visuelle est attendue
* Une brève explication de la manière dont un éventuel problème est évité ou géré de manière transparente par votre architecture.
* Si vous utilisez une solution d'orchestration (ex. Kubernetes), veuillez fournir des détails sur sa mise en place.

### EG-25 : Environnements

Veuillez inclure une brève description de vos différents environnements dans la chaîne de production (développement, test, production).

Décrivez qui y aura accès et comment les différents environnements sont configurés pour garantir un pipeline de validation avant qu'une nouvelle version ne soit mise à la disposition du public.

### EG-26 : Déploiement continue

Idéalement, les nouvelles versions seront publiées à l'aide de processus automatisés afin de :

* réduire le risque d'erreurs lors d'un déploiement manuel
* réduire les temps d'arrêt (rolling updates) : les services existants continuent de fonctionner pendant les mises à jour.&#x20;

Veuillez décrire comment cela sera réalisé, idéalement avec un exemple fonctionnel utilisant GitHub ou GitLab.

{% hint style="info" %}
**Indice**

Il s'agit généralement d'un déploiement continu, qui peut être configuré à l'aide, par exemple, de GitLab Pipelines et de Kubernetes. Plus d'informations [ici](https://docs.glassworks.tech/devops/cd/010-cd).
{% endhint %}

### EG-27 : Sécurité

Veuillez décrire les mesures de sécurité que vous mettrez en œuvre, en tenant particulièrement compte du fait que nous stockerons des **données médicales.**

Veuillez décrire les mesures de sécurité que vous mettrez en œuvre :

* Quelles sont les normes à respecter pour ce type de données ?
* présentez la liste des risques potentiels et des procédures d'atténuation qui seront mises en œuvre (au moins 3).

### EG-28 : Gestion des risques

Outre la cybersécurité (traitée au point précédent), veuillez fournir une liste des autres risques qui seront anticipés par votre plateforme. Il peut s'agir, entre autres, de :

* Perte de données (exemple : incident au centre de données)
* Perte de services / de disponibilité
* Suppression/corruption malveillante de données par un membre validé du personnel
* Perte d'un membre du personnel possédant des connaissances spécialisées
* Divulgation de données sensibles par votre personnel
* ...

### EG-29 : Adhérence aux normes de qualité

Veuillez donner un aperçu de la manière dont votre plate-forme/organisation respecte les normes de l'industrie (ne donnez qu'un aperçu) :

* ISO9001
* ISO27001

### EG-30 : SLA et KPIs

Veuillez fournir votre garantie de service (SLA - service level agreement), et mentionner les KPI (key performance indicators) qui nous permettront d'évaluer, sur une base régulière, si votre SLA a été respecté ou non.

Vous devez inclure au moins :

* le temps de fonctionnement (disponibilité) de vos plateformes
* le temps de réponse aux incidents
* le temps de réponse aux questions non urgentes

### EG-31 : Gestion des incidents

Veuillez fournir votre stratégie de gestion des incidents, qui devrait inclure :

* Comment vous gérez le retour d'information des utilisateurs (forums, chat-bots, helpdesk, tickets).
* Plan de reprise après sinistre : en cas d'interruption majeure du service, comment les services seront-ils rétablis et dans quel délai ?
