# Rendu du projet Final pour le passage de la certification d'Administrateur d'Infrastructures Sécurisées

## Projet AOTDS (Death Star)

*Diagrammes de l'infrastructure (état des lieux et pistes d'améliorations) réalisé avec Draw.io*
*Templates de présentations Gamma utilisés*

# Bloc 1 - Manage and secure infrastructure

Ce projet est obligatoire pour valider le bloc 1 de la certification **Administrateur d'Infrastructures Sécurisées**. L'objectif est de démontrer vos compétences en tant qu'ingénieur en **cybersécurité** à travers deux parties : la description du réseau et la détection des vulnérabilités, puis la construction d'une stratégie de **Gouvernance, Gestion des Risques et Conformité (GRC)** en cybersécurité.

## Partie I : Description du Réseau et Détection des Vulnérabilités

### Topologie et Description du Réseau

- **Dessiner une topologie** de l'infrastructure AOTDS.
- **Décrire le réseau** : expliquer comment l'infrastructure est construite, y compris les hôtes virtualisés s'il y en a.

### Rapport sur les Vulnérabilités

- Fournir un **rapport détaillé** des vulnérabilités détectées sur l'infrastructure.

## Partie II : Stratégie de Gouvernance, Gestion des Risques et Conformité (GRC) en Cybersécurité

### Stratégie GRC

Construire une stratégie GRC centrée sur la cybersécurité, couvrant trois aspects :

1. **Technique** : Mesures et contrôles à mettre en place pour protéger les actifs.
2. **Organisationnel** : Établir des rôles et responsabilités clairs, la gestion des politiques, et intégrer les pratiques de cybersécurité dans tous les processus organisationnels.
3. **Confidentialité** : Intégrer les considérations de confidentialité, en veillant à ce que les données personnelles soient traitées conformément aux lois et réglementations sur la confidentialité comme le RGPD.

## Livrables Attendus

### Présentation PowerPoint

La présentation doit contenir :

1. **Diagramme de la topologie** découverte dans le laboratoire AOTDS.
2. **Explication détaillée** de la topologie du réseau, divisée en sections logiques si nécessaire.
3. **Stratégie GRC en cybersécurité**, rapportant les mauvaises pratiques et proposant des mesures correctives dans les domaines technique, organisationnel et de confidentialité.

### Format et Structure

- Le diagramme de topologie doit tenir sur une **diapositive**.
- L'explication de la topologie doit être détaillée et répartie sur plusieurs diapositives.
- Mentionnez et expliquez les hôtes virtualisés dans l'infrastructure.
- La présentation finale doit compter environ **15 à 25 diapositives**.

## Aide et Ressources

### Outils pour la Topologie

- Excalidraw
- PowerPoint / Google Slide
- EdrawMax
- PacketTracer
- Google Image pour les icônes (routeur, etc.)

### Ressources pour la Stratégie GRC

- **NIST Cybersecurity Framework**
- **ISO 27002**
- **ISO 27005**
- **Référentiel Général de Sécurité**
- **Infrastructure Hardening**
- **Checklist for Securing and Hardening your Server Environment**

### Conseils et Recommandations

- Utilisez les mauvaises pratiques identifiées comme base pour décrire de meilleures pratiques.
- Concentrez-vous uniquement sur l'aspect cybersécurité du cadre GRC.
- Revoyez les modules **From Zero to IT Hero** et **Blue Team** pour vous aider à construire votre projet.

## Synthèse du Cours

Le projet consiste à gérer et sécuriser une infrastructure en deux parties : description et détection des vulnérabilités, puis construction d'une stratégie GRC en cybersécurité. Les étudiants doivent dessiner une topologie, décrire le réseau, fournir un rapport de vulnérabilités, et élaborer une stratégie GRC couvrant les aspects techniques, organisationnels et de confidentialité. Les livrables incluent une présentation PowerPoint avec un diagramme de la topologie, des explications détaillées, et une stratégie GRC. Utiliser des outils de dessin et s'appuyer sur des standards comme le NIST et ISO pour structurer la stratégie.

# Bloc 2 - Patch Infrastructure

https://app.jedha.co/course/project-presentation-cybfs/project-bloc-2-cybfs

Ce projet est obligatoire pour valider le bloc 2 de la certification **Administrateur d'Infrastructures Sécurisées**. L'objectif est de corriger un système mal configuré dans l'infrastructure AOTDS en se basant sur les vulnérabilités identifiées.

## Objectifs

### Sélection et Correction d'une Vulnérabilité

- **Sélectionner une vulnérabilité** trouvée lors de l'analyse.
- **Démontrer comment la corriger** (**patcher**).
- **Expliquer l'amélioration** apportée dans un rapport d'évolution du système.

### Livrables Attendus

Pour ce projet, vous devez fournir :

1. Une **présentation PowerPoint** structurée comme suit :
    - Présentation de la **vulnérabilité**.
    - **Démonstration du patch**.
    - **Rapport d'évolution** du système.

## Structure de la Présentation

### Format et Contenu

- La présentation doit compter environ **15 diapositives**.
- Utilisez le modèle de diapositives de Jedha disponible pour créer des diapositives esthétiques.
- La présentation doit viser une durée de **10 minutes**.

### Conseils et Outils

- **Profondeur de présentation** : Expliquez en détail comment vous avez patché la mauvaise configuration.
- **Illustrations** : Fournissez soit une vidéo, soit des captures d'écran de votre patch.
    - Utilisez des outils comme **Vimeo Extension** ou **Screen Recorder**.
- **Plan de Continuité d'Activité (BCP)** : Si le patch implique une interruption de l'infrastructure, proposez des recommandations sur la continuité du service sur 1-2 diapositives.

## Synthèse du Cours

Ce projet consiste à corriger une vulnérabilité dans l'infrastructure AOTDS pour valider le bloc 2 de la certification Administrateur d'Infrastructures Sécurisées. Les étudiants doivent sélectionner une vulnérabilité identifiée, démontrer comment la corriger et expliquer l'amélioration apportée. Les livrables incluent une présentation PowerPoint de 15 diapositives avec des démonstrations et des recommandations pour assurer la continuité du service en cas d'interruption due au patch. Utiliser des outils pour capturer le processus de patch est recommandé pour illustrer la correction.

<aside>
⚠️ 1 vuln + 1 rémédiation (partch de l’infrastructure, hardening)

</aside>

# Bloc 3 - Information Security Audit

https://app.jedha.co/course/project-presentation-cybfs/project-bloc-3-cybfs 

Ce projet est obligatoire pour valider le bloc 3 de la certification **Administrateur d'Infrastructures Sécurisées**. L'objectif est de réaliser un audit de sécurité basé sur l'infrastructure AOTDS et de produire plusieurs livrables détaillés. Il faudra fournir des preuves des **vulnérabilités**, évaluer les **risques** et recommander des **améliorations**.

## Objectifs

### Identification des Vulnérabilités

- **Preuves des vulnérabilités** : Apporter des preuves tangibles des failles de sécurité identifiées.
- **Évaluation des risques** : Analyser les risques associés à chaque vulnérabilité trouvée.
- **Recommandations** : Proposer des solutions pour remédier aux failles.

### Livrables Attendus

Pour ce projet, vous devrez fournir :

1. **Rapport de test d'intrusion** en format PDF contenant :
    - Le **périmètre** du test
    - Présentation des **vulnérabilités** avec leur **risque** associé
    - Preuves des **vulnérabilités** trouvées
    - **Recommandations** et **remédiations**
2. **Rapport de compromission** en format PDF contenant :
    
    <aside>
    ⚠️ IoC, forensic, s’il y a a Dump de RAM, screen pendant que la machine a été compromise
    
    </aside>
    
    - **Indicateurs de Compromission (IoCs)**
        
        → Wazuh, .pcap et au mieux dump process (si docker) ou dump de ram étudiés avec Volatility
        
    - **Tactiques, Techniques et Procédures (TTPs)**
    - **Contre-mesures**
3. Une **PSSI (Politique de Sécurité des Systèmes d'Information)** simple en format PDF
4. Une **présentation PowerPoint** soulignant les points clés des trois rapports

### Important

- **Sélection des vulnérabilités** : Si vous trouvez plus de 3 vulnérabilités, sélectionnez les plus critiques. Il n'est pas nécessaire de détailler plus de dix vulnérabilités dans votre rapport.

## Préparation de la Présentation

Pour la certification, visez une présentation de 20 minutes. Utilisez le modèle de diapositives de Jedha pour créer des diapositives esthétiques, que ce soit sur Google Slide ou PowerPoint.

## Aide et Ressources

Pour structurer vos rapports de compromission et de test d'intrusion, suivez les recommandations du module de rapport du cours. La PSSI doit être basée sur les problèmes identifiés dans l'infrastructure AOTDS. Vous pouvez utiliser les templates fournis pour vous guider dans l'élaboration de votre PSSI.

## Synthèse du Cours

Ce projet final en cybersécurité vise à évaluer et à améliorer la sécurité de l'infrastructure AOTDS. Les étudiants doivent identifier les vulnérabilités, évaluer les risques et proposer des solutions. Les livrables comprennent un rapport de test d'intrusion, un rapport de compromission, une PSSI et une présentation PowerPoint. L'accent est mis sur l'apport de preuves tangibles, l'analyse des risques, et la formulation de recommandations claires et pratiques. Pour structurer le travail, il est conseillé de suivre les modules de cours et d'utiliser les templates fournis.

# Quelques ressources :

## Dockers utilisés

[hub.docker.com](https://hub.docker.com/r/tleemcjr/metasploitable2)

[hub.docker.com](https://hub.docker.com/r/davidaavilar/bwapp)

## Rapport de compromission

https://github.com/soufianetahiri/ransomware_Incident_Response_FR/blob/main/README.md

[nvlpubs.nist.gov](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf)

[www.ossir.org](https://www.ossir.org/paris/supports/2018/2018-05-15/2018-05-15_ExaTrack.pdf)

[www.corvid.co.uk](https://www.corvid.co.uk/hubfs/documents/Compromise-assessment-report-CORVID.pdf)

[cycraft.com](https://cycraft.com/download/CyCraft_DataSheet_Compromise_Assessment_v1.2.pdf)

[www.corvid.co.uk](https://www.corvid.co.uk/hubfs/documents/Compromise-assessment-report-CORVID.pdf)
