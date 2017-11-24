## Erste Schritte in der Programmierung

### Eingabe, Variable und Ausgabe

In der ersten Einheit lernen wir Daten einzugeben, in Variablen zu speichern und Werte auszugeben.

### Der erste Warenkord

Mit dem folgenden Programm können wir bereits ein paar Artikel in einen Warenkorb legen. Die einzelnen Schritte können in github nachvollzogen werden. Zu jedem commit gibt es ein kurzes Video.

```
// Angebot an Artikeln
def angebot = ['Honig', 'Salz', 'Tran', 'Pelze'] as Set
def get = { it -> System.console().readLine(it + '\n') }

def artikel = [] as Set

// Schleife mit Abbruchbedingung
while (artikel.size() < 3 ) {
  // Validierung der Auswahl
  def auswahl = get( 'Wähle ein Produkt aus ' + angebot)
  if ( angebot.contains(auswahl) ) {
    artikel.add( auswahl )
  } else {
    println auswahl + ' ist nicht im Angebot!'
  }
}

println artikel
```

// Alle Beispiele zum Nachlesen | als Video mit Erläuterung | ... ?

### Was haben wir bis hier kennen gelernt?

* Ein- und Ausgabe
* Schleifen
* Verzweigungen
* Zeichenketten
* Mengen
