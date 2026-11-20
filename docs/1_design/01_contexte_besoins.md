# 1. Contexte et Besoins

Ce document constitue le dossier d’analyse des besoins métiers d’UrbanHub attendu dans le cadre de l’EC01. Il présente le contexte, les enjeux Smart City, le périmètre étudié, les acteurs ainsi que les besoins fonctionnels et non fonctionnels majeurs.

Référence : [Fiche apprenant EC01 - Conception et modélisation d’architecture logicielle](<../../docs_src/EC01 - Fiche apprenant - Conception et modélisation d’architecture logicielle - UrbanHub.pdf>).

> Trame à compléter : les indications entre crochets précisent les informations à renseigner. Le niveau de détail attendu reste celui des besoins métiers et de la vision d’ensemble.

## 1.1 Contexte et enjeux

Cette section situe le projet dans son environnement urbain et explicite les enjeux auxquels il doit répondre.

### 1.1.1 Contexte du projet

[À compléter : contexte de la collectivité, situation initiale, problématique rencontrée et rôle attendu du jumeau numérique urbain.]

### 1.1.2 Enjeux Smart City

[À compléter : enjeux urbains concernés et leur importance pour la collectivité. Examiner les domaines cités dans l’EC01 : trafic, pollution, énergie et sécurité.]

### 1.1.3 Objectifs métiers et résultats attendus

[À compléter : objectifs poursuivis, bénéficiaires et résultats observables permettant d’apprécier la réponse aux enjeux.]

## 1.2 Périmètre retenu

Cette section délimite le système étudié et précise ses frontières avec l’environnement existant.

### 1.2.1 Éléments inclus

[À compléter : domaines urbains, services rendus, données IoT et limites géographiques ou organisationnelles retenus pour l’étude.]

### 1.2.2 Éléments hors périmètre

[À compléter : exclusions et limites de l’étude, avec leur justification.]

### 1.2.3 Environnement et interfaces externes

[À compléter : sources de données, systèmes d’information existants et échanges à prendre en compte ; préciser les contraintes connues et les dépendances externes. Une vue de contexte en Mermaid v11 peut être ajoutée si utile.]

## 1.3 Acteurs et parties prenantes

Cette section identifie les parties prenantes, leur rôle et leurs attentes. Elle distingue les acteurs qui interagissent avec le système des parties prenantes concernées par ses résultats ou ses décisions.

[À compléter : examiner les services techniques, élus, opérateurs et citoyens cités dans l’EC01, ainsi que les systèmes externes pertinents pour le périmètre retenu.]

Les identifiants `Axx` permettent de référencer les acteurs dans les besoins et les cas d’utilisation.

| ID  | Acteur / partie prenante | Rôle et responsabilités | Attentes principales | Interaction avec UrbanHub |
| --- | ------------------------ | ----------------------- | -------------------- | ------------------------- |
| A01 | [À compléter]            | [À compléter]           | [À compléter]        | [À compléter]             |

## 1.4 Besoins fonctionnels (BF)

Les besoins fonctionnels expriment ce que le système doit permettre pour répondre aux objectifs métiers. Chaque besoin est rattaché à un acteur, à un domaine et à un résultat attendu vérifiable.

La priorité suit la convention Must / Should / Could (indispensable / important / souhaitable). Les identifiants `BFxx` sont réutilisés dans les scénarios et les cas d’utilisation.

[À compléter : besoins fonctionnels majeurs du périmètre, formulés du point de vue des acteurs ; dupliquer la ligne pour chaque besoin.]

| ID   | Besoin        | Acteur(s) concerné(s) | Domaine       | Priorité                | Résultat attendu / critère de validation |
| ---- | ------------- | --------------------- | ------------- | ----------------------- | ---------------------------------------- |
| BF01 | [À compléter] | [Axx]                 | [À compléter] | [Must / Should / Could] | [À compléter]                            |

## 1.5 Besoins non fonctionnels (BNF)

Les besoins non fonctionnels précisent les qualités attendues et les contraintes qui orientent l’architecture. Chaque exigence doit pouvoir être évaluée ; les valeurs encore inconnues sont signalées comme hypothèses ou points à clarifier.

[À compléter : examiner la volumétrie IoT, la performance et la latence, la sécurité, la disponibilité, la résilience, l’interopérabilité et les contraintes du SI existant, ainsi que l’écoconception, conformément aux recommandations de l’EC01.]

La priorité suit la même convention que pour les besoins fonctionnels. Les identifiants `BNFxx` permettent de relier ces exigences à l’étude de faisabilité et aux choix d’architecture.

| ID    | Famille       | Besoin / exigence                                                 | Acteur porteur | Domaine                | Priorité                | Vérification prévue |
| ----- | ------------- | ----------------------------------------------------------------- | -------------- | ---------------------- | ----------------------- | ------------------- |
| BNF01 | [À compléter] | [À compléter : exigence et cible mesurable ou critère observable] | [Axx]          | [Domaine / transverse] | [Must / Should / Could] | [À compléter]       |

## 1.6 Hypothèses et points à clarifier

Cette section distingue les hypothèses de travail des informations confirmées et recense les questions qui peuvent affecter le périmètre, les besoins ou la conception.

### 1.6.1 Hypothèses de travail

[À compléter : hypothèses retenues, justification, besoins concernés et conséquences sur l’étude si elles ne sont pas confirmées.]

### 1.6.2 Points à clarifier

[À compléter : informations manquantes, partie prenante à consulter et incidence sur les besoins ou l’architecture.]

## 1.7 Scénarios clés à modéliser

Cette section relie les besoins aux scénarios qui seront détaillés dans les diagrammes UML. Elle permet d’identifier les cas d’utilisation clés et de sélectionner au moins un flux IoT complet pour la modélisation du comportement.

[À compléter : scénarios pertinents pour le périmètre, en examinant les exemples de l’EC01 (trafic, qualité de l’air, incidents réseau). Pour le flux IoT choisi, préciser le point de départ et le résultat final attendu.]

| ID   | Scénario      | Acteur(s) | Besoins concernés | Déclencheur et résultat attendu | Flux IoT à détailler    |
| ---- | ------------- | --------- | ----------------- | ------------------------------- | ----------------------- |
| SC01 | [À compléter] | [Axx]     | [BFxx / BNFxx]    | [À compléter]                   | [Oui / Non, à préciser] |
