\# Exercice 6 : Étude de Cas - The Phoenix Project

Ce livre, écrit par Gene Kim, Kevin Behr et George Spafford, est une fiction d'entreprise qui dépeint les défis quotidiens d'une organisation TI dysfonctionnelle et sa transformation grâce à l'application des principes DevOps.



1\. Résumé des Problèmes Identifiés

Le problème central de l'entreprise Parts Unlimited est le chaos autour de son projet critique, The Phoenix Project. Les problèmes identifiés sont systémiques et fréquents dans les organisations traditionnelles :



Silos Organisationnels : Des murs épais existent entre le Développement (Dev), les Opérations (Ops) et la Sécurité (Sec). Chaque équipe a des objectifs différents, conduisant à des conflits et des frictions.



Absence de Visibilité du Flux de Travail : L'équipe est submergée par des urgences (travail non planifié). Il est impossible de savoir où se trouve un travail dans la chaîne de valeur (goulot d'étranglement).



Dépendance à l'Héros (Brent) : L'organisation repose sur quelques individus critiques (comme Brent) qui détiennent l'essentiel des connaissances. Lorsque ces personnes sont sollicitées, tout s'arrête.



Déploiements Douloureux : Les mises en production sont rares, manuelles, terrorisantes et échouent régulièrement, nécessitant des rollbacks coûteux.



Manque de Mesure : La performance n'est pas mesurée en fonction de la valeur métier, mais uniquement en fonction de l'activité (ex. : nombre de tickets fermés).



2\. Solutions DevOps Proposées : Les Trois Voies

Les solutions proposées sont structurées autour des Trois Voies du DevOps, qui forment le cadre théorique du livre :



A. La Première Voie : L'Amélioration du Flux de Travail (Système)

Objectif : Accélérer le flux de travail de Dev vers Ops.



Pratiques : Utilisation des principes Lean pour la gestion des files d'attente (Work In Progress - WIP) et l'identification des goulots d'étranglement.



Exemple dans le Livre : Limiter le nombre de projets en cours pour concentrer les ressources sur l'achèvement du travail. Rendre visible l'état du travail.



B. La Deuxième Voie : L'Amélioration des Boucles de Rétroaction (Feedback)

Objectif : Créer un cycle rapide, fréquent et bidirectionnel.



Pratiques : Surveillance (Monitoring) pour détecter rapidement les problèmes. Apprentissage continu à partir des échecs.



Exemple dans le Livre : Mettre en place des outils de surveillance et donner aux développeurs la responsabilité et les outils pour monitorer leur code en production.



C. La Troisième Voie : L'Amélioration de l'Apprentissage et de la Culture (Expérimentation)

Objectif : Créer une culture d'expérimentation, de prise de risque et d'apprentissage continu.



Pratiques : Automatisation pour créer des environnements reproductibles. Partage de connaissances et culture de la non-blâme.



Exemple dans le Livre : Utiliser l'Infrastructure as Code (IaC) pour que les environnements soient créés de manière fiable et ne dépendent pas des connaissances tacites.



3\. Application à un Contexte Réel

Le cas de The Phoenix Project s'applique à toute organisation avec :



Délai de Mise sur le Marché Lent : Si les fonctionnalités prennent des mois à atteindre les clients.



Haute Taux d'Échec : Si les déploiements échouent plus de 15 % du temps.



Conflits Inter-Équipes : Si Dev blâme Ops (et vice-versa) en cas de panne.



Application Concrète : La première étape dans une organisation similaire serait d'appliquer la Première Voie : cartographier le flux de valeur (de l'idée à la production) et utiliser des outils de gestion de projet (comme Jira ou Trello) pour limiter le WIP et rendre les goulots d'étranglement visibles.

