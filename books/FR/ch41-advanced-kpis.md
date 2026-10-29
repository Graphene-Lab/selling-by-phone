# Chapitre 41 : KPI Avancés et Analyse Prédictive

## 41.1 KPI de Conversion Avancés

**Les métriques que les meilleurs vendeurs tracent :**

| KPI | Formule | Signification |
|-----|---------|---------------|
| **Lead-to-Opportunity Rate** | Opportunités / Leads × 100 | Qualité du lead |
| **Opportunity-to-Proposal Rate** | Propositions / Opportunités × 100 | Qualité de la découverte |
| **Proposal-to-Win Rate** | Won / Propositions × 100 | Qualité de la proposition |
| **Average Sales Cycle** | Σ(Jours Lead→Won) / N deals | Vitesse du cycle |
| **Revenue per Call** | Revenue total / Appels faits | Efficience globale |
| **Pipeline Velocity** | (N deals × Valeur × Win Rate) / Cycle | Vitesse de génération revenue |
| **Multi-threading Rate** | Contacts par deal | Profondeur relation |
| **Expansion Revenue Rate** | Revenue expansion / Revenue total | Upsell effectiveness |

## 41.2 Analyse Prédictive

**Utiliser les données pour prévoir les résultats :**

**Modèle de scoring lead :**
| Facteur | Score |
|---------|-------|
| Secteur fit | +20 |
| Taille fit (20-500) | +15 |
| Signal de croissance | +15 |
| Budget confirmé | +20 |
| Décideur impliqué | +15 |
| Urgence haute | +15 |
| **Total** | **100** |

**Seuil** : Lead avec score > 70 = haute priorité. Score < 40 = disqualification.

## 41.3 Cohort Analysis

**Comparer des groupes de deals par période :**
- Deals closés Q1 vs. Q2 : Qu'est-ce qui a changé ?
- Deals de cold call vs. inbound : Lequel convertit mieux ?
- Deals avec démo vs. sans démo : Différence de win rate ?
- Deals multi-thread vs. single-thread : Qui clôture plus ?

## 41.4 Funnel Analysis Profonde

**Identifier le "gouttage" par phase :**

| Phase | Entrés | Sortis | Conversion | Gouttage |
|-------|--------|--------|------------|----------|
| Lead | 100 | 40 | 40% | 60 perdus |
| Contact | 40 | 20 | 50% | 20 perdus |
| Qualifié | 20 | 12 | 60% | 8 perdus |
| Démo | 12 | 8 | 67% | 4 perdus |
| Proposition | 8 | 4 | 50% | 4 perdus |
| Won | 4 | 4 | 100% | 0 perdus |

**Question clé** : Où goutte le plus ? Là se trouve le plus grand potentiel d'amélioration.

## 41.5 Revenue Attribution

**Attribuer le revenue à des activités spécifiques :**
- Quel script génère le plus de revenue ?
- Quel secteur produit des deals plus gros ?
- Quel canal (cold, warm, inbound) est le plus efficient ?
- Quel type de démo convertit mieux ?
- Quelle séquence de follow-up fonctionne ?

## 41.6 Predictive Forecasting

**Méthode avancée :**
```
Forecast = Σ (Deal_value × Phase_probability × Rep_confidence)

Où :
- Phase_probability : issu de l'historique (ex. Démo = 40%)
- Rep_confidence : auto-évaluation (0.5-1.5)
- Adjustments : tendance, saisonnalité, marché
```

## 41.7 KPI de Qualité

| KPI | Comment Mesurer | Target |
|-----|-----------------|--------|
| **Temps de réponse** | Minutes pour répondre à un lead | < 5 minutes |
| **Taux de personnalisation** | % appels avec recherche pré-call | > 80% |
| **Taux de follow-up** | % deals avec 5+ follow-ups | > 70% |
| **Documentation CRM** | % appels documentés | 100% |
| **NPS post-vente** | Sondage client | > 50 |

## 41.8 Benchmarking Avancé

**Comparez non seulement les résultats mais les PROCESSUS :**
- Temps moyen par phase vs. top performer
- Nombre de contacts par deal vs. top performer
- Taux de personnalisation vs. top performer
- Cycle de vente vs. top performer
- Revenue par activité vs. top performer

## 41.9 Insights des Données

**Exemples d'insights :**
- "Les deals avec 3+ contacts clôturent 40% plus souvent"
- "Démo dans les 48h après discovery convertit 2x"
- "Follow-up dans les 24h augmente conversion de 300%"
- "Secteur X a un cycle 2x plus long mais des deals 3x plus gros"
- "Script B génère 2x de rendez-vous vs. Script A"

## 41.10 Dashboard Avancée

**Métriques par niveau :**

**Niveau Rep (journalier) :**
- Appels, conversations, rendez-vous, revenue

**Niveau Manager (hebdomadaire) :**
- Pipeline, forecast, conversion par phase, top/bottom performer

**Niveau Executive (mensuel) :**
- Revenue, croissance, pipeline velocity, CAC, LTV

---

## Résumé du Chapitre

Les KPI avancés incluent :
- **Conversion** : Par chaque phase de la pipeline
- **Prédictif** : Scoring lead, forecasting
- **Cohort** : Comparaison par période et canal
- **Attribution** : Quelle activité génère du revenue
- **Qualité** : Temps réponse, personnalisation, documentation
- **Insights** : Patterns cachés dans les données

---

## Actions à Entreprendre

- [ ] Calculer la pipeline velocity de votre équipe
- [ ] Créer un modèle de scoring lead
- [ ] Identifier le point de plus gros gouttage
- [ ] Construire un dashboard avec KPI avancés
- [ ] Générer 3 insights de vos données et agir dessus
