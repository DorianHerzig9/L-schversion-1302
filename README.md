# L-schversion-1302

Lorenzo Lai, Dorian Herzig, Cyril Lutziger, Marek von Rogall

| Datum | Version | Zusammenfassung |
| ---- | --------------- | ---- |
| 17.11.2023 | 0.0.1   | Heute haben wir angefangen, TicTacToe zu programmieren.|
| 24.11.2023 | 0.0.2   | Heute haben wir tatsächlich mit dem programmieren angefangen und konnten schon ein paar Features einbauen. (z.B. Das Raster und Spielerreihenfolge)|
| 01.12.2023 | 0.0.3   | Heute haben wir den Grossteil des Codes fertiggestellt und sind fast mit dem Projekt fertig. |   
| 08.12.2023 | 1.0.0   | Heute haben wir den Code komplet fertiggestellt und fangen mit dem Mahara Portfolioeintrag an. |
| 15.12.2023 | 1.0.0   | Heute haben wir weiter am Portfolioeintrag gearbeitet. |
| 22.12.2023 | 1.0.0   | Heute waren wir schon fast mit allem fertig und haben mehr Pause gemacht |
| 12.01.2023 | 1.0.0   | Wir haben das Projekt abgeschlossen. |

## 1 Informieren

### 1.1 Ihr Projekt

Wir haben ein Tic-Tac-Toe-Spiel in HTML, CSS, Javascript unter Verwendung von Visual Studio entwickelt.

In diesem Projekt haben wir ein interaktives Tic-Tac-Toe-Spiel erstellt, das es Benutzern ermöglicht, gegeneinander anzutreten. Wir haben uns für die Verwendung von Visual Studio entschieden, da es eine leistungsstarke Entwicklungsumgebung bietet. Unser Ziel war es, eine unterhaltsame und benutzerfreundliche Anwendung zu schaffen, die Menschen dabei unterstützt, das klassische Tic-Tac-Toe-Spiel zu spielen und Spass zu haben.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  Muss               |  Funktional    | Als User möchte ich, das Programm lokal mit einem Freund spielen. |
| 2    |  Muss               |  Funktional    | Als User möchte ich, dass das Programm eine grafische Benutzeroberfläche besitzt. |
| 3    |  Muss               |  Funktional    | Als User möchte ich, dass das Programm automatisch erkennt , ob ein Spieler gewonnen hat. |
| 4    |  Muss               |  Funktional    | Als User möchte ich, dass das Spiel eine Auswahl besitzt um den Startspieler festzulegen. |

| 5X   |  Muss               |  Funktional    |  Als User möchte ich, meine Optionen mit Kriterien selber bewerten, um die beste Analyse zu erreichen. |
| 6    |  Können             |  Qualität      |  Als User möchte ich, ein sauber gestaltetes Front-end. |
| 7X   |  Können             |  Qualität      |  Als User möchte ich, dass die gewichtung nicht mehr verändert werden kann, nachdem man sie festgelegt hat. |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Die Webseite wurde aufgerufen | Die Schaldfläche "New Game" wurde detätigt. | Das TicTacToe wird gestartet. |
| 1.2  | Die Webseite wurde aufgerufen |  |         "Lidl erscheint rechts im Fenster"          |
| 2/3.1  | GUI: Kriterien hinzufügen:   |    Preis     |         -          |
| 2/3.2  | GUI: "Gewichtung"            |    3     |        -           |
| 2/3.3  | GUI: "Preis und 3"             |   "man drückt auf Hinzufügen"      |         "Preis (3) erscheint rechts im Fenster"           |
| 4.1  |      "2. Fenster mit Tabelle"        |    "man drückt auf Auswerten"     |         "Kriterien und gewichtung werden berechnet und entschtet ein Punktzahlreihe." |
| 5.1  |      "2. Fenster mit Tabelle"        |    3 "bei Kriterium Preis und Objekt/Option Lidl, wird 3 geschrieben"     |         -          |
| 6.1  |      -       |    -     |         -          |
| 7.1  |      "2. Fenster mit Tabelle"       |    "versucht Gewichtung zu ändern"     |        -        |

### 1.4 Diagramme




## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   22.09.23    |     Dorian      |      Informieren auf Stackoverflow        |       25'        |
| 1.B  |   22.09.23    |    Dorian/Marek       |      Realisierung der Optionen/Objekten        |        45'       |
| 1.C  |   22.09.23    |    Marek       |     Implementierung des Features         |       15'        |
| 2.A  |   22.09.23    |    Marek       |      Informieren auf Stackoverflow         |       15'        |
| 2.B  |   22.09.23    |    Lorenzo/Marek       |       Realisierung der Kriterien       |      45'         |
| 2.C  |   22.09.23    |    Lorenzo/Marek       |       Implementierung des Features       |       15'        |
| 3.A  |   29.09.23    |     Marek/Cyril      |       Realisierung der Gewichtung       |       45'        |
| 3.B  |   29.09.23    |     Marek/Cyril      |      Implementierung des Features        |       15'        |
| 4.A  |   29.09.23 / 27.10.23    |     Cyril/Marek      |       Informieren aus verschiedenen Internet Quellen      |       35'        |
| 4.B  |   29.09.23 / 27.10.23    |     Cyril/Marek      |       Realisierung der Berechnung und Punktzahl       |       ~85'        |
| 4.C  |   29.09.23 / 27.10.23    |     Cyril      |       Implementierung des Features       |       35'        |
| 5.A  |   27.10.23    |     Marek/Lorenzo      |       Realisierung der Bewertung       |       60'        |
| 5.B  |   27.10.23    |     Marek       |       Implementierung des Features       |       35'        |
| 6.A  |   22.09.23 / 03.10.23    |     Cyril/Dorian/Marek/Lorenzo      |      Verbesserung des GUIs        |       ~1200'        |
| 6.B  |   22.09.23 / 03.10.23    |     Cyril/Dorian/Marek/Lorenzo      |      Richtige Implementierung        |       ~1200'        |
| 7.A  |   27.10.23    |     Dorian      |       Realisierung des Fehlerbehebungs       |       45'        |
| 7.B  |   27.10.23    |     Dorian      |       Implementierung des Features       |       35'        |

Total: ~1200' - 1600'

## 3 Entscheiden

Wir haben uns für diese User Stories entschieden, weil sie sowohl für den Benutzer als auch für uns am sinnvollsten sind. Als Beispiel nehmen wir die GUI: Diese wurde so gestaltet, dass der Benutzer unser Programm problemlos verwenden kann. Je weniger Zeit man benötigt, um etwas zu verstehen, desto geringer wird die Wahrscheinlichkeit von Fehlern. Die Gestaltung der GUI war jedoch keine einfache Aufgabe.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  22.09.23     |  Dorian/Marek         |  25'             |  15'                 |
| 1.B  |  22.09.23     |  Dorian/Marek         |  45'             |  35'                 |
| 1.C  |  22.09.23     |  Dorian         |  15'             |  5'                 |
| 2.A  |  22.09.23     |  Lorenzo/Marek         |  15'             |  15'                 |
| 2.B  |  22.09.23     |  Lorenzo/Marek         |  45'             |  30-45'                 |
| 2.C  |  22.09.23     |  Lorenzo         |  15'             |  15'                 |
| 3.A  |  29.09.23     |  Marek         |  45'             |  60'                 |
| 3.B  |  29.09.23     |  Marek         |  15'             |  15'                 |
| 4.A  |  29.09.23 / 27.10.23     |  Cyril/Marek         |  35'             |  45'                 |
| 4.B  |  29.09.23 / 27.10.23     |  Cyril/Marek         |  ~85'             |  120'                 |
| 4.C  |  29.09.23 / 27.10.23     |  Cyril         |  35'             |  35'                 |
| 5.A  |  27.10.23     |  Marek/Lorenzo         |  60'             |  45'                 |
| 5.B  |  27.10.23     |  Marek         |  35'             |  15'                 |
| 6.A  |  22.09.23 / 03.10.23     |  Cyril/Dorian/Marek/Lorenzo         |  ~1200'             |  ~1200'                 |
| 6.B  |  22.09.23 / 03.10.23     |  Cyril/Dorian/Marek/Lorenzo         |  ~1200'             |  ~1200'                 |
| 7.A  |  27.10.23     |  Marek/Dorian         |  45'             |  55'                 |
| 7.B  |  27.10.23     |  Marek         |  35'             |  25'                 |

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |  03.10.23     |  OK        |  Lorenzo      |
| 1.2  |  03.10.23     |  OK        |  Lorenzo      |
| 2/3.1  |  03.10.23 / 27.10.23     |  OK        |  Marek/Lorenzo      |
| 2/3.2  |  03.10.23 / 27.10.23    |  OK        |  Marek      |
| 2/3.3  |  03.10.23 / 27.10.23    |  OK        |  Cyril      |
| 4.1  |  03.10.23 / 27.10.23     |  OK        |  Cyril      |
| 5.1  |  27.10.23     |  OK        | Dorian/Marek       |
| 6.1  |  27.10.23     |  OK        | Dorian/Marek/Lorenzo/Cyril       |
| 7.1  |  27.10.23     |  OK        | Dorian       |

Alles funktioniert und ist erfolgreich implementiert worden.

## 6 Auswerten

Was lief gut in unserem Projekt?
Wir konnten alles ziemlich schnell und nach Plan erledigen. Es gab ein paar Schwierigkeiten mit WinForms, aber wir haben es trotzdem geschafft. Was ziemlich gut lief, war die Zusammenarbeit und die Kommunikation.

Was lief nicht gut in unserem Projekt?
