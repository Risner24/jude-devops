Diagramme du cycle de vie DevOps

flowchart LR

&nbsp;   A\[Plan] --> B\[Code]

&nbsp;   B --> C\[Build]

&nbsp;   C --> D\[Test]

&nbsp;   D --> E\[Release]

&nbsp;   E --> F\[Deploy]

&nbsp;   F --> G\[Operate]

&nbsp;   G --> H\[Monitor]

&nbsp;   H --> A



Description détaillée des phases

1\. Plan



Acteurs : Product Owner, Lead Developer

Outils : Jira, Confluence, Miro

Livrables : User stories, backlog, schémas d’architecture

Durée estimée : 1 à 2 semaines par sprint



2\. Code



Acteurs : Développeurs

Outils : VS Code, GitHub, Node.js

Livrables : Code source, commits versionnés

Durée estimée : Toute la durée du sprint (continu)



3\. Build



Acteurs : Développeurs, Pipeline CI

Outils : GitHub Actions, Docker

Livrables : Builds automatisés, artefacts compilés, images Docker

Durée estimée : Automatisé (quelques minutes)



4\. Test



Acteurs : QA, Devs, pipeline CI

Outils : Jest, Playwright, Postman, GitHub Actions

Livrables : Rapports de tests, logs

Durée estimée : Quelques minutes à quelques heures selon les tests



5\. Release



Acteurs : DevOps Engineer, Release Manager

Outils : GitHub Actions, SemVer, Changelog Generator

Livrables : Version taguée, changelog, artefacts prêts à déployer

Durée estimée : 10–30 minutes



6\. Deploy



Acteurs : DevOps Engineer

Outils : Kubernetes, Docker, Helm, AWS

Livrables : Application en production ou staging

Durée estimée : Quelques minutes grâce à l’automatisation



7\. Operate



Acteurs : SRE, DevOps

Outils : Kubernetes, Nginx, AWS Load Balancers

Livrables : Application opérationnelle, logs système

Durée estimée : Continu



8\. Monitor



Acteurs : SRE, DevOps, Support

Outils : Prometheus, Grafana, ELK Stack, Sentry

Livrables : Alertes, dashboards, métriques

Durée estimée : Continu


# Diagramme du cycle de vie DevOps



!\[Cycle DevOps](./exercice-3-cycle-de-vie.png)



