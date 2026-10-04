# Contexte — Yassine Amloul (expériences et projets en STAR)

Document de référence à donner à une IA (ou à relire avant un entretien) pour rédiger CV, lettres et messages sans inventer. Tout ce qui est écrit ici a été dit par Yassine. Quand un résultat n'est pas connu ou pas chiffré, c'est indiqué : il ne faut pas le compléter à la place.

---

## 1. Profil

- **Nom** : **Yassine Amloul** — c'est le nom à écrire sur les CV et lettres (« YASSINE AMLOUL » en-tête de CV). Ne jamais écrire « Ahmed Yassine ». Seuls l'adresse email et l'URL LinkedIn contiennent « ahmed », ce qui est normal.
- **Formation** : 3e année du cycle ingénieur informatique, ENSICAEN (Caen), majeure Cybersécurité & IA, promo 2024-2027
- **Avant** : Bac Sciences Maths (2022), CPGE MPSI (2022-2024), Lycée Mohammed V, Maroc
- **Contact** : +33 6 22 46 91 14 · ahmedyassineamloul@gmail.com · LinkedIn « Ahmed Yassine Amloul » · Caen
- **Recherche** : stage de fin d'études (PFE) de 6 mois à partir de début mars 2027. Domaines : IA, data, cloud, DevOps
- **Recommandations (systématique sur tous les nouveaux CV)** : une section Recommandations, juste avant Compétences techniques, avec la ligne : « **Maxime Bernard**, Manager — NXP Semiconductors (Caen) · maxime.bernard@nxp.com ». Jamais de numéro de téléphone (non fourni dans la lettre). Source : lettre de recommandation PDF fournie par Yassine.

**Date de début** : la date affichée sur le CV (accroche, profil, pied de page) suit **la date de début que l'offre demande** plutôt qu'un « mars 2027 » par défaut, exactement comme pour les langues. Yassine vise mars 2027, mais si une annonce précise un autre mois (ex. février 2027), afficher ce mois-là sur ce CV.

**Langues** : français courant, anglais courant (TOEIC 860/990), arabe langue maternelle
- **Certifications** : AWS Cloud Practitioner (CLF-C02) obtenue ; AWS Solutions Architect – Associate en cours (formation Udemy, pas encore passée) ; Model Context Protocol (MCP), formation certifiée Kloud
- **Recommandation** : lettre de Maxime Bernard, manager RF Integrated Circuit Engineering, NXP Semiconductors Caen

**Règles de rédaction** : dans les messages, écrire « Je suis élève ingénieur » (jamais « Élève ingénieur » seul, ça fait IA). Ton court, naturel, direct. Pas de n8n dans le titre du projet autoMate.

**Longueur** : un CV ne doit jamais dépasser une page. Si le contenu déborde, couper (projets les moins pertinents pour l'offre, puces secondaires) plutôt que réduire la taille du texte.

**Formulation des puces (option 1 — noms d'action)** : toutes les puces du CV, expérience comme projets, commencent par un **nom d'action** mis en gras — Automatisation, Développement, Conception, Intégration, Comparaison, Détection, Construction, Modélisation, Livraison, Présentation, Traitement, Analyse. Jamais de mélange avec des verbes à l'infinitif ou conjugués : la constance prime. La **première puce de chaque bloc doit dire ce qu'est le projet**, pas son contexte : on doit comprendre l'idée dès la première ligne. Les puces suivantes donnent le détail technique puis le résultat. La logique STAR reste appliquée dans cet ordre, mais **sans jamais écrire les étiquettes** « Situation », « Tâche », « Action », « Résultat ».

**Structure de référence (CV modèle « FR / EN » de Yassine, clonée)** : mise en page à un seul flux, police Roboto, en-tête avec **photo à GAUCHE** (26 × 32 mm) puis nom en capitales, sous-titre bleu, ligne contact, ligne LinkedIn + « Stage PFE de 6 mois dès mars 2027 ». Sections dans cet ordre : **Profil, Expérience professionnelle, Projets d'ingénierie & d'innovation, Formation, Certifications, Compétences techniques**. Titres de sections en capitales avec filet bleu ; titre de bloc à gauche et date alignée à droite ; ligne de contexte en italique ; premier mot de chaque puce en gras (nom d'action). Certifications avec statut en bleu (Obtenue / Formation certifiée Kloud / En cours de préparation). Pied de page « Ahmed Yassine Amloul — Curriculum Vitae » et « Stage PFE Mars 2027 ». Dans Formation : écrire **« École d'ingénieur en informatique »** et non « Diplôme d'ingénieur ». **Couleur d'accent : bleu roi `#1d3fc4` pour tous les CV, choix confirmé par Yassine** (pas de variante marine). Cette structure remplace l'ancien format Poppins pour les prochains CV. Le script de génération est fourni dans `modele_cv_structure_bouygues.py`.

**Ordre des sections** (ancienne règle, toujours valable pour les CV au format Poppins) : Accroche, (Certifications si l'offre les met en valeur), Expérience professionnelle, Projets, **Formation**, puis **Compétences** en dernier. La formation vient donc après les projets et avant les compétences, jamais tout en bas.

**Photo** : le CV porte la photo de Yassine, y compris dans les versions ATS — en haut à droite, à côté du bloc nom et coordonnées (largeur 26 mm). Vérifié : la photo n'empêche pas l'extraction du texte par les parseurs ATS (nom, email, téléphone, sections et mots-clés restent tous lisibles).

**Langues** : sur chaque CV, ajouter une ligne « Langues » dans la section Formation, avec le **niveau calqué sur ce que demande l'offre** (ex. offre « anglais avancé, français courant » → « Français (courant) · Anglais (avancé, TOEIC 860/990) · Arabe (langue maternelle) »). Toujours afficher le score TOEIC 860/990 pour étayer le niveau d'anglais. Si l'offre ne précise rien, garder « Anglais (courant, TOEIC 860/990) ».

**Corrections** : quand Yassine demande une correction ou un ajout sur les CV, l'appliquer **uniquement au dernier CV généré (le CV n-1)**. Ne jamais régénérer ni modifier les anciens CV, sauf demande explicite de sa part (« refais aussi les anciens »). La règle vaut aussi pour les ajouts de contenu futurs : ils s'appliquent aux nouveaux CV, pas à ceux déjà faits.

**Nombre de blocs** : maximum **NXP + 3 projets** sur chaque CV (4 blocs au total), jamais plus. On choisit les 3 projets les plus proches de l'offre.

**Certifications sur les offres IA** : sur les CV pour des offres orientées IA (agents, LLM, RAG, data science), ne PAS afficher « AWS Cloud Practitioner — certifié ». Afficher à la place deux lignes : **AWS Solutions Architect – Associate — Formation Udemy certifiée** et **Model Context Protocol (MCP) — Formation certifiée Kloud**. Écrire bien « formation Udemy certifiée » : l'examen AWS SAA-C03 n'est pas passé, donc ne jamais écrire « AWS Certified Solutions Architect ». Sur les offres cloud, DevOps et DevSecOps, le Cloud Practitioner reste affiché.

**Placement des certifications** : quand l'offre porte sur un domaine couvert par une certification (cloud, DevOps, DevSecOps, agents IA/MCP), le bloc **Certifications remonte juste sous l'accroche**, avant l'expérience — pas en bas de page où personne ne le lit. Chaque ligne = intitulé + statut + une phrase disant à quoi elle a servi concrètement. Ne jamais placer une certification dans la section Projets : ce n'est pas un projet, et un ATS l'indexerait mal. Quand l'offre n'a rien à voir avec les certifications, elles restent en bas avec la formation.

**STAR sur les certifications** : la méthode STAR peut aussi s'appliquer aux certifications, selon l'offre. Quand l'offre insiste sur un sujet couvert par une certification (cloud AWS, MCP...), la présenter en STAR : pourquoi je l'ai passée (Situation/Tâche), ce que j'ai appris ou pratiqué (Action), ce que ça m'a permis de faire (Résultat, par exemple un projet réalisé grâce à ces acquis). Ne rien inventer : AWS Cloud Practitioner est obtenue, AWS Solutions Architect – Associate est en cours (pas encore passée), MCP est une formation certifiée Kloud.

---

## 2. Expérience professionnelle

### NXP Semiconductors, Caen — Stage ingénieur, Automatisation & Machine Learning
*Avril – août 2026 · équipe Conception Analogique/RF · manager Maxime Bernard*

- **Situation** : l'analyse du réseau d'alimentation (PDN) des circuits demandait plusieurs jours de travail manuel aux ingénieurs de conception, et l'identification du bloc IP responsable du bruit se faisait à la main.
- **Tâche** : automatiser l'ensemble du flow d'analyse et aider à identifier automatiquement la source du bruit. Besoin ouvert : cadrage, choix techniques et livraison à faire en autonomie.
- **Action** :
  - Scripts d'automatisation du flow PDN dans Cadence (scripts SKILL).
  - Pipeline de traitement du signal sur les données de simulation : détection de régime permanent par DTW, interpolation, fenêtrage temporel, analyse spectrale FFT.
  - Modèle de machine learning non supervisé (k-means sur séries temporelles, scikit-learn, tslearn) pour identifier le bloc IP responsable du bruit.
  - Application Python / PySide6 packagée avec PyInstaller, interfacée avec Cadence.
  - Travail direct avec les ingénieurs de conception pour cadrer le besoin.
- **Résultat** : plusieurs jours de travail manuel ramenés à quelques clics ; outil livré à l'équipe et utilisé quotidiennement ; lettre de recommandation du manager. *Pas de chiffre exact sur le temps gagné au-delà de « plusieurs jours → quelques clics ».*

---

## 3. Projets

### Zelkio — extraction fiable de devis hétérogènes (LLM & VLM)
*Projet industriel ENSICAEN avec l'entreprise Zelkio · en cours depuis septembre 2026*

- **Situation** : l'entreprise cliente doit extraire des données de devis très variés (PDF natifs et scans). Le vrai risque n'est pas l'erreur visible mais l'erreur silencieuse, qui passe inaperçue.
- **Tâche** : comparer des approches d'extraction et mesurer leur fiabilité réelle pour décider quoi automatiser.
- **Modèle utilisé** : **Mistral Large** (à mentionner sur chaque CV qui contient Zelkio, dans la ligne de contexte du projet : « LLM : Mistral Large »).
- **Action** :
  - Comparaison OCR + LLM avec sortie JSON contrainte vs approche VLM multimodale qui lit directement la mise en page.
  - Détection des erreurs silencieuses : self-consistency, LLM-as-judge, règles métier.
  - Protocole d'évaluation : jeu de test annoté, métriques par champ et par famille de documents, courbe risque/couverture.
  - Points réguliers avec le client.
- **Résultat** : *projet en cours, pas de résultat final à annoncer.* Ne pas prétendre à des chiffres de performance.

### autoMate — système multi-agents qui transforme des procédures en workflows exécutables
**Formulation voulue par Yassine (à utiliser sur les nouveaux CV)** : autoMate est *une solution multi-agents autonome qui aide les entreprises à savoir comment automatiser leurs tâches, à partir de leurs documents (PDF, modes opératoires) et de leurs bases de données, en générant l'automatisation correspondante*.

*Gemini 3 Hackathon (Google DeepMind), international · février 2026*

- **Situation** : les équipes ont des procédures internes (PDF, modes opératoires, logs) qui décrivent des tâches répétitives jamais automatisées.
- **Tâche** : construire en temps limité un prototype qui lit une procédure et produit l'automatisation correspondante.
- **Action** :
  - Architecture multi-agents avec LangGraph et LangChain, modèle Gemini 3.
  - Pipeline RAG sur les documents métier.
  - Documentation technique récupérée en temps réel via MCP (Context7), pour que le code généré s'appuie sur de vraies API et pas sur la mémoire du modèle.
  - Génération d'un workflow n8n exécutable, importable et lançable tel quel.
- **Résultat** : prototype fonctionnel livré pendant le hackathon. *Aucun classement ou prix annoncé : ne pas en inventer.*

### Pipeline de qualification et d'audit de données financières par IA
*Projet orienté data · juin 2026*

- **Situation** : des données financières brutes issues d'API de marché contiennent des anomalies courantes (doublons, valeurs manquantes, sauts de prix aberrants) qu'il faut détecter avant toute exploitation.
- **Tâche** : construire une chaîne d'extraction, de stockage et de contrôle qualité, avec un agent IA qui qualifie automatiquement les incidents.
- **Action** :
  - Extraction de données financières (cours d'actions) via une API publique en Python.
  - Conception d'un schéma de base SQL pour stocker les historiques de façon optimisée.
  - Développement de scripts Python et de requêtes SQL pour détecter les anomalies.
  - Intégration d'un agent IA sur un flux LangGraph analysant les journaux d'erreurs et classifiant le type d'incident qualité.
  - Configuration de l'agent pour proposer un niveau de priorité et une piste de résolution.
  - Rédaction de la documentation technique (architecture bout en bout, fonctionnement multi-agents).
- **Résultat** : chaîne complète construite, de l'extraction API à la qualification automatique des incidents par l'agent. *Pas de chiffre communiqué (volume traité, taux de classification correcte) : à demander à Yassine avant de l'écrire sur un CV.*
- **Technologies** : Python, SQL, API de marché, LangGraph, LLM.

### Tableau de bord d'analyse d'impact des anomalies métier
*Projet orienté data · mars 2026*

- **Situation** : les erreurs techniques d'un référentiel de produits financiers (incohérences de schémas, transactions non référencées) ont un impact métier que les équipes ne visualisent pas.
- **Tâche** : relier les anomalies techniques à leur conséquence financière, et la rendre lisible pour des non-techniciens.
- **Action** :
  - Génération d'un jeu de données simulant un portefeuille de produits financiers avec erreurs volontaires.
  - Nettoyage et consolidation via des procédures SQL, dans un environnement relationnel strict.
  - Développement d'un tableau de bord interactif Power BI sur l'état global de la qualité des données.
  - Calcul et affichage de KPI traduisant l'impact financier direct des erreurs sur la valorisation du portefeuille.
  - Formulation de règles de gestion métier pour corriger les erreurs et limiter leur impact.
  - Rédaction de la documentation fonctionnelle reliant erreurs techniques et conséquences métier.
- **Résultat** : tableau de bord livré, reliant chaque anomalie technique à son impact financier sur la valorisation du portefeuille. *Pas de chiffre communiqué : à demander à Yassine avant de l'écrire sur un CV.*
- **Technologies** : Python, SQL, Power BI ou Oracle Apex.

### Suricata + LLM local — détection en temps réel avec explication des alertes
**Titre à utiliser sur les nouveaux CV** : « Détection de vulnérabilités en temps réel avec LLM local — Suricata & ELK ».
**À mentionner sur les nouveaux CV** : le LLM local (Ollama, qwen2.5:3b) est exécuté **dans une sandbox, pour des raisons de sécurité**, en plus de n'avoir aucune donnée sortante.

*Projet 2A ENSICAEN, équipe de 4 · mars 2026*

- **Situation** : les alertes d'un IDS sont difficiles à lire pour un non-spécialiste, et envoyer les logs à un service externe pose un problème de confidentialité.
- **Tâche** : construire une chaîne de détection dont les alertes sont expliquées en langage clair, sans qu'aucune donnée ne sorte de la machine.
- **Action** :
  - Chaîne Suricata → Filebeat → Elasticsearch → Kibana (collecte, parsing, indexation, dashboards temps réel).
  - Règles de détection écrites à la main, validées avec des attaques simulées (Scapy, SQLMap) : SQLi, SYN flood, scan de ports.
  - LLM local (Ollama, qwen2.5:3b) qui explique chaque alerte en langage clair.
- **Résultat** : chaîne complète fonctionnelle, aucune donnée sortante. *Ne pas écrire « 100 % des attaques détectées » : non défendable.*

### Datathon Normandie — croiser offre de formation et logement
*Région Normandie / DataLab Normandie · en équipe · novembre – décembre 2025*

- **Situation** : les décideurs régionaux manquent d'une vue croisée entre l'offre de formation du Calvados et les conditions de logement.
- **Tâche** : construire en équipe une plateforme d'aide à la décision à partir de données open data hétérogènes.
- **Action** :
  - Collecte et croisement de jeux de données ouvertes (formation, logement, territoire) : nettoyage, normalisation des référentiels géographiques, jointures.
  - Modèle de classification XGBoost avec feature engineering.
  - Restitution cartographique interactive pensée pour des non-techniciens.
- **Résultat** : projet présenté devant un jury de décideurs régionaux à Caen. *Détails du jury (lieu exact, fonctions) à vérifier avant de les citer. Pas de classement annoncé.*

### Plateforme Kubernetes & GitOps sur AWS
*Projet personnel · mars 2026*

- **Situation** : volonté de maîtriser une chaîne complète du commit à la production, sans intervention manuelle sur les serveurs.
- **Tâche** : provisionner l'infrastructure et déployer automatiquement une application.
- **Action** :
  - Infrastructure as code avec Terraform sur AWS : VPC, sous-réseau public, internet gateway, security groups restreints (80/443/22), instance EC2, backend S3 pour le state.
  - CI GitHub Actions déclenchée à chaque push : build de l'image Docker, push vers un registre, mise à jour automatique du tag dans un dépôt Git de configuration séparé.
  - CD GitOps avec ArgoCD sur un cluster K3s, qui synchronise le cluster à chaque nouvelle version.
  - Routage du trafic avec Nginx Ingress Controller.
- **Résultat** : déploiement de bout en bout sans accès manuel au serveur. *Date du projet non précisée.*

### Pipeline DevSecOps & observabilité applicative
*Projet personnel · juin 2026*

- **Situation** : la sécurité est souvent vérifiée trop tard, après le déploiement.
- **Tâche** : intégrer des contrôles de sécurité dans le pipeline et superviser l'application en continu.
- **Action** :
  - Analyse statique avec SonarCloud (bugs, mauvaises pratiques, secrets) et scan de l'image Docker avec Trivy avant le build.
  - Le pipeline s'arrête sur vulnérabilité critique et bloque le déploiement.
  - Monitoring Prometheus sur le cluster (latence, mémoire, volume de requêtes), dashboards Grafana, alertes Alertmanager vers un canal d'équipe sur dépassement de seuil.
  - Validation des fichiers Terraform et Dockerfile contre les bonnes pratiques.
- **Résultat** : pipeline qui bloque réellement un déploiement non conforme, avec supervision et alerting en place.

### Mini Google Drive — déploiement AWS automatisé de bout en bout
*Projet personnel · octobre 2025*

- **Situation** : apprendre à livrer une application complète (front, back, stockage, déploiement) de façon reproductible.
- **Tâche** : construire un clone simplifié de Google Drive et automatiser sa mise en ligne.
- **Action** :
  - Application React / Node.js conteneurisée avec Docker.
  - Stockage Amazon S3 avec politique IAM au moindre privilège.
  - Pipeline GitLab CI/CD : build → tests → push de l'image → déploiement automatisé sur EC2.
- **Résultat** : zéro intervention manuelle entre le commit et la mise en ligne. *Projet de type tutoriel/apprentissage : ne pas le présenter comme un produit.*

### GPT-Life — simulateur de vie avec agent IA local
*OpenAI Open Model Hackathon (avec Hugging Face, NVIDIA, Ollama, vLLM, LM Studio) · équipe de 3 · septembre 2025*

- **Situation** : hackathon sur les modèles open-weight, avec des contraintes de temps et de matériel.
- **Tâche** : construire une application où un « citoyen » a son environnement, sa personnalité et interagit avec le monde via un agent IA local.
- **Action** :
  - Déploiement local du modèle gpt-oss:20b, très gourmand en CPU/GPU.
  - Contournement des limites matérielles par des choix d'optimisation sous pression de temps.
  - Travail en équipe de 3.
- **Résultat** : application réalisée pendant le hackathon. *Aucun prix annoncé. Retiré des CV récents, sauf pour les postes sur l'IA locale ou les agents.*

---

## 4. Compétences (ce qui est défendable en entretien)

- **Langages** : Python (principal), C, C++, Java, JavaScript, SQL, Shell
- **Frameworks / API** : FastAPI (utilisé par Yassine, contexte précis non donné)
- **Data / BI** : Power BI, SQL (schémas, procédures, requêtes de contrôle qualité), détection d'anomalies, KPI métier
- **IA / data** : LLMs, RAG, agents multi-agents (LangChain, LangGraph), MCP, Ollama, scikit-learn, tslearn, XGBoost, séries temporelles, feature engineering, évaluation (LLM-as-judge, self-consistency)
- **Cloud / DevOps** : AWS (EC2, S3, IAM, VPC, Lambda), Terraform, Docker, Kubernetes / K3s, ArgoCD, GitHub Actions, GitLab CI/CD, Prometheus, Grafana, Alertmanager, SonarCloud, Trivy
- **Cyber** : Suricata, ELK, Wireshark, Scapy, TCP/IP, SSL/TLS
- **Outils** : Cadence (scripts SKILL), PySide6, Git

---

## 5. Ce que Yassine n'a PAS fait (à ne jamais afficher comme compétence)

Ces trous sont revenus dans plusieurs offres. Les assumer honnêtement en entretien vaut mieux que de les cacher.

- **Azure** (AKS, Azure DevOps, Azure OpenAI, Copilot Studio) : expérience AWS uniquement
- **Selenium, Playwright, Appium** (tests automatisés web/mobile)
- **Octopus Deploy**
- **Langages HDL** : Verilog, SystemVerilog, VHDL, Verilog-AMS, UVM, SVA
- **PyTorch / JAX** en profondeur, entraînement sur clusters GPU, publications
- **GitHub sur le CV** : choix explicite de ne pas l'afficher (à reconsidérer, bloquant pour certains postes)
- **FinOps**, habilitation de sécurité défense : rien à revendiquer

À vérifier avant de les défendre : pandas/NumPy (à maîtriser si le CV Data est envoyé), « Python typed/tested » et « CI pipelines » (à ne garder que si c'est vrai), orthographe de « Kloud ».

---

## 6. Recherche en cours (résumé)

- **Marché** : recrutements cadres informatiques en baisse. Environ 4 emplois sur 10 se trouvent dans l'entreprise du PFE, d'où l'intérêt de viser les entreprises produit et les grands groupes tech.
- **Cibles prioritaires** : NXP (offre NFC Caen, candidat interne), OVHcloud, Orange, BNP Paribas, Crédit Agricole (CIB et « Entreprise IA »), Mistral, Cadence, Airbus, Framatome, Chanel, Wavestone, BearingPoint.
- **Wavestone** : un premier refus automatique via le portail ; nouvelle candidature via recommandation interne (Carlos Dos Santos) sur « AI for Digital Foundations », test AssessFirst à passer.
- **Rythme fixé** : 4 candidatures sur offres + 1 spontanée + 10 invitations LinkedIn + 2 relances par jour, 5 jours par semaine.
- **CV à envoyer** : version ATS (une colonne) pour les portails type Workday ; version design (deux colonnes) pour un envoi direct à un humain.

---

## 7. Mises à jour de format (modèle de référence : CV Atos Data Science & IA, fait par Yassine)

Ces points **remplacent** les règles précédentes quand elles se contredisent. Ils s'appliquent aux nouveaux CV uniquement.

- **Ordre des sections** : Profil, Expérience professionnelle, Projets d'ingénierie & d'innovation, Formation, **Compétences et langues**, Recommandations, Certifications.
- **Zelkio** : placé dans Expérience professionnelle, sous NXP, sous le titre « Projet industriel — Évaluation de la fiabilité de sorties IA » (ligne de contexte : « ENSICAEN en partenariat avec Zelkio · LLM : Mistral Large »). Il ne compte plus dans les 3 projets.
- **NXP** : le stage mentionne la **méthode Agile** et l'**architecture MVC** (application Python/PySide6), ainsi que la documentation. Le traitement du signal (DTW, interpolation, FFT) est cité dans la puce k-means.
- **Langues** : la ligne « Langues » passe de Formation à la section « Compétences et langues ». Ajouter une ligne « Qualités » (ex. : Motivé, travail en équipe, communication).
- **Recommandations** : écrire « Lettre de recommandation de Maxime Bernard, Manager — NXP Semiconductors (Caen), disponible sur demande ». Plus d'adresse email.
- **Certifications** : en dernière section, sauf si l'offre porte sur un domaine couvert par une certification.
- **Projets** : puces plus courtes (1 à 2 par projet) pour garder une seule page.
- **Réponses de Claude** : donner uniquement le nom de l'offre et le nom du CV, sans commentaire. Noms de fichiers courts.
- **Photo LinkedIn** : `photo_linkedin.png` (visage dézoomé, espace en bas).
