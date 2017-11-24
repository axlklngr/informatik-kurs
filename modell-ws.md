
## Modell der Wirtschaftssimulation

Bevor wir jetzt voreilig weiter in die Programmierung einsteigen, wollen wir erstmal nochmal einen Schritt zurückgehen und definieren, was wir eigentlich erreichen wollen. Wir beschreiben zunächst formlos was wir erreichen wollen, machen uns anschließen ein Modell davon und setzen es dann mit den Werkzeugen der Programmierung um.

[![Modell der Wirtschaftssimulation Video](https://img.youtube.com/vi/vLI5kN-_654/maxresdefault.jpg)](https://youtu.be/vLI5kN-_654)

### Marktplatz

Der Marktplatz zeigt die Produkte mit Anzahl und Preis, wie sie gekauft werden können.

```
Marktplatz 1
------------
1. Ware 1 - 20 Stk. - 13 EUR
2. Ware 2 - 40 Stk. - 27 EUR
3. Ware 3 - 10 Stk. - 17 EUR
```

### Tasche

In der Tasche befinden sich deine gekauften Waren. Die Tasche kann maximal X Waren aufnehmen.

### Waren

Die Waren sollten am Ende konfigurierbar sein, so dass man mit verschiedenen Konfigurationen mit anderen Waren handeln kann. Waren können hier zum Beispiel auch Aktien sein - und wer mehr lernen will, kann das ganze noch um eine Echtzeit-Abfrage von Werten aus dem Netz erweitern.

Beispiel für eine Konfiguration, wie sie aufgebaut sein könnte
```
[Marktplätze]
Frankfurt
London
New York
Tokio

[Waren]
Orangen 3-6 EUR
Äpfel   2-4 EUR
Pfeffer 10-20 EUR
```
