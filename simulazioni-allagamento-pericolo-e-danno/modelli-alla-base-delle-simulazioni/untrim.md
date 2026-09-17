---
description: University Numerical Tidal, River, and Inundation Model
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/6a3QgDGzrxeFxNcSzPJg/simulazioni-allagamento-pericolo-e-danno/modelli-di-allagamento-hazard-saferplaces/untrim
---

# 💧 UNTRIM

{% hint style="info" %}
**Il modello UNTRIM è un modello idrodinamico 2D in grado di simulare scenari di allagamento pluviale, fluviale e costiero.**
{% endhint %}

Il modello di calcolo UnTRIM (University Numerical Tidal, River, and Inundation Model) risolve le equazioni differenziali non lineari, mono, bi e tridimensionali, dipendenti dal tempo, relative a problemi di flusso idrostatico e non idrostatico a superficie libera, su una griglia ortogonale non strutturata, per coprire problemi con geometria complicata.

Le equazioni risolte sono descrizioni matematiche di leggi fisiche di conservazione per:

* volume d'acqua (equazione di continuità)
* quantità di moto lineare (equazioni di Navier-Stokes mediate da Reynolds (RANS)) e
* massa del tracciante (equazione di trasporto), ad esempio per: sale, calore (temperatura) e sedimenti sospesi o inquinanti passivi.

applicate a diversi tipi di acque (fiumi, laghi, estuari, mari costieri, ecc.).

Le equazioni sopra citate vengono risolte numericamente. Le seguenti grandezze fisiche possono essere ottenute in funzione dello spazio tridimensional&#x65;_(x,y,z)_&#x65; del tempo _t_:

elevazione della superficie dell'acqua _η(x,y,z)_ rispetto a una superficie di riferimento (ad esempio il livello medio del mare),

* &#x20;velocità della corrente _u(x,y,z,t), v(x,y,z,t), w(x,y,z,t),_
* componente di pressione non idrostatica _q(x,y,z,t)_&#x65;
* concentrazione di traccianti _C(x,y,z,t),_ ad esempio temperatura, salinità, concentrazione di sedimenti in sospensione o di inquinanti passivi.

&#x20;

Quando il modello di calcolo UnTRIM viene utilizzato in modalità mono o bidimensionale (con uno strato z in direzione verticale), i risultati per _u,v_ and _C_ saranno i rispettivi valori mediati in profondità per la velocità della corrente e la concentrazione del tracciante .&#x20;

Una descrizione dettagliata del modello UNTRIM è disponibile al seguente [link](https://wiki.baw.de/en/index.php/Mathematical_Model_UNTRIM) e alla seguente [pubblicazione scientifica](https://onlinelibrary.wiley.com/doi/10.1002/fld.4715).

Il Modello UNTRIM consente di simulare la propagazione idrodinamica di rilasci fluviali, eventi meteorici e inondazioni costiere.\
In particolare l'utente potrà simulare l'evoluzione temporale degli allagamenti per assegnato volume di rilascio, intensità di pioggia o livello medio del mare.\
I risultati delle simulazioni relative all'estensione dell'area allagata e relativa profondità dell'acqua vengono prodotti per diversi intervalli di tempo, in questo modo l'utente può visualizzare l'evoluzione del fenomeno nel tempo come nel video.

{% embed url="https://drive.google.com/file/d/1ICMSJS5kLI3eyLglU92gASnx7ldCAmEZ/view?usp=sharing" %}







