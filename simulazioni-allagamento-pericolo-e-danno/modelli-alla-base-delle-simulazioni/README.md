---
metaLinks:
  alternates:
    - >-
      https://app.gitbook.com/s/6a3QgDGzrxeFxNcSzPJg/simulazioni-allagamento-pericolo-e-danno/modelli-di-allagamento-hazard-saferplaces
---

# 📓 Modelli alla base delle simulazioni

Il servizio dispone dei seguenti modelli:

* [safer\_rain.md](safer_rain.md "mention")&#x20;
* [safer\_coast.md](safer_coast.md "mention")
* [untrim.md](untrim.md "mention")
* &#x20;[safer\_fire.md](safer_fire.md "mention")



Per le simulazioni di eventi alluvionali, il servizio utilizza diversi tipi di gli algoritmi di elaborazione rapida, sviluppati da SaferPlaces, che consentono una valutazione dei rischi alluvionali rapida, ad alta risoluzione e adatta alle aree urbane.&#x20;

Si tratta di algoritmi idrostatici basati sul DEM (Modelli di Elevazione Digitale del terreno) che forniscono una stima ad alta risoluzione della profondità dell'acqua e dell'estensione dell'area allagata. Il modello **Safer\_RAIN** è specifico per inondazioni da piogge intense o pluviali, mentre il modello **Safer\_COAST** è specifico per inondazioni costiere.

Il modello **UNTRIM**, invece, è un modello idrodinamico 2D in grado di simulare la propagazione idrodinamica di eventi meteorici e inondazioni costiere. In particolare l'utente può simulare l'evoluzione temporale degli allagamenti per intensità di pioggia o livello medio del mare.&#x20;

Il modello **Safer\_FIRE** è un modello probabilistico per la simulazione della propagazione degli incendi, basato sull’integrazione di differenti sorgenti informative territoriali e ambientali. Il sistema utilizza dati relativi alla morfologia del terreno (_Digital Elevation Model_), alla tipologia di vegetazione e combustibile presente, all’umidità del suolo e della vegetazione, alle condizioni del vento (direzione e intensità), ai punti di innesco dell’incendio e a dati satellitari e cartografici ad alta risoluzione, al fine di stimare l’evoluzione spaziale e temporale del fronte di fiamma.



<br>

