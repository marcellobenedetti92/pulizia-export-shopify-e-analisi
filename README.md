L'export viene pulito a scopo di analisi in questo modo:
- drop delle colonne non interessanti
- mapping dei tipi di dati
- rinominazione delle intestazioni
- rinominazione valori
- creazione delle seguenti colonne: ora, giorno, mese, anno, giorno della settimana e data
- aggiunta della colonna tasse con valori concordati con il cliente
- aggiunta della colonna "subtotale dopo tasse"
- salvataggio in formato parquet per mantenere i tipi di dati

L'analisi risponde alle domande:
- qual è la percentuale di clienti ricorrenti?
- quali sono le prime tre province per numero di ordini?
- qual è la media giornaliera del numero di ordini?
- qual è la media oraria del numero di ordini?
- qual è il trend giornaliero nel numero di ordini? (con annotazioni per segnalare eventi importanti successi in una particolare data, a mò di GA4)
- qual è la categoria migliore?
- quanti ordini per ciascun nome maglietta?
- quanti ordini per ciascun nome tazza?
- qual è il subtotale dopo tasse per anno e mese?
