# da-vicino-materiali

Magazzino comune dei materiali per i reel «… da vicino» (Quartieri News). Repository privato.

## Regola

1. Prima di generare, scaricare o cercare all'esterno un materiale: aggiorna la tua copia del repository e cerca in tutti i cataloghi della cartella giusta, anche quelli delle altre rubriche.
2. Se c'è un materiale adatto, usa quello.
3. Se manca, crealo e caricalo subito qui con la sua riga di catalogo. Se è a pagamento, annotalo anche nel documento di progetto `claude/spese-strumenti.md`.

Un materiale che resta solo dentro una chat non conta come fatto.

## Cartelle

| Cartella | Contenuto | Formato |
|---|---|---|
| `musica/` | brani musicali | mp3 |
| `effetti/` | effetti sonori | mp3 |
| `immagini/` | foto e illustrazioni usate nei reel | jpg, png |
| `voci/` | letture già generate | mp3 |

Non si caricano: reel finiti, file temporanei, chiavi o password. Nessun file oltre 50 MB.

## Nomi dei file

`rubrica-descrizione-breve`, minuscolo, senza spazi. Esempio: `vip-pianoforte-malinconico-01.mp3`.
Non rinominare né sovrascrivere i file di un'altra rubrica.

## Cataloghi

In ogni cartella c'è un catalogo per rubrica: `catalogo-<rubrica>.csv` (per esempio `catalogo-vip.csv`, `catalogo-chi-era.csv`). Ogni chat scrive solo nel catalogo della propria rubrica e legge tutti gli altri. Le colonne sono nel file `catalogo-MODELLO.csv` di ogni cartella: copialo, non modificarlo.

Le immagini senza autore e licenza noti non si caricano.
