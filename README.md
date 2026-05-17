# Il mio anno vale — Sito di supporto

Sito di supporto alla giornata di tutoraggio collettivo del Servizio Civile Universale.
Progetto ASC — CoopInRete.

## Stack

Sito statico in un solo file `index.html`. Nessuna build, nessuna dipendenza.

## Deploy locale

Apri `index.html` direttamente nel browser, oppure servilo con un server statico:

```bash
python3 -m http.server 8080
# poi apri http://localhost:8080
```

## Deploy su Vercel

Il file `vercel.json` configura il sito come statico con header di sicurezza minimi.
Connettendo questo repo a Vercel il deploy è automatico ad ogni `git push`.

## Struttura

- `index.html` — sito completo (HTML + CSS + JS inline)
- `vercel.json` — configurazione deploy
- `.gitignore`
- `README.md`

## Contatti

antonio.scaramuzzino@coopinrete.it
