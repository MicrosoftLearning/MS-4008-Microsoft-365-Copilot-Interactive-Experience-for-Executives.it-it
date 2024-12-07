---
title: Istruzioni ospitate online
permalink: index.html
layout: home
---

# Esperienza interattiva di Microsoft 365 Copilot per dirigenti 

## Directory contenuto

Le demo per questo corso sono basate sulle demo della guida demo del kit [di acceleratore e sulla Points.docx di parlare](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

È importante acquisire familiarità con le demo prima di tenere questa formazione. Per diverse demo, verranno utilizzati documenti di esempio, riunioni e messaggi di posta elettronica di Teams creati in modo preliminare, disponibili nelle istruzioni per le demo.

- Pre-scaricare tutti i documenti [di esempio qui](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- Configurare riunioni e thread di posta elettronica di Teams seguendo le istruzioni [riportate qui](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- Acquisire familiarità con l'esperienza interattiva:
    - Opzione 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - Opzione 2: aka.ms/TeamsEE

    > **NOTA:** se particpants non hanno una licenza di Microsoft 365 Copilot, possono usare la versione commerciale gratuita dell'esperienza trovata in [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## Descrizione del corso

Scoprire in che modo Microsoft 365 Copilot migliora la produttività e l'innovazione dell'area di lavoro. Questa esperienza, personalizzata per i leader aziendali moderni, fornisce informazioni dettagliate sulla creazione di richieste contestuali per Copilot e include esercizi di casi d’uso coinvolgenti che mostrano una perfetta integrazione nei flussi di lavoro giornalieri.

Gli obiettivi principali per questo recapito sono:

- Presentare partipcants a Microsoft 365 Copilot e insegnare loro come creare un prompt efficace
- Dimostrazione di Microsoft 365 Copilot nelle app di Office (fino a 3 demo)
- Guidare i partecipanti attraverso un'esperienza interattiva
- Invitare i partecipanti a scaricare e provare Microsoft Copilot per dispositivi mobili

## Tempi corso (stima) 

| # | Argomento                                 | Total Time      |
|---|---------------------------------------|-----------------|
| 1 | Introduzione a Microsoft 365 Copilot | 10 minuti    |
| 2 | Guida per dirigenti alla creazione di richieste efficaci | 30 minuti      |
| 3 | Esperienza interattiva di Microsoft 365 Copilot  | 20 minuti      |
|   |                                       | Total Downtime Minutes |


In basso sono elencati i collegamenti ipertestuali a tutti i lab.

## Demo

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Demo |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
