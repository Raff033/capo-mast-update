# CAPO MAST — Firmware Update Repository

Repository pubblico dedicato esclusivamente alla distribuzione degli aggiornamenti firmware di **CAPO MAST**.

## Contenuto
- `latest.json` — manifest dell'ultima versione stabile disponibile
- `firmware/stable/` — firmware stabili
- `firmware/beta/` — firmware di test/beta
- `firmware/archive/` — versioni precedenti
- `changelog/CHANGELOG.md` — cronologia delle versioni
- `docs/UPDATE_FORMAT.md` — formato del manifest OTA
- `SECURITY.md` — note di sicurezza

## Importante
Questo repository **non deve contenere il codice sorgente** di CAPO MAST.

Non caricare mai:
- file `.ino`, `.cpp`, `.h`, `.py` o sorgenti del progetto;
- password Wi-Fi;
- chiavi AES;
- chiavi private di firma;
- chiavi Secure Boot;
- credenziali, token o segreti.

I file `.bin` pubblicati qui sono immagini firmware compilate destinate all'aggiornamento OTA.

Finché non viene pubblicato il primo firmware OTA reale, il manifest rimane in stato `disabled`.
