# trading-2h-data

Dati pubblici della dashboard del **Fast Swing Trader 2H** (paper trading).

Contiene solo **statistiche** (saldo virtuale, storico settimanale, trade, funnel) —
nessuna credenziale, nessun codice. Le chiavi API e il `.env` restano nel repo privato del bot.

- `dashboard_data.json` — rigenerato dal bot ogni ~5 min e pubblicato qui ogni 30 min da una GitHub Action.
- URL pubblico: `https://raw.githubusercontent.com/ivanx519/trading-2h-data/main/dashboard_data.json`

La dashboard web legge quell'URL e si aggiorna da sola. Non modificare a mano.
