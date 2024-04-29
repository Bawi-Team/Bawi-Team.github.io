# <img width="32" height="32" src="https://bawi-team.github.io/logo.png" alt="logo" /> Bawi Team website
Il sito della squadra di pallavolo mista Bawi Team.

## Istruzioni per aggiornare il sito
Il sito web viene automaticamente pubblicato tramite un workflow di GitHub quando sul repository Git viene fatto PUSH.

### Come modificare il sito web sul proprio computer

#### Ottenimento codice
Comandi [Git](https://git-scm.com) per ottenere il sito web:

```bash
git clone https://github.com/Bawi-Team/Bawi-Team.github.io.git
cd Bawi-Team.github.io
```

#### Aggiornamento codice
Comandi [Git](https://git-scm.com) per avere l'ultima versione del sito web:

```bash
git pull
```

#### Aggiornamento sito web
Una volta apportate le modifiche alle pagine web bisogna eseguire i seguenti comandi [Git](https://git-scm.com)

```bash
git status
git add .
git commit -m "descrizione della modifica apportata"
git push
```

## License
Copyright (c) 2018-2024 Michele Maione, Bawi Team. All rights reserved.

Licensed under the [GNU](LICENSE) License.
