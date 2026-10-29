# Capitolo 41: KPI Avanzati e Analisi Predittiva

## 41.1 KPI di Conversione Avanzati

**Metriche che i migliori venditori tracciano:**

| KPI | Formula | Significato |
|-----|---------|-------------|
| **Lead-to-Opportunity Rate** | Opportunità / Lead × 100 | Qualità del lead |
| **Opportunity-to-Proposal Rate** | Proposte / Opportunità × 100 | Qualità della scoperta |
| **Proposal-to-Win Rate** | Won / Proposte × 100 | Qualità della proposta |
| **Average Sales Cycle** | Σ(Giorni Lead→Won) / N deal | Velocità del ciclo |
| **Revenue per Call** | Revenue totale / Chiamate fatte | Efficienza complessiva |
| **Pipeline Velocity** | (N deal × Valore × Win Rate) / Ciclo | Velocità di generazione revenue |
| **Multi-threading Rate** | Contatti per deal | Profondità relazione |
| **Expansion Revenue Rate** | Revenue espansione / Revenue totale | Upsell effectiveness |

## 41.2 Analisi Predittiva

**Usare i dati per prevedere risultati:**

**Modello di scoring lead:**
| Fattore | Punteggio |
|---------|-----------|
| Settore fit | +20 |
| Dimensione fit (20-500) | +15 |
| Segnale di crescita | +15 |
| Budget confermato | +20 |
| Decisore coinvolto | +15 |
| Urgenza alta | +15 |
| **Totale** | **100** |

**Soglia**: Lead con score > 70 = alta priorità. Score < 40 = squalifica.

## 41.3 Cohort Analysis

**Confrontare gruppi di deal per periodo:**
- Deal chiusi Q1 vs. Q2: Cosa è cambiato?
- Deal da cold call vs. inbound: Quale converte meglio?
- Deal con demo vs. senza demo: Differenza di win rate?
- Deal multi-thread vs. single-thread: Chi chiude di più?

## 41.4 Funnel Analysis Profonda

**Identificare il "gocciolamento" per fase:**

| Fase | Entrati | Usciti | Conversione | Gocciolamento |
|------|---------|--------|-------------|---------------|
| Lead | 100 | 40 | 40% | 60 persi |
| Contatto | 40 | 20 | 50% | 20 persi |
| Qualificato | 20 | 12 | 60% | 8 persi |
| Demo | 12 | 8 | 67% | 4 persi |
| Proposta | 8 | 4 | 50% | 4 persi |
| Won | 4 | 4 | 100% | 0 persi |

**Domanda chiave**: Dove gocciola di più? Lì c'è il maggior potenziale di miglioramento.

## 41.5 Revenue Attribution

**Attribuire revenue a attività specifiche:**
- Quale script genera più revenue?
- Quale settore produce deal più grandi?
- Quale canale (cold, warm, inbound) è più efficiente?
- Quale tipo di demo converte meglio?
- Quale follow-up sequence funziona?

## 41.6 Predictive Forecasting

**Metodo avanzato:**
```
Forecast = Σ (Deal_value × Phase_probability × Rep_confidence)

Dove:
- Phase_probability: da storico (es. Demo = 40%)
- Rep_confidence: self-assessment (0.5-1.5)
- Adjustments: trend, seasonality, market
```

## 41.7 KPI di Qualità

| KPI | Come Misurare | Target |
|-----|---------------|--------|
| **Tempo di risposta** | Minuti per rispondere a lead | < 5 minuti |
| **Tasso di personalizzazione** | % chiamate con ricerca pre-call | > 80% |
| **Tasso di follow-up** | % deal con 5+ follow-up | > 70% |
| **Documentazione CRM** | % chiamate documentate | 100% |
| **NPS post-vendita** | Sondaggio cliente | > 50 |

## 41.8 Benchmarking Avanzato

**Confronta non solo i risultati ma i PROCESSI:**
- Tempo medio per fase vs. top performer
- Numero di contatti per deal vs. top performer
- Tasso di personalizzazione vs. top performer
- Ciclo di vendita vs. top performer
- Revenue per attività vs. top performer

## 41.9 Insight da Dati

**Esempi di insight:**
- "I deal con 3+ contatti chiudono il 40% più spesso"
- "Demo entro 48h dalla discovery convertono il 2x"
- "Follow-up entro 24h aumenta conversione del 300%"
- "Settore X ha ciclo 2x più lungo ma deal 3x più grandi"
- "Script B genera 2x appuntamenti vs. Script A"

## 41.10 Dashboard Avanzata

**Metriche per livello:**

**Livello Rep (giornaliero):**
- Chiamate, conversazioni, appuntamenti, revenue

**Livello Manager (settimanale):**
- Pipeline, forecast, conversion per fase, top/bottom performer

**Livello Executive (mensile):**
- Revenue, crescita, pipeline velocity, CAC, LTV

---

## Riepilogo del Capitolo

I KPI avanzati includono:
- **Conversione**: Per ogni fase della pipeline
- **Predittivo**: Scoring lead, forecasting
- **Cohort**: Confronto per periodo e canale
- **Attribuzione**: Quale attività genera revenue
- **Qualità**: Tempo risposta, personalizzazione, documentazione
- **Insight**: Pattern nascosti nei dati

---

## Azioni da Intraprendere

- [ ] Calcola la pipeline velocity del tuo team
- [ ] Crea un modello di scoring lead
- [ ] Identifica il punto di maggior gocciolamento
- [ ] Costruisci una dashboard con KPI avanzati
- [ ] Genera 3 insight dai tuoi dati e agisci su di essi
