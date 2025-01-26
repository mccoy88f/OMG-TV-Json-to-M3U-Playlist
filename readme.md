# OMG TV Json to M3U Playlist

**OMG TV Json to M3U Playlist** è un semplice strumento Python per convertire una lista di canali IPTV in formato JSON in un file playlist `.m3u`. Questo strumento è utile per chi gestisce liste IPTV e desidera convertirle in un formato compatibile con la maggior parte dei lettori multimediali.

## Funzionalità

- Converte un file JSON contenente una lista di canali IPTV in un file `.m3u`.
- Supporta campi come `name`, `group`, `logo`, `tvg_id` e `url`.
- Genera un file `.m3u` con lo stesso nome del file JSON di input.

## Requisiti

- Python 3.x
- Modulo `argparse` (incluso nella libreria standard di Python)

## Installazione

1. Clona il repository:
   ```bash
   git clone https://github.com/tuo-username/omg-tv-json-to-m3u.git
2. Entra nella directory del progetto:
   ```bash
   cd omg-tv-json-to-m3u

### Utilizzo

1. Assicurati di avere un file JSON valido con la lista dei canali IPTV. Ecco un esempio di formato JSON:
2. ```json
   [
  {
    "group": "Germany",
    "logo": "",
    "name": "1.2.3 TV (7)",
    "tvg_id": null,
    "url": "https://vavoo.to/live2/play/51258455.ts"
  },
  {
    "group": "Germany",
    "logo": "",
    "name": "13TH STREET (7)",
    "tvg_id": null,
    "url": "https://vavoo.to/live2/play/3160812963.ts"
  }
]
3. python omg-converter.py nomefile.json
