<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoraggio: che cosa si legge e con quale esito

[English](README.en.md)

Come global-law monitora ogni paese: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Questa pagina fa lo stesso per Marche soltanto: ogni lettura di una fonte ufficiale, quando è avvenuta e con quale esito (atti aggiunti, modificati e rimossi). La forma leggibile dalle macchine è [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` come commit `Kind: check`, e mese per mese in [checks/](checks/).

**Ultimo controllo:** 2026-11-24 00:32 UTC, Consiglio regionale delle Marche, Banca dati delle leggi e dei regolamenti regionali: 47 indirizzi letti; 0 aggiunti, 0 modificati, 0 rimossi; nessuna modifica; 23 non pubblicati, di cui 0 senza motivo. Segnalazioni: `audit-disagrees`.

## Fonti

| Fonte | Cartelle | Frequenza | Ultimo controllo riuscito | Ultimo esito | Stato |
| --- | --- | --- | --- | --- | --- |
| [Consiglio regionale delle Marche, Banca dati delle leggi e dei regolamenti regionali](https://www.consiglio.marche.it/banche_dati_e_documentazione/leggi/) | `lr/`, `statuto/` | ogni giorno | 2026-11-24 00:32 UTC | nessuna modifica | sorvegliata: solo testo vigente, come il repository è costruito: un testo modificato è una nuova versione datata il giorno della lettura, attribuita alla banca dati come editore; regolamenti e leggi statutarie di modifica dello Statuto non sono inclusi |

## Gli ultimi 30 giorni

| Inizio (UTC) | Fonte | Letti | Aggiunti | Modificati | Rimossi | Non pubblicati (senza motivo) | Esito | Commit |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 00:29](checks/2026-11.md#it-consiglio-marche-20261124t002945z) | consiglio-marche | 47 | 0 | 0 | 0 | 23 (0) | nessuna modifica `audit-disagrees` | — |

## Verificalo da te

```
python tools/checktrail.py                      # l'ultimo controllo di ogni fonte
python tools/checktrail.py --day 2026-11-23     # tutti i controlli di un giorno
python tools/checktrail.py --act <id>           # quando un atto è stato visto e pubblicato
git log --grep='^Kind: check' --format='%ci %s'  # i controlli nella cronologia
```

Ha valore legale solo la pubblicazione ufficiale; i testi qui sono copie per la lettura e la ricerca.
