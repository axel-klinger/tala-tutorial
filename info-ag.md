# Informatik Kurs - Programmierung

Kurs aufbauen -> TALA -> AG anbieten (flipped!)


Ziele
---

Spiele entwickeln für Mobilgeräte

... was ihr nach einem halben/ganzen Jahr selbst gemacht haben werdet ...

* Wirtschaftssimulation (WS)
  - Beispiel: Fluggesellschaft, Autovermietung, Server/Services, ... irgendwas zum Mieten halt ...
  ... alt. Produktion oder Dienstleistung ...
* Adventure (ADV)
  - Beispiel: Märchen als CC, Film, Geschichte ... aber CC!

Jeweils in den Ausbaustufen

1. Konsole am PC
2. App für Mobilgerät

Später ...

3. Multiplayer // Fortgeschrittene
4. Software Entwicklung mit allem was dazugehört ...
   ... + Datenbanken, Lizenzen, Automatisierung von allem ...

Werkzeuge

* PC, Groovy/Java, Node.js, Ionic, Git/GitHub, Atom


Einheiten -> 1. Halbjahr Konsole, 2. Halbjahr App

- Entwicklungsumgebung einrichten Konsole + "Hello World!" in Git

- Modell der Informationen Wirtschaftssimultion

  In diesem Kurs bauen wir ein Spiel, bei dem wir Waren an verschiedenen Orten handeln können und nach 30 Tagen so viel wie möglich verdient haben müssen. Das Spiel kann beliebig erweitert werden.

  - Objekte, Handlungen und Eigenschaften
  - Variablen
  - Ein- und Ausgabe
  - Navigation
  - Struktur des Modells

- Modell der Informationen Adventure

  In diesem Kurs bauen wir ein Spiel, bei dem wir uns in einer Matrix aus Szenen bewegen und Aufgaben in einem Spielverlauf lösen müssen.

  - s.o.

- Programmiereinheiten WS ... s.a. info-ag-ws git

```
// Angebot an Artikeln
def angebot = ['Honig', 'Salz', 'Tran', 'Pelze'] as Set
def get = { it -> System.console().readLine(it + '\n') }

def artikel = [] as Set

// Schleife mit Abbruchbedingung
while (artikel.size() < 3 ) {
  // Validierung der Auswahl
  def auswahl = get( 'Wähle ein Produkt aus ' + angebot)
  if (angebot.contains(auswahl)) {
    artikel.add( auswahl )
  } else {
    println auswahl + ' ist nicht im Angebot!'
  }
}

println artikel
```
Was haben wir bis hier gelernt?
* s. git log


- Programmiereinheiten ADV

...

- Entwicklungsumgebung einrichten Mobilgerät + "Hello World!" in Git
