---
description: Controllo temporale
icon: clock-rotate-left
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/6a3QgDGzrxeFxNcSzPJg/safercast-interfaccia-gui-web/barra-inferiore
---

# Barra Inferiore

La barra inferiore è costituita da una barra temporale orizzontale che mostra l'evoluzione nel tempo dei dati selezionati.&#x20;

Un **cursore verticale** evidenzia l’istante temporale selezionato. Sopra il cursore è visualizzata un’etichetta con:

* **giorno della settimana**
* **data**
* **ora precisa**

Cliccando sopra l'etichetta con il mouse è possibile spostare orizzontalmente il cursore, che consente di variare sia un istante preciso nel tempo che un intervallo di tempo (nel caso in cui sia stata selezionata una cumulata).&#x20;

Per quanto concerne **i dati istantanei**, si precisa che la barra può essere caratterizzata da due sezioni cromatiche:

* **Blu (a sinistra)** → rappresenta i **dati storici / osservati**
* **Arancione (a destra)** → rappresenta i **dati previsionali**

<figure><img src="../.gitbook/assets/barra temporale real time &#x26; forecast.png" alt=""><figcaption><p>Sezioni cromatiche in cui è divisa la barra tra dati storici/osservati e dati previsionali</p></figcaption></figure>

{% hint style="info" icon="hourglass-half" %}
Nello scenario _Coastal e nello scenario Fire,_ nel quale lo scenario in tempo reale e quello previsionale sono integrati, la barra temporale consente di esplorare l’evoluzione dello scenario nel tempo sia per dati passati che previsionali.&#x20;
{% endhint %}

{% hint style="info" icon="hourglass-end" %}
Nello scenario _Pluvial Real Time_ sarà presente solo lo scenario in tempo reale perciò la barra sarà solo di colore blu
{% endhint %}

{% hint style="info" icon="hourglass-start" %}
Nello scenario _Pluvial Forecast,_ invece, sarà presente solo lo scenario previsionale perciò la barra sarà solo di colore arancione
{% endhint %}

<figure><img src="../.gitbook/assets/9_barra inferiore ora precisa.png" alt=""><figcaption><p>Barra inferiore con cursore temporale posizionato in un'ora precisa</p></figcaption></figure>

Nel caso della cumulata, invece, l'intervallo selezionato sarà delimitato, sulla barra inferiore, da due etichette che riportano la data e orario di inizio e fine, e sarà colorato di arancione.

<figure><img src="../.gitbook/assets/9_barra inferiore cumulata.png" alt=""><figcaption><p>Barra inferiore con cursore temporale riferito ad una cumulata di 2h </p></figcaption></figure>

&#x20;In entrambi i casi la mappa si aggiornerà mostrando la situazione corrispondente all'istante o intervallo di tempo selezionato.
