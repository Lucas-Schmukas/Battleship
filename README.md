Battleships

Konzept:

Ein zweidimensionales Array wird gefüllt, z.B.

Spielfeld hat 10x10 Felder

1 Schlachtschiff(5Felder), 2xKreuzer(4), 3xZerstörer (3 Felder), 4x U-Boot(2 Felder),

Jede Koordinate hat erst mal einen Platzhalter

Die Koordinaten bekommen verschiedene Symbole, je nachdem was mit ihr passiert ist.

Schiffe dürfen nichtt nebeneinander gesetzt werden (Regeln)


Frage: Was bedeutet es, wenn irgenwo ein Symbol im Feld gesetzt wird?

Gesetztes Schiff: <==> (■) / S

Getroffen: X

Daneben geschossen: O


Wir haben eine Array mit Strings.

Funktionalität 1: Spieler setzt (Lucas)

Funktionalität 2: Abfrage ob Schiff, nicht übern Rand gestellt ist.

Funktionalität 3: Schießen (Aurelia)
