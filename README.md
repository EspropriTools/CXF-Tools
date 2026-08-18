<div align="center">

# CXF Tools

**Converte i file CXF del Catasto in Shapefile e DXF**

Software gratuito per Windows, pensato per geometri, tecnici e uffici tecnici.

[![Scarica](https://img.shields.io/badge/Scarica-CXF%20Tools%202.3.47-2ea44f?style=for-the-badge&logo=windows)](https://github.com/EspropriTools/CXF-Tools/releases/download/v2.3.47/CXF-Tools-2.3.47.msi)

<sub>[Tutte le versioni e le note di rilascio](https://github.com/EspropriTools/CXF-Tools/releases)</sub>

![Versione](https://img.shields.io/badge/versione-2.3.47-blue)
![Licenza](https://img.shields.io/badge/licenza-freeware-lightgrey)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6)

</div>

---

## Cosa fa

CXF Tools legge i file in formato **CXF** dell'Agenzia delle Entrate e li converte in due formati utilizzabili nei software tecnici:

- **Shapefile (SHP)** — per QGIS, ArcGIS e i sistemi GIS in generale
- **DXF** — per AutoCAD, BricsCAD e i CAD compatibili

La conversione avviene **interamente sul tuo computer**. Nessun file viene caricato online, nessuna connessione a Internet è richiesta.

<img width="1772" height="1263" alt="schermata-principale (1)" src="https://github.com/user-attachments/assets/17a55e74-4d92-41b3-8ad2-3412fd9de056" />

*Selezione dei file, scelta dei layer da esportare e modalità di output.*


<img width="620" alt="impostazioni-dxf (1)" src="https://github.com/user-attachments/assets/8dc5d603-0329-48be-9b92-10d873316a19" />


*Nomi e colori dei layer DXF, personalizzabili e salvati tra le sessioni.*

## Caratteristiche

- Conversione di più file in un'unica operazione
- Scelta dei layer da esportare (particelle, fabbricati, acque, strade, testi, simboli)
- Colori e proprietà dei layer DXF personalizzabili
- Esportazione unificata o file separati
- Simboli grafici catastali resi come blocchi DXF
- Interfaccia in italiano

## Requisiti

Windows 10 o Windows 11 a 64 bit. Nient'altro: Python e le librerie sono già incluse nel pacchetto.

## Installazione

1. Scarica il file `CXF-Tools-2.3.47.msi` dalla [pagina delle release](https://github.com/EspropriTools/CXF-Tools/releases/latest)
2. Fai doppio clic sul file scaricato
3. Accetta le condizioni di licenza e prosegui

L'installazione avviene nella cartella dell'utente e **non richiede diritti di amministratore**.

### Avviso di Windows durante l'installazione

Windows mostrerà un avviso di **SmartScreen** con il messaggio "PC protetto da Windows". Compare perché il pacchetto non è firmato con un certificato commerciale, non perché il software sia dannoso.

Per procedere: clicca su **Ulteriori informazioni**, poi su **Esegui comunque**.

### Installazione silenziosa

Per il deployment su più postazioni:

```
msiexec /i CXF-Tools-2.3.47.msi /qn
```

## Verifica dei dati prodotti

> **I dati generati dalle conversioni devono essere sempre verificati.**
>
> CXF Tools è uno strumento di ausilio tecnico e non garantisce in alcun caso la correttezza, la completezza o l'accuratezza degli elaborati prodotti. Prima di utilizzare, depositare o consegnare i file convertiti, è necessario controllarne integralmente la correttezza confrontandoli con i file di origine e con le fonti ufficiali.
>
> La responsabilità degli elaborati sottoscritti, depositati o consegnati resta interamente in capo al professionista che li produce.

## Licenza

Software distribuito **gratuitamente**. Uso personale, professionale e commerciale consentito, su un numero illimitato di dispositivi.

La ridistribuzione è consentita a titolo gratuito e a pacchetto inalterato, inclusa la copia su risorse di rete interne di enti e studi tecnici. Sono vietati la modifica, la rivendita e ogni cessione a pagamento.

Le condizioni complete sono riportate nel [contratto di licenza](LICENSE.md), lo stesso testo che viene mostrato e accettato durante l'installazione.

Il software integra librerie open source di terze parti, elencate con le rispettive licenze nel file `LICENSES.txt` incluso nel programma.

## Segnalazioni

Per segnalare un problema o proporre un miglioramento, apri una [issue](https://github.com/EspropriTools/CXF-Tools/issues).

---

<div align="center">

© 2026 — Tutti i diritti riservati<br>
Opera depositata presso il Registro Pubblico Speciale per i Programmi per Elaboratore (SIAE)

</div>
