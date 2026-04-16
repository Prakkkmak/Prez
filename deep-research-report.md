# Améliorer la collecte de feedback événementiel en entreprise francophone

## Résumé exécutif

Dans une entreprise francophone, les deux leviers les plus efficaces pour augmenter **le taux de réponse** et **la qualité** du feedback post‑événement sont (a) la **réduction de la friction** (répondre là où l’on travaille déjà : chat, mobile, QR, lien en 1 clic) et (b) la **capacité à exploiter rapidement les verbatims** (résumés, thèmes, sentiment, détection de réponses “bâclées”). citeturn7search2turn7search0turn8search0turn16search10

Le scan de marché met en évidence cinq familles de solutions qui surpassent généralement le duo “Google Forms + relances manuelles” :

- **Plateformes d’enquêtes/experience management (EM/XM) orientées entreprise** : adaptées si vous voulez standardiser, intégrer au CRM/ITSM, gérer SSO et gouvernance, et industrialiser l’analyse (ex. entity["company","Qualtrics","experience management saas"], entity["company","Medallia","experience management platform"]). citeturn0search0turn0search12turn8search5turn3search3turn6search1  
- **Outils “forms/surveys” modernes avec IA** : meilleure UX mobile, diffusion simple, et analyse IA des verbatims (ex. entity["company","SurveyMonkey","online survey platform"], entity["company","Typeform","online form builder"], entity["company","SurveySparrow","survey software saas"]). citeturn8search0turn16search10turn8search16  
- **Outils d’interaction live (pendant réunion/événement) + exports** : très efficaces pour capter du feedback “à chaud” et augmenter la participation (ex. entity["company","Slido","audience interaction tool"], entity["company","Mentimeter","interactive presentation tool"], entity["company","Wooclap","audience engagement platform"]). citeturn1search8turn11search10turn23search1  
- **Plugins de sondages “in‑chat” (Slack/Teams)** : réponse ultra‑rapide (1 clic) mais analytics souvent plus limitées (ex. entity["company","Polly","polls for slack and teams"]). citeturn1search3turn19search3turn13search2  
- **Voix→texte / NLP** : utile pour des formats “micro‑interview” ou debrief vocal ; peut s’appuyer sur la transcription Teams (FR inclus) ou des modules speech analytics (ex. entity["company","Microsoft","software company"] pour Teams ; Medallia Speech Analytics). citeturn22search3turn15search2  

Trois prototypes “quick‑win” (no‑code à dev léger) ressortent comme particulièrement rentables : (1) bot conversationnel (Teams/Slack) automatisant la collecte, (2) micro‑sondage post‑événement avec synthèse IA et diffusion automatique d’un digest, (3) workflow hybride micro‑sondage + micro‑interviews vocales avec transcription et extraction de thèmes. citeturn20search12turn16search10turn22search3turn7search2

Enfin, la réussite dépend autant de la technique que de la **confiance** : anonymat bien conçu (pas seulement “ne pas demander le nom”) et transparence sur l’usage des données. citeturn3search5turn3search1

## Contexte et critères de sélection

Dans beaucoup d’organisations, l’outil “par défaut” (formulaire + relance email) échoue pour des raisons structurelles :

- **Friction élevée** : clics multiples, changement de contexte, longueur non maîtrisée → baisse du démarrage et de la complétion. Des expérimentations montrent par exemple que **l’intégration d’une question directement dans l’email d’invitation** peut augmenter le taux de réponse, tout en conservant une mesure comparable. citeturn7search2turn7search18  
- **Relances non systématiques** : or les rappels peuvent produire des gains matériels de participation (dans une étude, les rappels augmentent la proportion de répondants de manière substantielle). citeturn7search0turn7search20  
- **Charge d’analyse** : les verbatims sont riches mais coûteux à traiter ; des suites IA (thèmes, sentiment, résumé) accélèrent la lecture et la mise en action. citeturn8search3turn16search10turn3search3  

Pour une entreprise francophone avec exigences “enterprise”, les critères de sélection les plus discriminants sont :

- **Support FR** (interface admin et/ou expérience répondant) et multi‑langue pour des publics mixtes. citeturn8search1turn16search4turn12search2turn9search7  
- **Intégrations** : messageries (Slack/Teams), email et automatisation (Power Automate/Zapier), CRM (ex. Salesforce), exports et API. citeturn8search2turn0search12turn0search16turn0search8turn6search2turn25search0  
- **Mobile UX** (QR code, lien, expérience web mobile, mode kiosque/offline si besoin). citeturn12search14turn24search8turn24search1turn24search2turn24search3  
- **Anonymat / confidentialité paramétrables** (anonyme, pseudonyme, confidentiel, ou identifié) selon le contexte de l’événement. citeturn17search2turn17search0turn18search3turn19search3turn17search12  
- **RGPD, sécurité et gouvernance** : DPA, options de résidence des données (si disponibles), certifications (ISO 27001/SOC2), gestion de la conservation, DPIA si nécessaire. citeturn5search1turn6search6turn23search2turn25search18turn6search1turn3search5  

Point d’attention “anonymat” : la entity["organization","CNIL","french data protection authority"] rappelle qu’assurer l’anonymat ne se réduit pas à ne pas collecter nom/prénom ; il faut aussi éviter toute combinaison de données permettant une ré‑identification. citeturn3search5turn3search1

## Scan de marché des solutions

Le marché se segmente moins par “outil de sondage” que par **moment de collecte** (pendant / juste après / à froid) et **canal** (chat, email, QR/mobile, entretien). Ci‑dessous, une lecture “orchestrée” des catégories pertinentes pour augmenter réponse + qualité, avec un biais vers support FR et intégrations entreprise.

Les plateformes “enterprise” de feedback et d’analyse NLP se distinguent par la gouvernance, les intégrations et la profondeur analytique. Qualtrics propose par exemple une analyse de texte (Text iQ) incluant **sentiment** et **tagging par thèmes**, et des intégrations de diffusion/notification via Slack ou Teams, ainsi qu’une intégration Salesforce permettant de déclencher des enquêtes depuis un événement Salesforce et de remapper des réponses. citeturn0search0turn0search19turn0search12turn8search5turn0search8 Medallia met fortement l’accent sur la **text analytics** (thèmes/sentiment/émotions sur de nombreuses langues) et une couche d’intégration (APIs/ETL) ; son portefeuille inclut aussi des fonctions “speech analytics” (transcription multi‑langue pour analytics) utiles dans des workflows d’entretiens ou de retours vocaux. citeturn3search3turn15search14turn15search2turn6search1

Les suites “survey/forms” avec IA cherchent à gagner sur l’UX et le time‑to‑insight. SurveyMonkey met en avant une suite IA avec **sentiment**, **détection de qualité de réponses** (filtre réponses incohérentes/bâclées) et **analyse thématique**, avec un mode “Analyze with AI” produisant des réponses, graphiques et résumés à partir de questions posées sur les résultats. citeturn8search0turn8search3turn8search21 Typeform propose des capacités IA (Smart Insights) couvrant **résumés**, **détection de sujets** et **sentiment** sur questions ouvertes, ainsi que des intégrations directes avec Slack et Teams. citeturn16search10turn16search3turn6search5turn6search2 SurveySparrow se positionne sur les surveys “conversationnelles” et l’analyse texte via CogniVue (extraction de sujets / drivers et sentiment), avec intégrations Teams et Slack. citeturn8search16turn0search3turn16search2

Pour augmenter la participation “à chaud”, les outils d’interaction live (réunions, ateliers, all‑hands) sont très efficaces car la réponse se fait en séance, souvent par QR/lien et sans compte. Slido met en avant l’intégration à Teams et propose des fonctionnalités IA (assistant de rédaction, génération de contenus/polls/quiz) ; il offre aussi un export des données d’engagement. citeturn1search8turn12search12turn12search16turn12search1turn12search3 Mentimeter propose aussi une app Teams, un créateur IA de sessions, et des fonctions IA pour **regrouper les réponses en clusters thématiques** et **résumer** des réponses texte. citeturn11search3turn11search9turn11search10turn11search0 Wooclap est particulièrement présent dans les environnements francophones, offre une intégration Teams et des exports (Excel/PDF/CSV) ; il propose également Wooclap AI pour générer des questions depuis un sujet/document/vidéo. citeturn1search2turn23search1turn23search0

Pour des organisations où la messagerie est le “centre de gravité”, les plugins natifs Slack/Teams augmentent souvent le taux de réponse car l’utilisateur ne quitte pas son outil de travail. Polly explicite des réglages d’anonymat (anonyme / non anonyme / confidentiel), des options de planification, et un mode Teams “in‑meeting”. citeturn1search3turn19search3turn19search7turn13search2

Enfin, pour un besoin de conformité renforcée (hébergement UE, contrôle fin, self‑host), LimeSurvey peut être pertinent : il met en avant des localisations d’hébergement (dont Allemagne/Finlande recommandées UE), une API (RemoteControl 2 en XML‑RPC/JSON‑RPC) et des options d’anonymisation. citeturn25search18turn25search0turn25search7turn3search2

Sur le volet “voix→texte”, Teams documente la **transcription en direct** et liste explicitement la prise en charge de langues dont **French (France)** ; Microsoft annonce aussi des fonctionnalités récentes autour de la détection automatique de langues en réunion multilingue (publication Mar 30, 2026). citeturn22search3turn22search1 Ces briques permettent d’industrialiser des retours vocaux courts (micro‑interviews) sans transcription manuelle, puis de passer en analyse thématique/sentiment côté outil de feedback ou via pipeline IA interne. citeturn15search2turn3search3

## Tableau comparatif des 10 outils recommandés

| Outil recommandé | Pricing tier (indicatif) | Support FR | IA (résumé / sentiment / thèmes) | Intégrations clés | Mobile UX | Anonymat / confidentialité | Effort de mise en place | RGPD / conformité (éléments publiés) | Meilleur cas d’usage |
|---|---|---|---|---|---|---|---|---|---|
| entity["company","Qualtrics","experience management saas"] citeturn8search1turn0search0turn0search12turn8search5turn14search11turn5search5turn17search2turn24search3 | Enterprise (souvent sur devis) + self‑serve “Buy Online” annoncé ($420/mo pour 1 000 réponses/an, USD) | Oui (UI plateforme en FR) | Sentiment + thèmes via Text iQ ; résumés : non précisé | Slack (diffusion), Teams (diffusion/notifications), Salesforce | Très bon (web + app offline) | Lien “anonymous” (IP collectée par défaut) + options d’anonymisation | Élevé (gouvernance, modèles, intégrations) | Page conformité RGPD ; trust center ; options suppression/DSR | Standardiser le feedback à l’échelle + routage/actions + intégration CRM/IT |
| entity["company","Medallia","experience management platform"] citeturn3search3turn6search1turn15search14turn15search3turn15search2turn15search8 | Enterprise (modèle de pricing ; montants non précisés publiquement) | Oui (multilingue ; détail FR variable selon produit) | Thèmes + sentiment/émotions (NLU) ; résumés : non précisé (selon modules) | Salesforce, APIs/ETL ; connecteurs Microsoft (ex. Dynamics) ; autres via intégration | Bon (dépend du module collecte) | Variable selon dispositif (non précisé) | Élevé | Page sécurité : SOC2, ISO 27001/27701, GDPR/SCCs (annoncés) | Feedback multi‑source + NLP “enterprise” + speech analytics / call‑like debrief |
| entity["company","SurveyMonkey","online survey platform"] citeturn8search0turn8search3turn0search16turn0search1turn17search0turn14search1turn24search2turn16search1turn5search0 | SMB/Team (Team Advantage/Team Premier) + Enterprise sur devis | Oui (site FR + multi‑langue) | Résumé + sentiment + thèmes + détection qualité réponses | Teams + Power Automate ; CRM (Salesforce, HubSpot…) | Très bon (SurveyMonkey Anywhere offline/kiosque) | “Anonymous responses” paramétrable ; IP en logs backend avec rétention annoncée | Moyen | DPA disponible ; page transferts/accords (DPF) | Post‑event survey standard + analytics IA + intégration Microsoft/CRM |
| entity["company","Typeform","online form builder"] citeturn14search0turn16search10turn16search3turn6search5turn6search2turn16search4turn19search2turn5search11turn24search1 | SMB → Enterprise (Basic/Plus/Business/Enterprise ; prix publics en USD) | Oui (FR dans multi‑langue formulaire) | Smart Insights : résumés + topics + sentiment ; “Ask AI” | Slack + Teams ; automatisations (selon plan/add‑on) | Excellent (design mobile + preview mobile) | “Anonymous by default” (mais métadonnées techniques possibles selon config) | Faible à moyen | DPA publié ; docs sécurité/RGPD | Feedback court et élégant, taux de complétion élevé, synthèses IA rapides |
| entity["company","SurveySparrow","survey software saas"] citeturn0search3turn16search2turn8search16turn5search8turn5search4turn5search12turn14search2turn14search14 | SMB → Enterprise (prix exacts variables ; références “à partir de $19/mo” selon agrégateurs) | Oui (multi‑langue ; +60 langues mentionnées) | CogniVue : sujets/drivers + sentiment ; résumés : non précisé | Teams + Slack ; intégrations CRM (annoncées) | Bon (app “SurveySparrow Go”) | Anonymat possible (selon mode de diffusion/config) | Moyen | Pages GDPR + SOC2/ISO mentionnés | Surveys “conversationnels” pour booster réponse, notamment en interne |
| entity["company","Slido","audience interaction tool"] citeturn1search8turn12search12turn12search16turn12search3turn12search2turn6search0turn6search3 | Freemium → SMB (Engage) → Enterprise | Oui (FR (France/Canada) listé) | IA surtout “création/rédaction” (polls/quiz/Q&A) ; analyse qualitatif : limité/nc | Teams ; add‑ons (Slides/PowerPoint) ; exports | Très bon (QR/lien ; pas de téléchargement requis côté participant) | Participant sans compte (selon réglages) | Faible à moyen | Page sécurité ; mention GDPR ; DPA | Feedback “à chaud” + Q&A + quelques questions post‑session |
| entity["company","Mentimeter","interactive presentation tool"] citeturn11search3turn11search9turn11search10turn11search0turn18search3turn9search7turn9search1turn13search8 | Freemium → Pro/Business ; Enterprise sur devis (tarifs exacts : variables ; ex. Capterra) | Oui (FR listé) | Résumé de textes + clustering thématique ; sentiment : non précisé | App Teams ; add‑in PowerPoint | Excellent (join code/QR/lien) | Vote anonyme par défaut (options d’identification possibles) | Faible | Page RGPD/transparence ; “AI at Mentimeter” (cadre) | Ateliers/événements : capter feedback live + structurer verbatims rapidement |
| entity["company","Wooclap","audience engagement platform"] citeturn1search2turn23search0turn23search1turn23search2turn17search3turn23search7turn23search18 | Pro (sur devis/quote) + offres ; détails variables | Oui (éditeur francophone + site FR) | IA surtout “génération de questions” ; analyse de verbatims : non précisé | Teams ; PowerPoint ; exports | Très bon (usage mobile/QR) | Anonyme / pseudo / login (selon réglage) | Faible à moyen | Trust center : ISO 27001:2022 (annoncé) + RGPD ; ATD/DPA | Formations, réunions, conférences : interaction live + exports structurés |
| entity["company","Polly","polls for slack and teams"] citeturn1search3turn13search2turn19search3turn1search7turn19search7 | Freemium → Pro/Teams ; prix publics (USD) | Non précisé (UI souvent EN ; répondants peuvent répondre en FR) | Pas d’IA d’analyse natif (orienté polling) | Natif Teams + Slack ; planification/rappels | Excellent (dans Teams/Slack mobile) | Anonyme / non anonyme / confidentiel | Très faible | Page GDPR ; réglages d’anonymat documentés | Micro‑sondages ultra courts dans le flux de travail (pulse post‑event) |
| entity["company","LimeSurvey","open-source survey software"] citeturn13search15turn25search18turn25search2turn25search0turn25search7turn3search2 | Cloud “Basic/Expert/Business” + Corporate ; self‑host possible | Oui (FR disponible ; multi‑langue) | Pas d’IA native (à ajouter via pipeline) | API (JSON‑RPC/XML‑RPC) ; plugins ; webhooks via plugins (tiers) | Bon (web ; mode kiosque “à concevoir”) | Anonymisation possible (fonction) | Moyen (config + hébergement/IT) | Hébergement UE (Allemagne/Finlande indiqué) ; ISO 27001‑certified (annoncé) ; GDPR compatible | Contextes sensibles RGPD / besoin contrôle, ou intégration sur mesure |

*Abréviation : “nc” = non communiqué / non précisé par les sources consultées. “Tarifs indicatifs” : les prix varient selon pays, volume, options et négociation ; quand les pages éditeur sont dynamiques ou incomplètes, le tableau indique des ordres de grandeur issus d’agrégateurs réputés (ex. Capterra) et doit être vérifié lors du sourcing.*

## Concepts de prototypes quick‑win

Les “quick wins” ci‑dessous visent un objectif pragmatique : **+participation** (moins de friction) et **+qualité actionnable** (2–3 signaux structurés + 1 verbatim exploitable), tout en restant compatibles avec une organisation Teams/Slack et des contraintes RGPD.

Option de cadrage commune (recommandée) : faire un **triptyque** “à chaud / à froid / approfondissement” :
- **Pendant** : 1–2 questions live (sliders, word cloud, “stop/continue/start”).  
- **Juste après (0–60 min)** : micro‑sondage 3 questions max.  
- **À froid (J+3 à J+7)** : relance ciblée sur non‑répondants ou sous‑populations, ou micro‑interviews (échantillon).  
Les rappels et la réduction de friction sont des leviers mesurés pour augmenter le taux de réponse. citeturn7search0turn7search2

### Prototype A : bot conversationnel automatisé (Teams ou Slack)

**Idée** : un bot envoie automatiquement, après l’événement, une courte conversation (ou carte interactive) dans Teams/Slack : 2 échelles + 1 question ouverte + 1 question “si note ≤ X, demande pourquoi”. Les réponses sont stockées et une synthèse est publiée au facilitateur/owner.

**Composants requis**
- Un orchestrateur bot : entity["company","Microsoft Copilot Studio","agent builder for teams"] (publication Teams/web documentée) ou bot Slack (développement léger). citeturn20search12turn20search0  
- Canal de diffusion : chat de réunion Teams, message à un canal, ou DM (attention anonymat).  
- Stockage : SharePoint/Dataverse/DB interne (non précisé : dépend SI).  
- Synthèse IA : LLM interne/contractuel + pipeline d’anonymisation (si besoin).  
- Règles d’enrôlement : liste participants (depuis calendrier/Teams attendance si disponible) (non précisé : selon configuration M365).

**Temps d’implémentation estimé**
- No‑code (Teams) : 5–10 jours ouvrés (design conversation + connecteurs + sécurité).  
- Dev léger (Slack bot) : 2–4 semaines selon SSO, stockage, conformité (estimation).

**Ordre de coût**
- Licences : Copilot Studio est vendu en “packs de crédits” (25 000 crédits/pack/mois à $200/pack/mois) ; coût réel dépend de l’usage. citeturn20search0  
- Autres coûts : dépend du LLM et de l’hébergement (non précisé).

**Flux utilisateur (Mermaid)**

```mermaid
flowchart TD
  A[Fin d'événement (calendrier/Teams)] --> B[Déclencheur (Power Automate / webhook)]
  B --> C[Bot Teams/Slack envoie micro-questionnaire]
  C --> D{Répondant}
  D -->|Répond| E[Stockage réponses (DB/SharePoint/Dataverse)]
  E --> F[Pipeline IA: nettoyage + résumé + thèmes]
  F --> G[Digest envoyé au propriétaire + canal de suivi]
  D -->|Ignore| H[Rappel ciblé J+1 pour non-répondants]
  H --> C
```

**Points forts / limites**
- Très bon pour le taux de réponse (zéro changement de contexte).  
- Limite : DM = identité connue ; si vous avez besoin d’anonymat fort, privilégier lien “anonymous” vers une plateforme de sondage et ne pas remonter d’identifiants. citeturn3search5turn17search2  

### Prototype B : micro‑sondage post‑event + synthèse IA automatique (email + chat)

**Idée** : déclencher automatiquement un micro‑sondage (1 score + 1 question ouverte + 1 choix) juste après l’événement, puis générer une synthèse et des thèmes pour l’organisateur (et éventuellement un résumé “shareable” aux participants).

**Composants requis**
- Outil de collecte : Typeform (Smart Insights) ou SurveyMonkey (AI Analysis Suite) pour résumer/sentiment/thèmes, ou Qualtrics Text iQ (sentiment + thèmes). citeturn16search10turn8search3turn0search0  
- Automatisation : SurveyMonkey s’intègre à Teams et Power Automate (donc orchestration possible autour d’événements M365). citeturn0search16  
- Option “question intégrée” dans email : implémentation possible avec certains éditeurs (ou via technique d’email embed + landing), et l’intérêt de l’embed est corroboré par la littérature expérimentale (Survey Practice). citeturn7search2  
- Digest : envoi dans Teams/Slack + stockage central (Confluence/SharePoint) (non précisé : selon SI).

**Temps d’implémentation estimé**
- No‑code : 2–5 jours ouvrés (créer template, workflow “fin d’événement → envoi → rappel → export/synthèse”).  
- Dev léger : 1–2 semaines si vous voulez un tableau de bord interne.

**Ordre de coût**
- Licence Typeform : plan public “Basic $29/mo” (USD) ; autres plans selon volume. citeturn14search0  
- SurveyMonkey : Team Advantage/Team Premier (prix variable selon pays/page). citeturn14search1  

**Flux utilisateur (Mermaid)**

```mermaid
flowchart TD
  A[Fin d'événement] --> B[Trigger (Power Automate/Zapier)]
  B --> C[Envoi micro-sondage (email + Teams)]
  C --> D[Répondant répond (1-3 questions)]
  D --> E[Collecte dans l'outil]
  E --> F[IA: résumé + thèmes + sentiment + qualité]
  F --> G[Digest: 5 points + verbatims clés]
  G --> H[Publication: canal Teams + email organisateur]
  H --> I[Backlog d'actions + owners + échéances]
```

**Points forts / limites**
- Très bon équilibre “rapidité + qualité”, surtout si l’IA détecte les réponses faibles et structure les verbatims. citeturn8search0turn16search10turn8search3  
- Dépendance à la qualité des questions : il faut standardiser des modèles par type d’événement (formation / town hall / atelier).  

### Prototype C : workflow hybride “interviewer + voix→texte + NLP”

**Idée** : combiner un micro‑sondage quanti (tous participants) et un micro‑échantillon qualitatif via de courtes interviews (5–7 min) menées par un animateur (ou “pairs”), enregistrées en audio, puis transcrites et analysées (thèmes/sentiment). C’est un bon compromis quand vous voulez de la **profondeur** sans lancer une étude lourde.

**Composants requis**
- Sélection échantillon : règles simples (ex. 10–20% des participants, quotas équipe/séniorité) (non précisé : gouvernance interne).  
- Captation audio + transcription : transcription Teams en direct (langues supportées dont French (France)). citeturn22search3turn21search13  
- Analyse : Medallia (text/speech analytics) ou Qualtrics/SurveyMonkey/Typeform pour le texte ; ou pipeline IA interne. citeturn15search2turn3search3turn8search3turn16search10  
- Restitution : “insights deck” standardisé + plan d’actions.

**Temps d’implémentation estimé**
- 1–2 semaines pour le process + templates + consentements, puis 0,5–1 jour par événement selon taille.

**Ordre de coût**
- Faible si vous avez déjà Teams Premium / transcription activée ; sinon dépend des licences et du choix NLP (non précisé). citeturn21search5turn22search3  

**Flux utilisateur (Mermaid)**

```mermaid
flowchart TD
  A[Micro-sondage à tous] --> B[Scores + verbatims courts]
  A --> C[Échantillonnage répondants pour interviews]
  C --> D[Invitation créneau 7 min]
  D --> E[Micro-interview (Teams)]
  E --> F[Transcription]
  F --> G[Analyse NLP: thèmes + citations + irritants]
  B --> H[Consolidation quanti + quali]
  G --> H
  H --> I[Restitution + décisions + suivi actions]
```

**Points forts / limites**
- Produit des insights plus actionnables (causalité, exemples) que le survey seul, tout en restant industrialisable.  
- Demande une discipline opérationnelle (planning, interviewers, homogénéité du guide).  

## Mesure, métriques et idées d’A/B tests

Pour piloter l’amélioration, il faut distinguer **participation** (volume, vitesse, représentativité) et **qualité** (signal exploitable). Les outils IA peuvent aider à filtrer les réponses faibles (ex. détection de réponses “gibberish/rushed” annoncée par SurveyMonkey) et à structurer les verbatims en thèmes/sentiment. citeturn8search0turn8search3turn16search10

**Métriques de participation (par événement et par canal)**
- **Taux de réponse** = répondants uniques / invités uniques (fenêtre fixe : ex. 72h).  
- **Taux de démarrage** (si traçable) = sessions ouvertes / invitations délivrées.  
- **Taux de complétion** = enquêtes complètes / démarrées.  
- **Temps médian de complétion** (objectif : < 60 secondes pour micro‑sondage).  
- **Délai de première réponse** (latence entre fin d’événement et premières réponses).  
- **Effet rappel** : delta de taux de réponse après J+1. Les rappels ont montré des effets significatifs sur la participation dans la littérature. citeturn7search0turn7search4turn7search20  

**Métriques de qualité**
- **Taux de verbatims exploitables** (classification binaire “actionnable / non actionnable” via rubric ou IA).  
- **Longueur moyenne de texte** (caractères/mots) et distribution (attention aux outliers).  
- **Richesse thématique** : # thèmes distincts atteignant un seuil (ex. ≥5 mentions).  
- **Polarité / sentiment** (si disponible) et évolution dans le temps (avant/après actions). citeturn0search0turn8search3turn16search10turn3search3  
- **Taux de réponses de faible qualité** (si outil le détecte) + taux de suppression/filtrage. citeturn8search0  
- **Représentativité** : couverture par équipes/sites (agrégée, surtout si promesse d’anonymat).  

**Métriques d’impact opérationnel**
- **Time‑to‑insight** : délai fin d’événement → synthèse partagée (objectif : < 24h).  
- **Taux de clôture d’actions** : actions livrées / actions décidées, et délai moyen.  
- **Boucle de restitution** : % d’événements ayant un retour “vous avez dit / nous avons fait”.

**Idées d’A/B tests (pragmatiques, à fort ROI)**
- **Canal** : email vs Teams/Slack vs QR en fin de session (mesurer d’abord le delta sur démarrage et complétion).  
- **Embed d’une première question dans l’email** vs lien classique : la recherche en conditions expérimentales suggère une hausse du taux de réponse sans dégrader la mesure. citeturn7search2turn7search14  
- **Timing** : envoi à T+15 min vs T+24h ; + 1 rappel unique J+1. Les rappels augmentent la participation ; l’intervalle optimal dépend du contexte, d’où l’intérêt du test. citeturn7search0turn7search4turn7search20  
- **Longueur** : 2 questions vs 4 questions ; mesurer complétion et qualité actionnable.  
- **Anonyme vs identifié** (ou “confidentiel”) : Mentimeter avance que le vote anonyme favorise des réponses plus honnêtes (à valider chez vous). citeturn18search3turn3search5  
- **Formulation** : “1 amélioration prioritaire” vs “3 idées” ; mesurer taux de verbatim exploitable.  
- **Routage** : si score faible → question “cause principale” (liste) + champ libre ; mesurer actionnabilité.

## Risques, RGPD et conduite du changement

**Anonymat, pseudonymat, confidentialité : clarifier et prouver**
- D’un point de vue RGPD et de confiance interne, l’enjeu n’est pas seulement de “ne pas demander le nom” : la CNIL rappelle qu’il faut s’assurer qu’aucune donnée (ou combinaison) ne permette d’identifier une personne. citeturn3search5turn3search1  
- Beaucoup d’outils proposent des modes “anonymes” mais qui peuvent, par défaut, collecter des métadonnées techniques (ex. Qualtrics : lien anonyme collectant IP/localisation par défaut ; SurveyMonkey : option “Anonymous responses” et mention d’IP en logs backend ; Typeform : anonymat par défaut mais “network ID” dérivé de l’IP mentionné en communauté). citeturn17search2turn17search0turn19search18turn19search2  
- Recommandation : définir 3 niveaux internes **officiels** :  
  - *Anonyme fort* (données non rattachables, pas d’identifiants, seuils d’agrégation)  
  - *Confidentiel* (identité visible seulement à un rôle restreint, non partagée)  
  - *Identifié* (utile pour support/close‑loop individuel)  
  puis mapper chaque type d’événement à un niveau.

**Bases légales, transparence et gouvernance**
- Même hors sujets “données sensibles”, appliquer des principes RGPD : finalité explicite, minimisation, durée de conservation, information claire et droits. Des guides publics français sur le RGPD appliqué aux enquêtes insistent sur la nécessité d’informer et d’intégrer ces éléments dans l’architecture du questionnaire. citeturn2search8turn2search15  
- Côté RH/relations internes, la participation devrait rester **volontaire** lorsque cela s’y prête ; des synthèses de recommandations CNIL (sur des enquêtes en entreprise) mettent en avant le caractère facultatif, l’information et la préférence pour l’anonymat. citeturn2search15turn2search7  

**Transferts, sous‑traitants, DPA et sécurité**
- Demander et archiver les **DPA** (accords de traitement) et la liste des sous‑traitants. Beaucoup d’éditeurs publient DPA et pages sécurité (ex. SurveyMonkey DPA ; Typeform DPA ; Slido DPA). citeturn5search0turn5search11turn6search6  
- Vérifier la **résidence des données** si elle est requise : LimeSurvey indique des localisations d’hébergement (dont Allemagne/Finlande recommandées UE). citeturn25search18turn25search2  
- Pour l’IA : si des verbatims sont envoyés à un service de synthèse, cadrer contractuellement (sous‑traitance, localisation, rétention, usage entraînement — non précisé, dépend du fournisseur IA).

**Risques opérationnels fréquents**
- **Sur‑sollicitation** : trop d’enquêtes tue la participation ; mettre des règles de fréquence et des “moments clés”.  
- **Effet boîte noire IA** : si l’IA produit des thèmes/résumés, prévoir un contrôle humain sur un échantillon et conserver l’accès aux verbatims.  
- **Modération** : sur questions ouvertes live (word cloud), risque de contenus inappropriés ; Mentimeter recommande d’être attentif aux capacités de modération selon types de questions. citeturn11search23  
- **Défiance sur l’anonymat** : si la promesse est ambiguë, la qualité chute (auto‑censure). La clarification CNIL sur anonymisation est un appui pédagogique interne. citeturn3search1turn3search5  

**Conduite du changement (très concret)**
- “Vous avez dit / nous avons fait” : publier une synthèse courte (5 points) et 2–3 actions décidées – c’est souvent le meilleur driver de participation durable (logique de réciprocité).  
- Standardiser des **templates** par type d’événement (formation, all‑hands, atelier) et limiter à 60 secondes.  
- Nommer un “owner” (COMMS/People/PMO) et un “data steward” (DPO/Legal/IT) pour gouverner : modèles, anonymat, conservation.  
- Déployer par **pilotes** : 2–3 équipes, comparer canaux (Teams vs email), et itérer via A/B tests (timing, rappel, longueur). Les rappels et l’embed email sont des essais à fort effet attendu. citeturn7search0turn7search2