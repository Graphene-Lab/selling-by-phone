# Capitolo 27: Pipeline e Forecasting al Telefono

## 27.1 Costruire una Pipeline Telefonica

La pipeline è il flusso di tutti i prospect che stai lavorando, dalla cold call alla chiusura. Ogni chiamata telefonica alimenta la pipeline.

**Fasi della pipeline per AgentBridge:**

| Fase | Definizione | Criterio di Uscita |
|------|-------------|-------------------|
| **Lead** | Contatto identificato | Qualificato come fit |
| **Contatto** | Prima chiamata fatta | Conversazione avvenuta |
| **Qualificato** | MEDDIC 4/6 confermato | Demo fissata |
| **Demo** | Demo completata | Proposta richiesta |
| **Proposta** | Proposta inviata | Negoziazione avviata |
| **Negoziazione** | Termini discussi | Contratto firmato |
| **Chiuso-Won** | Deal chiuso | Pagamento ricevuto |
| **Chiuso-Lost** | Deal perso | Motivo documentato |

## 27.2 Metriche di Pipeline

**Metriche chiave da tracciare:**

| Metrica | Formula | Benchmark |
|---------|---------|-----------|
| **Velocità pipeline** | Giorni medi Lead → Won | 30-90 giorni |
| **Conversione per fase** | (Usciti / Entrati) × 100 | Varia per fase |
| **Valore medio deal** | Revenue totale / Numero deal | 5.000-50.000€ |
| **Pipeline coverage** | Pipeline totale / Target revenue | 3x-5x |
| **Win rate** | Won / (Won + Lost) × 100 | 20-40% |
| **Churn rate** | Persi / Totale × 100 | <10% |

## 27.3 Forecasting Telefonico

Il forecasting è prevedere quanto revenue chiuderai in un dato periodo basandoti sulla pipeline attuale.

**Metodo di forecasting:**

```
Forecast = Σ (Valore deal × Probabilità chiusura per fase)

Fase Lead: 5%
Fase Contatto: 10%
Fase Qualificato: 25%
Fase Demo: 40%
Fase Proposta: 60%
Fase Negoziazione: 80%
Fase Chiuso-Won: 100%
```

**Esempio:**
- 20 Lead × 5.000€ × 5% = 5.000€
- 10 Qualificati × 10.000€ × 25% = 25.000€
- 5 Demo × 15.000€ × 40% = 30.000€
- 3 Proposta × 20.000€ × 60% = 36.000€
- **Forecast totale: 96.000€**

## 27.4 Pipeline Hygiene

Una pipeline sporca è peggio di una pipeline vuota. I deal "zombie" (che non si muoveranno mai) gonfiano artificialmente il forecast e distraggono dalla vera vendita.

**Regole di pipeline hygiene:**
- **Regola dei 30 giorni**: Se un deal non si muove in 30 giorni, chiudilo o riqualificalo
- **Niente deal "forse"**: Ogni deal ha una data di chiusura o è chiuso
- **Aggiornamento settimanale**: Rivedi ogni deal ogni settimana
- **Motivo di perdita obbligatorio**: Ogni deal perso ha un motivo documentato
- **Niente doppio conteggio**: Un deal è in una sola fase, mai in due

## 27.5 Attività Telefonica e Pipeline

**Relazione attività → risultati:**

| Attività | Impatto sulla Pipeline |
|----------|---------------------|
| 50 chiamate/giorno | ~5-8 conversazioni → 1-2 appuntamenti |
| 2 demo/settimana | ~1 proposta/settimana |
| 1 proposta/settimana | ~0,5 chiusure/settimana |
| 10 follow-up/giorno | 2-3 riattivazioni/settimana |

**Regola pratica**: Per chiudere 1 deal a settimana, hai bisogno di ~50 chiamate al giorno, 2 demo a settimana e 10 follow-up al giorno.

## 27.6 Gestire una Pipeline Sottopesata

Se la pipeline è troppo magra:
1. **Aumenta il volume**: Più chiamate, più lead
2. **Migliora la qualificazione**: Meno deal spazzatura, più deal qualificati
3. **Accelera i deal esistenti**: Follow-up più aggressivi
4. **Attiva referral**: Chiedi ai clienti esistenti di introdurti
5. **Riattiva deal persi**: Chiama deal persi 6+ mesi fa

## 27.7 Gestire una Pipeline Sovrappesata

Se la pipeline è troppo piena (non riesci a gestire tutti i deal):
1. **Prioritizza**: Focus sui deal con più alta probabilità e valore
2. **Delega**: Passa deal piccoli a SDR o junior
3. **Automatizza**: Usa AgentBridge per gestire follow-up e documentazione
4. **Non chiudere troppo presto**: Una pipeline piena è un problema buono — gestiscilo con processo, non con panico

## 27.8 Reporting Telefonico

**Report settimanale:**
- Chiamate fatte
- Conversazioni avute
- Appuntamenti fissati
- Demo completate
- Proposte inviate
- Deal chiusi
- Pipeline totale
- Forecast

**Report mensile:**
- Trend di conversione per fase
- Win rate per settore/segmento
- Ciclo di vendita medio
- Revenue per attività telefonica
- Top motivi di perdita

## 27.9 Strumenti per Pipeline Management

**Tool essenziali:**
- **CRM**: HubSpot, Salesforce, Pipedrive (o AgentBridge per automazione)
- **Dashboard**: Visualizzazione pipeline in tempo reale
- **Automazione**: Follow-up automatici, reminder, aggiornamenti
- **Analytics**: Trend, conversioni, forecasting

🤖 **AgentBridge per Pipeline**: L'AI può generare report di pipeline automaticamente, inviare follow-up personalizzati e aggiornare i record CRM — liberandoti per fare chiamate.

## 27.10 Pipeline Review Telefonica

**Sessione settimanale di pipeline review (30 min):**

1. **Rivedi ogni deal attivo** (5 min per deal)
   - Prossimo passo?
   - Data di chiusura?
   - Blocco?
   - Supporto necessario?

2. **Identifica deal a rischio** (10 min)
   - Quali non si muovono?
   - Perché?
   - Piano di recupero?

3. **Prioritizza la settimana** (10 min)
   - Quali deal focus?
   - Quali chiamate critiche?
   - Quali follow-up urgenti?

4. **Aggiorna forecast** (5 min)
   - Probabilità aggiornate
   - Revenue atteso
   - Gap vs. target

---

## Riepilogo del Capitolo

Pipeline e forecasting al telefono riguardano:
- **Struttura**: Fasi chiare con criteri di uscita
- **Metriche**: Tracciare conversioni, velocità, valore
- **Forecasting**: Prevedere revenue con probabilità per fase
- **Hygiene**: Niente deal zombie, aggiornamento costante
- **Attività**: Collegare chiamate a risultati
- **Review**: Sessioni settimanali strutturate

---

## Azioni da Intraprendere

- [ ] Definisci le fasi della tua pipeline con criteri di uscita
- [ ] Crea un dashboard di pipeline (anche semplice, anche Excel)
- [ ] Calcola il tuo forecast attuale
- [ ] Imposta una review settimanale di 30 minuti
- [ ] Applica la "regola dei 30 giorni" ai deal stantii
