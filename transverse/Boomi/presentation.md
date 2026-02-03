# Introduction

> **Boomi** est une plateforme d’intégration cloud (iPaaS – Integration Platform as a Service)
> 
> Elle permet de connecter des applications, des bases de données et des services cloud afin qu’ils puissent échanger des données automatiquement. Boomi sert d’intermédiaire entre les systèmes
{.is-info}


**Boomi** est une plateforme d’intégration qui permet :

- De connecter des systèmes entre eux

- D’automatiser les échanges de données

- De centraliser la gestion des flux

Elle joue donc le rôle de passerelle entre les applications


# Principe de fonctionnement

Un flux Boomi suit généralement cette logique :

1. Lecture des données (source)

2. Transformation si nécessaire

3. Transmission vers une cible

> Chaque flux est appelé un **processus**
{.is-info}


# Architecture simplifiée

**Boomi** fonctionne principalement en mode cloud

L’exécution des flux se fait via un composant appelé **Atom**

Un **Atom** est un moteur d’exécution et peut être installé :

- Sur un serveur interne

- Dans une machine virtuelle

- Dans le cloud

> C’est l’Atom qui exécute les processus configurés dans **Boomi**
> 
> Pour des besoins plus importants, plusieurs Atoms peuvent être regroupés en **Molécule** (cluster pour haute disponibilité)
{.is-info}



# Éléments principaux d’un processus

Un processus Boomi est composé de :

- **Connecteurs** : permettent de se connecter à des applications (SAP, Salesforce, SQL, REST, FTP…)

- **Profiles** : définissent la structure des données (XML, JSON, CSV…)

- **Maps** : permettent de transformer les données

- **Shapes** : blocs logiques (décision, traitement, routage…)

Le développement se fait via une interface graphique en glisser-déposer


# À quoi sert Boomi ?

**Boomi** sert à connecter des applications entre elles afin qu’elles échangent des données automatiquement

Il permet de :

- Synchroniser des données entre ERP, CRM et autres applications métier

- Connecter des applications cloud et des systèmes internes

- Automatiser des flux sans développement spécifique lourd

- Transformer des données entre différents formats (XML, JSON, CSV…)

- Exposer ou consommer des API

- Orchestrer des processus impliquant plusieurs systèmes

**Boomi** agit comme une passerelle d’intégration entre les applications


# Cas d’usage typiques

**Boomi** est utilisé dans les situations suivantes :

- Synchronisation ERP ↔ CRM

- Intégration d’une application SaaS avec le système interne

- Migration de données entre deux applications

- Intégration B2B (échanges EDI avec des partenaires)

- Centralisation de données issues de plusieurs systèmes

- Exposition sécurisée d’API pour des partenaires ou applications mobiles

Il est particulièrement adapté aux environnements hybrides combinant cloud et infrastructure interne


# Assets 

![logo_boomi_1.png](https://vsod.sharepoint.com/:i:/r/sites/PMS24x7/Documents%20partages/Transverse/Asset_wikijs/Boomi/logo_boomi_1000x1000.png =100x)
