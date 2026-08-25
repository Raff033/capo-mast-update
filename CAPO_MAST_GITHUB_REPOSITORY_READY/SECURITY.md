# Security Policy — CAPO MAST

Questo repository è pubblico e serve soltanto alla distribuzione degli aggiornamenti.

## NON pubblicare mai
- codice sorgente;
- password;
- token GitHub;
- chiavi AES;
- chiavi private;
- chiavi Secure Boot;
- materiale di firma;
- configurazioni contenenti credenziali.

## Pubblicazione firmware
Per ogni release stabile:
1. compilare il firmware;
2. provarlo sulla scheda reale;
3. calcolare dimensione e SHA-256;
4. caricare il `.bin`;
5. aggiornare `latest.json`;
6. verificare URL, versione, hardware, size e SHA-256;
7. impostare `"enabled": true` solo alla fine.

In produzione CAPO MAST dovrà accettare soltanto firmware autorizzati tramite il meccanismo di firma previsto dal progetto.
