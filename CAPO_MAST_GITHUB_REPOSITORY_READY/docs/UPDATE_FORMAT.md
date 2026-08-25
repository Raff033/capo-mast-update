# Formato `latest.json`

Esempio:

```json
{
  "enabled": true,
  "product": "CAPO MAST",
  "channel": "stable",
  "version": "1.0.0",
  "hardware": "ESP32-2432S028R-V2",
  "min_version": "0.2.0",
  "url": "https://...",
  "size": 1234567,
  "sha256": "HASH_SHA256_DEL_FILE_BIN",
  "notes": "Versione completa CAPO MAST"
}
```

## Campi
- `enabled`: abilita/disabilita la distribuzione OTA
- `product`: identifica il prodotto
- `channel`: canale di aggiornamento
- `version`: versione disponibile
- `hardware`: modello hardware compatibile
- `min_version`: versione minima da cui è consentito l'aggiornamento diretto
- `url`: URL HTTPS del firmware `.bin`
- `size`: dimensione esatta in byte
- `sha256`: hash SHA-256 del firmware
- `notes`: breve descrizione dell'aggiornamento

Caricare prima il nuovo `.bin`, verificarlo, quindi modificare `latest.json` per ultimo.
