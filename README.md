# Apparatus Tricolumnis

**Machina N° 001 — Officina degli Enigmi**

![Version](https://img.shields.io/badge/version-1.4.1-B08D57?style=flat-square&labelColor=59412F)
![License](https://img.shields.io/badge/license-AGPL--3.0-A65E3F?style=flat-square&labelColor=59412F)
![Platform](https://img.shields.io/badge/platform-Web-315B50?style=flat-square&labelColor=59412F)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white&labelColor=59412F)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white&labelColor=59412F)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=292929&labelColor=59412F)
![No dependencies](https://img.shields.io/badge/dependencies-none-315B50?style=flat-square&labelColor=59412F)

## Descrizione

Apparatus Tricolumnis è una reinterpretazione in chiave steampunk del classico rompicapo della Torre di Hanoi.

Il giocatore deve trasferire una pila di dischi dal primo al terzo perno, rispettando le regole di spostamento e cercando di completare l'operazione con il minor numero possibile di mosse.

L'interfaccia richiama l'estetica di uno strumento meccanico di fine Ottocento: ottone, legno, quadranti e finiture industriali.

## Regole

Il gioco utilizza tre perni e un numero variabile di dischi.

Le regole sono:

1. Si può spostare soltanto il disco superiore di una pila.
2. Ogni mossa trasferisce un solo disco.
3. Non è consentito collocare un disco più grande sopra uno più piccolo.
4. L'obiettivo è trasferire l'intera pila dal primo al terzo perno.

Il numero minimo di mosse necessarie dipende dal numero di dischi:

| Dischi | Mosse minime |
|---:|---:|
| 3 | 7 |
| 4 | 15 |
| 5 | 31 |
| 6 | 63 |
| 7 | 127 |
| 8 | 255 |

## Funzionalità

- Selezione da 3 a 8 dischi.
- Contatore delle mosse effettuate.
- Indicazione del numero minimo di mosse.
- Cronometro.
- Annullamento dell'ultima mossa.
- Riavvio della partita.
- Registrazione del miglior risultato per ciascun numero di dischi, tramite `localStorage` del browser.
- Effetti sonori sintetizzati mediante Web Audio API.
- Musica di sottofondo.
- Comandi indipendenti per attivare e disattivare musica ed effetti sonori.
- Interfaccia adattabile a schermi desktop e dispositivi mobili.

## Installazione

Non è necessario installare software, librerie o dipendenze.

Scaricare i file del progetto e collocarli nella stessa directory:

```text
apparatus-tricolumnis/
├── index.html
└── orchestra.mp3
```

Aprire `index.html` con un browser moderno.

Il file `orchestra.mp3` è necessario per la riproduzione della musica di sottofondo. Deve rimanere nella stessa directory di `index.html`.

Per consentire la riproduzione audio, il browser richiede un'interazione esplicita dell'utente: premere **AVVIA LA MACCHINA** nella schermata iniziale.

## Tecnologie

Il progetto utilizza esclusivamente tecnologie web standard:

- HTML5
- CSS3
- JavaScript
- Web Audio API
- `localStorage`

Non utilizza framework, librerie esterne, database o servizi server-side.

## Crediti musicali

Musica di [Luis Humanoide](https://pixabay.com/users/luis_humanoide-12661853/) tramite [Pixabay](https://pixabay.com/music/).

## Versione

**1.4.1**

## Licenza

Il codice sorgente di Apparatus Tricolumnis è distribuito secondo i termini della **GNU Affero General Public License v3.0 (AGPL-3.0)**.

Il testo integrale della licenza è disponibile su:

https://www.gnu.org/licenses/agpl-3.0.html

SPDX-License-Identifier: AGPL-3.0-only

Nota: il file musicale `orchestra.mp3` è un contenuto di terze parti e non è automaticamente soggetto alla licenza AGPL del codice. Per il suo utilizzo si applicano le condizioni della relativa licenza musicale.