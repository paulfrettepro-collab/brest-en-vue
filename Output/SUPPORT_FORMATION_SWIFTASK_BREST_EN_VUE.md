# Support de Formation : Devenir Expert SwiftAsk & Créateur d'Agents
**Programme "Brest en Vue"**

---

## 1. Synthèse de Cadrage

**Contexte :**  
Cette formation s'inscrit dans le programme **"Brest en Vue"**, visant à acculturer et outiller les agents publics et équipes territoriales sur l'IA. Elle cible des utilisateurs ayant déjà une pratique de SwiftAsk (> 6 mois) pour les amener vers une autonomie complète (création d'agents).

**Objectifs Pédagogiques Globaux :**
À l'issue de la formation, les participants seront capables de :
1.  Maîtriser les fonctionnalités avancées de SwiftAsk pour des tâches complexes.
2.  Identifier et différencier les 3 niveaux d'agents IA (N1, N2, N3).
3.  Concevoir, paramétrer et déployer des agents IA adaptés aux processus métiers de la collectivité.
4.  Contribuer à la bibliothèque d'agents partagée pour automatiser 80% des tâches récurrentes.

**Découpage par Journée :**
*   **Jour 1 (Compréhension & Exploration) :** Consolidation des acquis, découverte des cas d'usage avancés et analyse de la structure des 6 agents types.
*   **Jour 2 (Création & Application) :** Atelier pratique de construction d'agents sur des cas réels du service public, tests et déploiement.

**Public Cible :**
*   Agents publics, équipes informatiques, managers.
*   **Prérequis :** Utilisation régulière de SwiftAsk depuis > 6 mois.
*   **Groupe :** 8 à 12 personnes.

**Indicateurs de Réussite :**
*   **Savoir :** Score > 80% aux quiz de connaissances (J1 & J2).
*   **Savoir-faire :** Chaque participant a créé au moins 1 agent fonctionnel (N2 ou N3) répondant à un besoin métier réel.

---

## 2. Plan Détaillé du Support de Slides – Jour 1
**Thème :** Expertise SwiftAsk et Typologie des Agents
**Volume estimé :** ~40-50 slides

### Module 1 : Introduction & Ancrage (09h00 - 10h00)

*   **Slide 1 : Titre - Formation Expert SwiftAsk**
    *   *Objectif :* Accueillir et poser le cadre.
    *   *Contenu :* Titre, Logo "Brest en Vue", Date, Noms formateurs.
*   **Slide 2 : Tour de table & Attentes**
    *   *Objectif :* Briser la glace et jauger le niveau réel.
    *   *Format :* Discussion. "Votre prénom, votre service, votre usage actuel de SwiftAsk (1 mot)".
*   **Slide 3 : Le programme "Brest en Vue"**
    *   *Objectif :* Rappeler le sens de la démarche.
    *   *Points clés :* Autonomie des équipes, culture de la donnée, amélioration du service public.
*   **Slide 4 : Objectifs de la formation (J1 & J2)**
    *   *Objectif :* Clarifier le contrat pédagogique.
    *   *Points clés :* De l'utilisateur au créateur. Objectif 80% d'autonomie.

### Module 2 : SwiftAsk - Au-delà du Chat (10h00 - 11h00)

*   **Slide 5 : Rappel des fondamentaux (Rapide)**
    *   *Objectif :* Nivellement express.
    *   *Points clés :* Prompting de base (Contexte, Tâche, Format), Gestion de l'historique.
*   **Slide 6 : Fonctionnalités avancées : Le traitement de fichiers**
    *   *Objectif :* Maîtriser l'ingestion de documents.
    *   *Points clés :* Formats acceptés (PDF, Excel, Word), limites de taille, bonnes pratiques (OCR).
    *   *Note formateur :* Insister sur la confidentialité des données (RGPD) dans le contexte public.
*   **Slide 7 : Fonctionnalités avancées : La recherche Web vs Base de connaissances**
    *   *Objectif :* Savoir quand connecter l'IA au web.
    *   *Points clés :* Hallucinations vs Sources vérifiées. Quand utiliser le mode "Recherche" ?
*   **Slide 8 : Démo Live - Analyse croisée**
    *   *Format :* Démonstration.
    *   *Contenu :* Uploader 2 PDF (ex: 2 délibérations) et demander une synthèse comparative.

### Module 3 : Les 6 Agents Types - Niveaux N1 & N2 (11h15 - 12h30)

*   **Slide 9 : La Pyramide des Agents (Concept)**
    *   *Objectif :* Présenter la classification N1/N2/N3.
    *   *Visuel :* Pyramide. Base = N1 (Simple), Milieu = N2 (Structuré), Sommet = N3 (Expert).
*   **Slide 10 : Agent N1 - L'Assistant (Reformulation/Correction)**
    *   *Objectif :* Définir l'agent N1 type.
    *   *Points clés :* Tâche unique, pas de contexte complexe. Ex: "Corrige l'orthographe de ce mail".
*   **Slide 11 : Agent N1 - L'Extracteur**
    *   *Objectif :* Cas d'usage extraction.
    *   *Points clés :* Transformer du non-structuré (texte) en structuré (tableau).
*   **Slide 12 : Cas Pratique Flash (15 min)**
    *   *Format :* Exercice individuel.
    *   *Sujet :* "Nettoyage de notes brutes" (Voir section Cas Pratiques).
*   **Slide 13 : Agent N2 - L'Analyste (Instructions métier)**
    *   *Objectif :* Introduire le "System Prompt".
    *   *Points clés :* On donne un rôle et une méthode. Ex: "Tu es un juriste, analyse ce contrat selon ces 3 critères".
*   **Slide 14 : Agent N2 - Le Rédacteur (Style et Format)**
    *   *Objectif :* Standardisation de la production.
    *   *Points clés :* Respecter une charte graphique ou un ton "Service Public".

### Module 4 : Les Agents N3 & Architecture (14h00 - 16h00)

*   **Slide 15 : Agent N3 - L'Expert (Connaissances)**
    *   *Objectif :* L'agent qui "sait" des choses.
    *   *Points clés :* Ajout de documents de référence (Règlements intérieurs, Code des marchés publics).
*   **Slide 16 : Agent N3 - Le Scénariste (Logique conditionnelle)**
    *   *Objectif :* Gestion de tâches complexes.
    *   *Points clés :* "Si X alors Y". Chaînage de pensées (Chain of Thought).
*   **Slide 17 : Anatomie d'un Agent**
    *   *Objectif :* Le modèle de structure.
    *   *Visuel :* Schéma (Identité + Contexte + Tâches + Format + Contraintes).
*   **Slide 18 : Cas Pratique Guidé (45 min)**
    *   *Format :* Atelier binôme.
    *   *Sujet :* "Analyseur de CV anonyme" (Voir section Cas Pratiques).

### Module 5 : Clôture J1 (16h30 - 17h00)

*   **Slide 19 : Quiz de validation J1**
    *   *Format :* Interactif (Kahoot ou main levée).
*   **Slide 20 : Recap & Préparation J2**
    *   *Objectif :* Transition.
    *   *Consigne :* "Pour demain, pensez à un processus pénible de votre quotidien".

---

## 3. Plan Détaillé du Support de Slides – Jour 2
**Thème :** Atelier de Création & Déploiement
**Volume estimé :** ~30-40 slides

### Module 1 : Méthodologie de Création (09h00 - 10h30)

*   **Slide 1 : Accueil & Réveil pédagogique**
    *   *Objectif :* Réactiver les neurones.
    *   *Activité :* "Le pitch de l'ascenseur" : Résumez un agent N2 en 30 secondes.
*   **Slide 2 : De l'idée au Prompt Système**
    *   *Objectif :* Méthode de design.
    *   *Points clés :* Définir le problème -> Définir le rôle -> Définir les étapes.
*   **Slide 3 : L'art du "Few-Shot Prompting"**
    *   *Objectif :* Technique avancée pour guider l'IA.
    *   *Points clés :* Donner des exemples (Exemple 1 : Entrée -> Sortie) pour calibrer l'agent.
*   **Slide 4 : Les variables et les champs dynamiques**
    *   *Objectif :* Rendre l'agent réutilisable.
    *   *Points clés :* Utiliser des placeholders `[INSÉRER TEXTE ICI]`.

### Module 2 : Atelier "Build" - Partie 1 (10h45 - 12h30)

*   **Slide 5 : Consignes de l'atelier**
    *   *Objectif :* Lancer la production.
    *   *Contenu :* Choisir un sujet parmi vos besoins ou la liste proposée. Objectif : Un agent N2 fonctionnel à midi.
*   **Slide 6 : Template de conception (Canvas)**
    *   *Format :* Slide affichée en permanence.
    *   *Contenu :* Nom, Rôle, Contexte, Instructions étape par étape, Format de sortie.
*   **Slide 7 : Coaching tournant**
    *   *Note formateur :* Slide "Au travail". Le formateur passe de groupe en groupe.

### Module 3 : Atelier "Build" - Partie 2 & Optimisation (14h00 - 15h30)

*   **Slide 8 : Retours d'expérience intermédiaires**
    *   *Objectif :* Partage de blocages.
    *   *Discussion :* "Mon agent hallucine", "Il oublie une consigne".
*   **Slide 9 : Techniques de débogage**
    *   *Objectif :* Corriger les agents.
    *   *Points clés :* Renforcer les contraintes négatives ("Ne fais jamais..."), réduire la température (créativité).
*   **Slide 10 : Finalisation des Agents**
    *   *Objectif :* Polissage.
    *   *Consigne :* Ajouter une base de connaissance (fichier) si pertinent (Passage en N3).

### Module 4 : Déploiement & Gouvernance (15h45 - 16h30)

*   **Slide 11 : Partager son agent**
    *   *Objectif :* Collaboration.
    *   *Points clés :* Bibliothèque partagée SwiftAsk. Qui a accès ?
*   **Slide 12 : Maintenance et Responsabilité**
    *   *Objectif :* Éthique et durabilité.
    *   *Points clés :* L'humain reste responsable de la validation (Human in the loop). Mise à jour des documents de référence.
*   **Slide 13 : Showcase (Présentation des résultats)**
    *   *Format :* Démo.
    *   *Contenu :* 2 ou 3 participants présentent leur agent finalisé.

### Module 5 : Clôture de la formation (16h30 - 17h00)

*   **Slide 14 : Quiz de validation J2**
*   **Slide 15 : Bilan & Suite du parcours**
    *   *Objectif :* Ouverture.
    *   *Points clés :* Prochaines étapes "Brest en Vue". Support disponible.
*   **Slide 16 : Feedback (ROTI)**
    *   *Format :* QR Code pour questionnaire satisfaction.

---

## 4. Cas Pratiques (Intégrés aux slides)

### Cas Pratique 1 : Le "Nettoyeur de Notes" (J1 - Niveau N1)
*   **Objectif :** Créer un agent simple de reformulation/structuration.
*   **Durée :** 15 min.
*   **Énoncé :** Vous revenez d'une réunion de quartier avec des notes prises à la volée sur smartphone (télégraphiques, fautes, abréviations). Créez un agent qui transforme ce texte en un compte-rendu formel et structuré.
*   **Input :** Un texte "brouillon" fourni (ex: "Problème voirie rue Pasteur... riverains colère... besoin intervention services techniques avant mardi").
*   **Critères de réussite :** Le résultat est un texte rédigé, sans fautes, avec des titres (Problématiques, Actions, Délais).
*   **Variante Avancée :** Demander à l'agent de générer automatiquement un email à envoyer au responsable voirie basé sur ce CR.

### Cas Pratique 2 : L'Analyste d'Appel d'Offres (J1 - Niveau N2)
*   **Objectif :** Créer un agent d'analyse documentaire avec instructions.
*   **Durée :** 45 min.
*   **Énoncé :** Vous devez analyser 3 réponses à un marché public (fictif). Créez un agent qui lit le PDF de réponse et remplit une grille d'analyse prédéfinie.
*   **Input :** 1 fichier PDF (Offre prestataire) + Une grille de critères (Prix, Délai, RSE).
*   **Critères de réussite :** L'agent sort un tableau comparatif ou une note de synthèse respectant strictement les critères demandés.
*   **Variante Facile :** Juste extraire le prix et le délai.

### Cas Pratique 3 : L'Agent FAQ RH (J2 - Niveau N2/N3)
*   **Objectif :** Créer un agent basé sur une connaissance métier (Règlement intérieur).
*   **Durée :** 1h (Atelier Build).
*   **Énoncé :** Le service RH est inondé de questions sur le télétravail et les congés. Créez un agent capable de répondre aux questions des agents en citant l'article du règlement.
*   **Input :** Le fichier "Guide du temps de travail" (PDF fictif).
*   **Critères de réussite :** L'agent répond juste à la question "Combien de jours de télétravail ai-je droit si je suis à 80% ?" en citant la source.
*   **Variante Avancée :** L'agent doit refuser de répondre si la question ne concerne pas les RH (Guardrails).

### Cas Pratique 4 : Le Générateur de Délibération (J2 - Niveau N3)
*   **Objectif :** Agent complexe de rédaction administrative.
*   **Durée :** 1h (Atelier Build).
*   **Énoncé :** Rédiger un projet de délibération pour le conseil municipal à partir d'une fiche projet technique.
*   **Input :** Une fiche projet (Word) + Un modèle de délibération vierge (Structure légale).
*   **Critères de réussite :** L'agent produit un texte qui respecte le formalisme légal ("Vu le code...", "Considérant que...") et intègre les données du projet.

---

## 5. Questionnaires d’évaluation

### Quiz J1 : Fondamentaux & Typologie (Extrait)
1.  **Q : Quelle est la différence principale entre un agent N1 et N2 ?**
    *   *R :* N1 = Tâche simple sans instruction complexe / N2 = Instructions structurées et rôle défini.
2.  **Q : (Vrai/Faux) Je peux envoyer un fichier contenant des données de santé nominatives à SwiftAsk pour analyse.**
    *   *R :* **Faux.** (Rappel RGPD et sensibilité des données, sauf si instance locale sécurisée et validée DPO, par défaut prudence).
3.  **Q : Pour forcer l'IA à respecter un format CSV, où dois-je mettre l'instruction ?**
    *   *R :* Dans le prompt système ou à la fin du prompt utilisateur (Format de sortie).
4.  **Q : Qu'est-ce qu'une "hallucination" de l'IA ?**
    *   *R :* Une réponse inventée par l'IA qui semble plausible mais est factuellement fausse.
5.  **Mini-Cas :** Vous voulez résumer un PDF de 200 pages. L'agent répond "Fichier trop long". Que faites-vous ?
    *   *R :* Découper le fichier ou utiliser un agent spécifique capable de traiter de longs contextes (si disponible).

### Quiz J2 : Création & Bonnes Pratiques (Extrait)
1.  **Q : À quoi sert le "Few-Shot Prompting" ?**
    *   *R :* À donner des exemples à l'IA pour qu'elle comprenne le modèle attendu.
2.  **Q : Si mon agent est trop "créatif" et invente des règles, quel paramètre dois-je ajuster (si accessible) ou quelle instruction donner ?**
    *   *R :* Baisser la température ou ajouter l'instruction "Tiens-toi strictement aux documents fournis".
3.  **Q : (Vrai/Faux) Un agent N3 peut exécuter des actions en dehors de SwiftAsk (ex: envoyer un mail tout seul) sans configuration API spécifique.**
    *   *R :* **Faux.** Il génère le texte du mail, mais ne l'envoie pas (sauf intégration spécifique non couverte ici).
4.  **Q : Quelle est la première étape avant de construire un agent ?**
    *   *R :* Définir le besoin et vérifier que l'IA est la bonne solution (Méthodologie).
5.  **Mini-Cas :** Votre agent RH répond correctement mais sur un ton très familier ("Salut mec, pour tes congés..."). Où est l'erreur ?
    *   *R :* Dans le "Tone & Style" du prompt système. Il faut spécifier "Adopte un ton professionnel et administratif".

---

## 6. Recommandations Pédagogiques

**Rythme & Animation :**
*   **Règle du 20/80 :** 20% de théorie, 80% de pratique. Ce sont des utilisateurs confirmés, ils s'ennuieront avec trop de slides.
*   **Live Coding :** Le formateur ne doit pas juste montrer des slides, il doit construire un agent en direct devant eux (et faire des erreurs pour montrer comment corriger).
*   **Peer Learning :** Favoriser le travail en binôme (un "tech" + un "métier" si possible) pour les ateliers de création.

**Personnalisation "Brest en Vue" :**
*   **Vocabulaire :** Utilisez les termes "Usager", "Citoyen", "Délibération", "Arrêté", "Note de service". Évitez le jargon "Client" ou "Business".
*   **Ancrage Réel :** Demandez aux participants d'apporter leurs propres fichiers (anonymisés) pour le J2. Rien ne vaut de travailler sur ses propres problèmes.

**Points de Vigilance :**
*   **Hétérogénéité :** Même "confirmés", les niveaux varient. Prévoyez des défis bonus pour les rapides.
*   **Effet "Magique" :** Rappelez constamment que l'IA n'est pas magique, elle est statistique. L'humain doit toujours vérifier (surtout dans le service public où l'erreur a des conséquences légales).

---

## Améliorations Optionnelles

### Évaluation Diagnostique (Avant J1)
*   Envoyer un formulaire 1 semaine avant : "Quel est votre dernier prompt complexe ?", "Avez-vous déjà utilisé des variables ?". Cela permet d'ajuster le niveau du J1.

### Fiche Mémo "Structure d'un Prompt Système"
*   **Rôle :** "Tu es un expert en..."
*   **Contexte :** "Nous sommes une collectivité territoriale..."
*   **Tâche :** "Ta mission est de..."
*   **Contraintes :** "Ne dépasse pas 200 mots, utilise un ton neutre..."
*   **Format :** "Réponds sous forme de liste à puces..."
*   **Exemple :** "Voici un exemple de ce que j'attends..."

### Plan Export PowerPoint (Extrait J1)

| Slide # | Titre | Contenu Visuel | Notes Formateur |
| :--- | :--- | :--- | :--- |
| 10 | Agent N1 - L'Assistant | Icône Robot + Crayon. Ex: "Reformule ce mail" | Insister sur la simplicité. Pas de mémoire complexe nécessaire. |
| 11 | Agent N1 - L'Extracteur | Entonnoir : Texte vrac -> Tableau Excel | Très utile pour les enquêtes publiques ou les retours formulaires. |
| 12 | Cas Pratique Flash | Chronomètre 15 min + Consigne | Passer dans les rangs. Vérifier que personne n'est bloqué. |
