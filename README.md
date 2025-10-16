# 🏠 Ripartizione Spese Riscaldamento e ACS

Questa applicazione web in HTML permette di calcolare la ripartizione delle spese di riscaldamento e acqua calda sanitaria (ACS) tra due appartamenti, partendo dai dati della bolletta e da alcuni parametri tecnici.

## Funzionalità principali

- **Calcolo automatico** della suddivisione delle spese tra due appartamenti.
- Inserimento dei dati della bolletta e dei consumi ACS.
- Configurazione dei parametri tecnici della caldaia (gas per ACS, rendimento, costo gas).
- Definizione delle percentuali di ripartizione per ogni appartamento (sia riscaldamento che ACS).
- Visualizzazione dettagliata dei calcoli (costo ACS, costo riscaldamento, totali da pagare).
- **Riepilogo spese** per ciascun appartamento.
- **Storico** degli ultimi 3 calcoli effettuati.
- Esportazione calcolo in **Excel** e **PDF**.
- Verifica della correttezza della ripartizione.
- Attenzione: i dati generati sono solo indicativi e non hanno valore legale.

## Come si usa

1. **Apri il file `RIPARTIZIONE_CONSUMI.html`** in un browser moderno.
2. **Compila i campi richiesti** nelle varie sezioni:
   - **Dati Bolletta:** Importo totale e metri cubi ACS consumati.
   - **Parametri Caldaia:** Gas necessario per ACS, rendimento della caldaia, costo del gas.
   - **Percentuali di Ripartizione:** Inserisci le percentuali di suddivisione tra i due appartamenti per riscaldamento e ACS.
3. Clicca su **"Calcola Ripartizione"** per ottenere:
   - Dettaglio calcoli (costo ACS, costo riscaldamento)
   - Riepilogo delle spese per ciascun appartamento
   - Verifica della correttezza
4. Puoi **esportare il risultato** in Excel o PDF tramite i pulsanti dedicati.
5. Nella sezione "Storico" vengono salvati gli ultimi 3 calcoli effettuati, che puoi cancellare in qualsiasi momento.

## Note tecniche

- Tutti i calcoli vengono eseguiti direttamente nel browser tramite JavaScript.
- Le esportazioni in PDF e Excel non richiedono servizi esterni.
- Lo storico è salvato in locale (localStorage) e non viene condiviso online.
- Interfaccia moderna, chiara e accessibile anche via dispositivi mobili.

## Avvertenze

> **ATTENZIONE:** I dati calcolati sono solo a scopo informativo e non hanno alcun valore legale.

---

**Creato da Denis D.**

Per domande o suggerimenti, visita il [repository su GitHub](https://github.com/a080502/Varie).