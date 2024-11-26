# ULTIMATE WEB SCRAPER

Questo progetto utilizza [n8n](https://n8n.io/) per costruire un workflow automatizzato che estrae informazioni da siti web, incluse le seguenti funzionalità principali:
- Profili aziendali
- Collegamenti ai social media
- Caratteristiche e funzionalità di applicazioni

## Caratteristiche

1. **Automazione Completa**: Navigazione automatizzata tra siti web per raccogliere dati rilevanti.
2. **Integrazione con Supabase**: Recupero e archiviazione dei dati estratti in un database.
3. **Output Strutturato**: Formattazione dei dati in JSON per una facile interpretazione.
4. **Intelligenza Artificiale**: Uso di modelli GPT per analizzare e sintetizzare i dati.
5. **Configurazione Flessibile**: Workflow modulare per adattarsi a diversi tipi di dati e fonti.

## Requisiti

- [n8n](https://n8n.io/)
- Account Supabase per la gestione dei dati
- API key per OpenAI (per funzioni AI)
- Accesso ai fogli Google per input/output opzionale

## Come Iniziare

1. Clona la repository:
   ```bash
   git clone https://github.com/tuo-username/ULTIMATE_WEB_SCRAPER.git
2. Importa il file .json nel tuo workspace di n8n.
3. Configura i nodi con le credenziali richieste (OpenAI, Supabase, ecc.).
4. Avvia il workflow e osserva l'estrazione automatica dei dati.
   
## Utilizzo
Estrarre Social Media: Naviga nel sito e raccoglie i link ai profili social.
Profilo Aziendale: Fornisce una descrizione sintetica delle attività aziendali.
Caratteristiche Applicazione: Identifica e riassume le funzionalità principali di un'app.
Personalizzazione
Puoi modificare i nodi o aggiungere nuove integrazioni per adattare il workflow a casi d'uso specifici.
