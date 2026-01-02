# <img width="32" height="32" src="https://bawi-team.github.io/logo.png" alt="logo" /> Bawi Team website
Il sito della squadra di pallavolo mista Bawi Team.

## Istruzioni per aggiornare il sito
Il sito web viene automaticamente pubblicato tramite un workflow di GitHub quando sul repository Git viene fatto PUSH.

### Come modificare il sito web sul proprio computer

#### 1. Ottenimento codice
Comandi [Git](https://git-scm.com) per scaricare il progetto:

```bash
git clone [https://github.com/Bawi-Team/Bawi-Team.github.io.git](https://github.com/Bawi-Team/Bawi-Team.github.io.git)
cd Bawi-Team.github.io
```

#### 2. Installazione dipendenze (Solo la prima volta)
Assicurati di avere Ruby installato sul tuo sistema:
```bash
bundle install
```

#### 3. Anteprima locale
Per vedere le modifiche in tempo reale prima di pubblicarle, avvia il server Jekyll:
```bash
bundle exec jekyll serve
```

Una volta avviato, il sito sarà visibile su: `http://localhost:4000`

#### 4. Struttura dei dati
Per aggiornare i contenuti senza toccare l'HTML:
* **Navigazione**: Modifica `_data/stagioni.yml`
* **Dati Stagione**: Modifica o aggiungi file in `_data/stagione_XX_XX.yml`
* **Layout**: La grafica comune si trova in `_layouts/default.html`

#### 5. Pubblicazione
Una volta apportate le modifiche, esegui i seguenti comandi:
```bash
git status
git add .
git commit -m "Descrizione della modifica (es. Aggiornata rosa 25/26)"
git push
```