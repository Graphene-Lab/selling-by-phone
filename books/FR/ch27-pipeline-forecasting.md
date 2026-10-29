# Chapitre 27 : Pipeline et Forecasting au Téléphone

## 27.1 Construire une Pipeline Téléphonique

La pipeline est le flux de tous les prospects que vous travaillez, du cold call à la clôture. Chaque appel téléphonique alimente la pipeline.

**Phases de la pipeline pour AgentBridge :**

| Phase | Définition | Critère de Sortie |
|-------|------------|-------------------|
| **Lead** | Contact identifié | Qualifié comme fit |
| **Contact** | Premier appel fait | Conversation eue |
| **Qualifié** | MEDDIC 4/6 confirmé | Démo fixée |
| **Démo** | Démo complétée | Proposition demandée |
| **Proposition** | Proposition envoyée | Négociation lancée |
| **Négociation** | Termes discutés | Contrat signé |
| **Closé-Won** | Deal closé | Paiement reçu |
| **Closé-Lost** | Deal perdu | Motif documenté |

## 27.2 Métriques de Pipeline

| Métrique | Formule | Benchmark |
|----------|---------|-----------|
| **Vitesse pipeline** | Jours moyens Lead → Won | 30-90 jours |
| **Conversion par phase** | (Sortis / Entrés) × 100 | Varie par phase |
| **Valeur moyenne deal** | Revenue total / Nombre deals | 5 000-50 000€ |
| **Pipeline coverage** | Pipeline total / Target revenue | 3x-5x |
| **Win rate** | Won / (Won + Lost) × 100 | 20-40% |
| **Churn rate** | Perdus / Total × 100 | <10% |

## 27.3 Forecasting Téléphonique

**Méthode de forecasting :**

```
Forecast = Σ (Valeur deal × Probabilité de clôture par phase)

Phase Lead: 5%
Phase Contact: 10%
Phase Qualifié: 25%
Phase Démo: 40%
Phase Proposition: 60%
Phase Négociation: 80%
Phase Closé-Won: 100%
```

**Exemple :**
- 20 Leads × 5 000€ × 5% = 5 000€
- 10 Qualifiés × 10 000€ × 25% = 25 000€
- 5 Démos × 15 000€ × 40% = 30 000€
- 3 Propositions × 20 000€ × 60% = 36 000€
- **Forecast total : 96 000€**

## 27.4 Pipeline Hygiene

Une pipeline sale est pire qu'une pipeline vide.

**Règles :**
- **Règle des 30 jours** : Si un deal ne bouge pas en 30 jours, fermez-le ou requalifiez-le
- **Pas de deals "peut-être"** : Chaque deal a une date de clôture ou est fermé
- **Mise à jour hebdomadaire** : Revoyez chaque deal chaque semaine
- **Motif de perte obligatoire** : Chaque deal perdu a un motif documenté
- **Pas de double comptage** : Un deal est dans une seule phase

## 27.5 Activité Téléphonique et Pipeline

| Activité | Impact sur la Pipeline |
|----------|----------------------|
| 50 appels/jour | ~5-8 conversations → 1-2 rendez-vous |
| 2 démos/semaine | ~1 proposition/semaine |
| 1 proposition/semaine | ~0,5 clôture/semaine |
| 10 follow-ups/jour | 2-3 réactivations/semaine |

**Règle pratique** : Pour clôturer 1 deal par semaine, il faut ~50 appels par jour, 2 démos par semaine et 10 follow-ups par jour.

## 27.6 Gérer une Pipeline Sous-Pesée

Si la pipeline est trop maigre :
1. **Augmenter le volume** : Plus d'appels, plus de leads
2. **Améliorer la qualification** : Moins de deals poubelle
3. **Accélérer les deals existants** : Follow-ups plus agressifs
4. **Activer les referrals** : Demander aux clients existants
5. **Réactiver les deals perdus** : Appeler les deals perdus il y a 6+ mois

## 27.7 Gérer une Pipeline Surpesée

Si la pipeline est trop pleine :
1. **Prioriser** : Focus sur les deals à plus haute probabilité et valeur
2. **Déléguer** : Passer les petits deals à un SDR ou junior
3. **Automatiser** : Utiliser AgentBridge pour les follow-ups
4. **Ne pas clôturer trop vite** : Une pipeline pleine est un bon problème

## 27.8 Reporting Téléphonique

**Report hebdomadaire :**
- Appels faits
- Conversations eues
- Rendez-vous fixés
- Démos complétées
- Propositions envoyées
- Deals closés
- Pipeline totale
- Forecast

**Report mensuel :**
- Tendance de conversion par phase
- Win rate par secteur/segment
- Cycle de vente moyen
- Revenue par activité téléphonique
- Top motifs de perte

## 27.9 Outils pour Pipeline Management

**Tools essentiels :**
- **CRM** : HubSpot, Salesforce, Pipedrive
- **Dashboard** : Visualisation pipeline en temps réel
- **Automatisation** : Follow-ups automatiques, rappels
- **Analytics** : Tendances, conversions, forecasting

🤖 **AgentBridge pour Pipeline** : L'IA peut générer des rapports de pipeline automatiquement, envoyer des follow-ups personnalisés et mettre à jour les enregistrements CRM.

## 27.10 Pipeline Review Téléphonique

**Session hebdomadaire (30 min) :**

1. **Revoir chaque deal actif** (5 min par deal)
   - Prochain pas ?
   - Date de clôture ?
   - Blocage ?
   - Support nécessaire ?

2. **Identifier les deals à risque** (10 min)
   - Lesquels ne bougent pas ?
   - Pourquoi ?
   - Plan de récupération ?

3. **Prioriser la semaine** (10 min)
   - Quels deals focus ?
   - Quels appels critiques ?
   - Quels follow-ups urgents ?

4. **Mettre à jour le forecast** (5 min)
   - Probabilités mises à jour
   - Revenue attendu
   - Gap vs. target

---

## Résumé du Chapitre

Pipeline et forecasting au téléphone :
- **Structure** : Phases claires avec critères de sortie
- **Métriques** : Tracer conversions, vitesse, valeur
- **Forecasting** : Prévoir revenue avec probabilités par phase
- **Hygiène** : Pas de deals zombie, mise à jour constante
- **Activité** : Relier appels à résultats
- **Review** : Sessions hebdomadaires structurées

---

## Actions à Entreprendre

- [ ] Définir les phases de votre pipeline avec critères de sortie
- [ ] Créer un dashboard de pipeline (même simple, même Excel)
- [ ] Calculer votre forecast actuel
- [ ] Configurer une review hebdomadaire de 30 minutes
- [ ] Appliquer la "règle des 30 jours" aux deals stagnants
