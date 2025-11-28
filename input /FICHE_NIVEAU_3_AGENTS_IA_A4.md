# 🔧 Niveau 3 : Développement d'Agents IA

**Public :** 200 collaborateurs | **Durée :** 3 jours (21h) | **Période :** Août-Novembre 2026 | **Prérequis :** Niveau 2 + 6 mois autonomie

## Objectif de la formation

Maîtriser le cycle complet de création d'agents IA : diagnostiquer les opportunités d'automatisation avec la méthodologie "Où perdez-vous du temps ?", comparer et choisir les bons LLM (GPT-4, Claude, Mistral, Llama), concevoir des agents avec prompts système et orchestration, assurer la conformité RGPD/IA Act, découvrir les SLM (IA sobre), et endosser le rôle de diffuseur/ambassadeur IA.

## Programme

**Jour 1 (9h-17h) - Fondamentaux :** Quiz diagnostic (30min) | Méthodologie "Où perdez-vous temps ?" (1h30) | Comparaison LLM (GPT-4, Claude, Mistral, Llama - 1h) | Architecture agents (1h30) | Prompts système (1h) | Atelier prompts (1h30)

**Jour 2 (9h-17h) - Création :** Orchestration agents (1h) | Atelier création agent complet (3h) | Déploiement & tests (1h30) | 10 techniques optimisation (1h30)

**Jour 3 (9h-17h) - Conformité & Diffusion :** Risque réglementaire RGPD/IA Act (1h) | SLM - IA sobre (45min) | Formateur interne (1h30) | Rôle diffuseur (1h) | Responsabilité complète (45min) | Badge personnalisé (30min) | Showcase final (1h30)

## 7 Compétences Clés Acquises

1. **Analyser & Diagnostiquer :** Méthodologie "Où perdez-vous du temps ?" - cartographie temps, schématisation processus, détection opportunités (tâches répétitives, volumes, analyse)
2. **Comparer & Choisir LLM :** GPT-4, Claude, Mistral Large (🇫🇷 souverain), Llama - capacités, coûts, langues, souveraineté, arbre de décision
3. **Concevoir Architecture :** 5 composantes (identité, instructions système, connaissances, intégrations, paramètres) + prompts système structure 7 blocs
4. **Orchestrer Agents :** Chaîner agents spécialisés (A→B→C) - patterns séquentiel, parallèle, conditionnel - automatiser processus complexes
5. **Sécuriser & Conformer :** Risque réglementaire RGPD, IA Act européen, checklist conformité, 5 questions clés avant déploiement
6. **Sobriété IA :** SLM (Small Language Models) - alternatives 10x moins énergivores, -90% CO2, quand choisir SLM vs LLM
7. **Diffuser & Responsabiliser :** Verbaliser usages (technique IMPACT), rôle diffuseur, responsabilité légale/technique/éthique, plan succession

## Comparaison LLM - Choisir le Bon Modèle

| Critère | GPT-4 (OpenAI) | Claude 3 (Anthropic) | Mistral Large 🇫🇷 | Llama 3 (Meta) |
|---------|----------------|----------------------|-------------------|----------------|
| **Origine** | USA | USA | France (Souverain ✅) | USA (Open source) |
| **Coût** | ⭐⭐⭐ Élevé | ⭐⭐⭐ Élevé | ⭐⭐ Moyen | ⭐ Faible |
| **Français** | ⭐⭐⭐⭐ Très bon | ⭐⭐⭐⭐⭐ Excellent | ⭐⭐⭐⭐⭐ Excellent | ⭐⭐⭐ Bon |
| **Code** | ⭐⭐⭐⭐⭐ Excellent | ⭐⭐⭐⭐ Très bon | ⭐⭐⭐ Bon | ⭐⭐⭐ Bon |
| **RGPD** | Contractuel | Contractuel | Natif ✅ | Variable |
| **Meilleur pour** | Polyvalence, code | Textes longs | Français, souverain | Perso, recherche |

**Recommandation CRPDL :** Mistral Large par défaut (souveraineté), Claude 3 pour textes complexes, GPT-4 pour code technique

## Prompts Système - Structure en 7 Blocs

**Anatomie d'un prompt système efficace pour configurer le comportement permanent de l'agent :**

1. **Identité & Expertise :** Rôle précis, années d'expérience, domaines d'expertise
2. **Ton & Style :** Professionnel/pédagogique/technique, adaptation au public cible
3. **Comportement Attendu :** Règles TOUJOURS respectées (vérifications, structure, sources)
4. **Contraintes & Limites :** Interdictions JAMAIS (inventer données, avis personnel, confidentialité)
5. **Format de Sortie :** Structure standardisée des réponses (synthèse, détail, recommandations)
6. **Règles Métier CRPDL :** Contexte collectivité, terminologie, seuils d'alerte spécifiques
7. **Gestion Cas Limites :** Comportements par défaut si données incomplètes ou situations ambiguës

**Exemple Agent Analyse Budget :** Analyste budgétaire senior 15 ans d'expérience, style pédagogique, vérifie cohérence montants, format Synthèse/Détail/Recommandations, référence M57, seuil alerte >5%

## Orchestration d'Agents - Automatisation Complexe

**3 Patterns d'Orchestration :**

1. **Séquentiel (A → B → C) :** Agent 1 traite, passe résultat à Agent 2, qui passe à Agent 3. Exemple : Extraction données → Calcul indicateurs → Rédaction rapport
2. **Parallèle (A + B + C → D) :** 3 agents travaillent simultanément, Agent 4 consolide. Exemple : Veille 3 sources → Synthèse globale
3. **Conditionnel (Si X → A, sinon → B) :** Branchement selon critères. Exemple : Si montant >10K → Validation manager, sinon → Approbation auto

**Cas Concret : Reporting Mensuel RH Automatisé (5 agents chaînés, 3h → 5min)**
- Agent 1 : Extracteur Données SIRH → Agent 2 : Calculateur Indicateurs → Agent 3 : Analyseur Tendances → Agent 4 : Générateur Graphiques → Agent 5 : Rédacteur Rapport
- Output : Rapport PDF complet, gain 97% temps, envoi automatique 5 du mois

## Conformité RGPD & IA Act Européen

**5 Questions Clés Avant Déploiement :**

1. **Données personnelles ?** Si OUI → Consulter DPO obligatoire, anonymisation si possible
2. **Décision automatisée ?** Si OUI → AIPD (Analyse Impact) + Humain dans la boucle obligatoire
3. **Niveau risque IA Act ?** 🟠 Élevé (RH, juridique) → Conformité stricte | 🟡 Limité (chatbot) → Transparence | 🟢 Minimal (synthèse) → Libre
4. **Données souveraines ?** Swiftask/LigerIA = France ✅ | ChatGPT = USA ❌ (Cloud Act)
5. **Documentation complète ?** Notice utilisateur, limites, procédure recours, contact DPO

**Règle d'Or CRPDL :** "Un agent IA propose, l'humain dispose" - Toute décision impactant une personne (RH, droits, budget) doit être validée par un humain responsable.

**Contact DPO :** dpo@paysdelaloire.fr

## SLM : Small Language Models - IA Sobre 🌱

**Pourquoi les SLM ?** Alternative légère et sobre aux LLM classiques pour tâches répétitives et simples.

| Modèle | Énergie/Requête | CO2 | Coût | Meilleur pour |
|--------|-----------------|-----|------|---------------|
| **GPT-4** | 10-50 Wh | ~5-10g CO2 | ⭐⭐⭐ | Tâches complexes |
| **Mistral Large** | 3-15 Wh | ~2-5g CO2 | ⭐⭐ | Polyvalent français |
| **Mistral Small (SLM)** | 0.5-3 Wh | ~0.3-1g CO2 (-90%) | ⭐ | Répétitif, volume |
| **Phi-3 (SLM)** | 0.2-1 Wh | ~0.1-0.5g CO2 | ⭐ | Structuré, rapide |

**Cas Idéaux SLM :** Correction orthographique, catégorisation emails, extraction données, résumés courts, reformulation simple
**Cas LLM Classique :** Analyse complexe, créativité, multi-langues, raisonnement stratégique

**Exemple CRPDL :** 500 emails/jour catégorisés - GPT-4 : 300€/mois, 2.5T CO2/an | SLM : 60€/mois (-80%), 0.25T CO2/an (-90%)

**Recommandation :** "Commencez par SLM, escaladez vers LLM si qualité insuffisante"

## Rôle de Diffuseur IA - Technique IMPACT

**Pourquoi verbaliser ?** 80% pensent que l'IA aide, seulement 15% l'utilisent → Barrière = manque d'exemples concrets

**5 Moments Clés pour Verbaliser :**
1. **En réunion :** Mentionner IA naturellement ("J'ai utilisé agent X pour analyser en 5min...")
2. **Par email :** Signature "Co-créé avec LigerIA - Questions ? Contactez-moi"
3. **Pause café :** Mini-démos informelles spontanées (10 sec sur téléphone)
4. **Café IA mensuel :** Partage 1 usage récent (2 min chrono), format convivial
5. **Mur des Agents IA :** Affiche physique/Teams avec photo créateur, QR code tuto

**Technique IMPACT (Pitch 30 secondes) :**
- **I**dentification : "Je suis [Prénom], [Fonction]"
- **M**ission : "J'ai créé agent qui [Action]"
- **P**roblème résolu : "Avant [X temps], maintenant [Y temps]"
- **A**vantage : "Gain [X h/semaine] pour [Activité valeur]"
- **C**all-to-action : "Si même besoin, démo 5 min"
- **T**ransparence : "Agent fait erreurs, je valide toujours"

**3 Niveaux Ambassadeur :** Utilisateur Visible (0-3 mois) → Formateur Pair (3-6 mois) → Ambassadeur Reconnu (6-12 mois, Référent IA organigramme)

## Responsabilité Complète du Créateur

**Triple Casquette :**

1. **🧑‍⚖️ Propriétaire Légal :** Vous répondez des erreurs et conformité RGPD
   - Responsabilité Civile (dommages & intérêts si erreur agent)
   - Responsabilité Pénale (RGPD : amendes 20M€ ou 4% CA si violation données)
   - Responsabilité Disciplinaire (sanctions RH si usage non-conforme)

2. **🔧 Mainteneur Technique :** Vous corrigez bugs et faites évoluer
   - Maintenance corrective : Intervention <48h si bug bloquant
   - Maintenance préventive : Revue mensuelle performances
   - Évolution fonctionnelle : Nouvelle version trimestrielle selon feedbacks
   - Veille technologique : Suivre maj Swiftask et nouveaux LLM

3. **🛡️ Garant Éthique :** Vous assurez usage responsable
   - Transparence totale : Informer utilisateurs que c'est IA
   - Contrôle humain : Validation sur décisions critiques (RH, budget, légal)
   - Non-discrimination : Tester agent sur profils variés, corriger biais
   - Protection données : Minimisation, anonymisation, RGPD strict
   - Réversibilité : Possibilité désactiver agent immédiatement

**Plan Succession :** Documentation complète, passation binôme backup, code source accessible, transfert PV signé avant départ

## Validation Niveau 3

**Badge "Créateur d'Agents IA" obtenu si :**
- ✅ 1 agent fonctionnel créé et testé par 3+ utilisateurs
- ✅ Documentation complète (guide + FAQ + vidéo tuto)
- ✅ Quiz final : 80%+ réussite
- ✅ Attestation responsabilité signée (10 engagements)
- ✅ 1 collègue formé pendant atelier

**Badge Personnalisé avec IA (15 min) :**
- Prompt LigerIA fourni pour créer badge unique
- Personnalisation : Nom agent phare, compétences signature (orchestration, LLM, RGPD, SLM...), emoji, couleur, citation
- Livrables : Badge HD (1080x1080), version web, LinkedIn, certificat PDF A4
- Challenge : Publier LinkedIn sous 48h, taguer 3 collègues, #CreateurAgentsIA

**Indicateurs Performance :**
- 95% présence (2 journées complètes)
- 90% validation (badge + agent fonctionnel)
- 200 agents créés (1 agent/personne)
- 70% agents actifs à 3 mois (5+ utilisateurs/agent)
- ROI moyen 350% (3h/mois gagnées minimum)

## Support & Ressources

**Référent IA CRPDL :** referent-ia@paysdelaloire.fr  
**DPO (Conformité RGPD) :** dpo@paysdelaloire.fr  
**Conformité IA Act :** conformite-ia@paysdelaloire.fr  
**Communauté :** Canal Teams "Créateurs Agents IA"  
**Coaching :** 2h avec expert disponibles  
**Ressources :** Guide Architecte IA (40 pages), 20 templates agents, bibliothèque prompts système

**🏆 Niveau 4 sur sélection (40 élites ambassadeurs IA) - Septembre-Décembre 2026**
