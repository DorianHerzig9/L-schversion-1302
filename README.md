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

| 5    |  Muss               |  Funktional    |  Als User möchte ich, dass das Spiel die Spieler abwechselend an die Reihe nimmt. |
| 6    |  Können             |  Qualität      |  Als User möchte ich, ein sauber gestaltetes Front-end. |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Die Webseite wurde aufgerufen | Die Schaldfläche "New Game" wurde betätigt. | Das TicTacToe wird gestartet. |
| 1.2  | Die Webseite wurde aufgerufen | Die Schaldfläche "Player X" wurde betätigt. | Player X begint mit dem Spiel. |
| 1.3  | Die Webseite wurde aufgerufen | Die Schaldfläche "Player O" wurde betätigt. | Player O begint mit dem Spiel. |
| 2.1  | Die Webseite wurde aufgerufen | Die Spielkachel wurde von einem Spieler makiert. | Der andere andere Spieler ist an der Reihe. |
| 2.2  | Die Webseite wurde aufgerufen | Letzer Spielkachel wurde gewählt | Das Spiel gibt aus wer gewonnen hat oder ob es ein Unentschieden gab|
| 3.1  | Die Webseite wurde aufgerufen und es wurde bereits eine Runde gespielt. | Die Schaldfläche "New Game" wurde betätigt. | Das TicTacToe wird neu gestartet. |

### 1.4 Diagramme

![TicTacToe1](https://github.com/DorianHerzig9/L-schversion-1302/assets/110893394/30df35fa-1c83-4e29-b36d-032fc83a6867)
![HatSpielerGewonnen(AktuellerSpieler)](https://github.com/DorianHerzig9/L-schversion-1302/assets/110893394/14b2a889-4093-4bd5-850a-4849812d37f5)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   22.09.23    | Dorian | Infomieren | 25' |
| 1.B  |   22.09.23    | Dorian/Marek | Infomieren | 45' |
| 1.C  |   22.09.23    | Marek | HTML-Teil; Infomieren| 5' |
| 2.A  |   22.09.23    | Marek | HTML-Teil; Realiesieren| 25' |
| 2.B  |   22.09.23    | Lorenzo/Marek | Javascript-Teil; Infomieren | 10' |
| 2.C  |   22.09.23    | Lorenzo/Marek | Javascript-Teil; Realiesieren | 50' |
| 3.B  |   29.09.23    | Marek/Cyril | CSS-Teil; Infomieren | 10' |
| 4.A  |   29.09.23    | Cyril/Marek | CSS-Teil; Realiesieren | 30'  |
| 4.B  |   29.09.23 / 27.10.23    | Cyril/Dorian | Mahara-Portfolioeintrag | 120' |
| 4.C  |   29.09.23 / 27.10.23    | Dorian | Projekt Abschluss | 20' |

Total: 340' - 1600'

## 3 Entscheiden

Wir haben uns für die folgenden User Stories im Zusammenhang mit der Spiellogik entschieden, da sie sowohl für die Benutzererfahrung als auch für unsere Entwicklungsziele sinnvoll sind. Als Beispiel nehmen wir die Spiellogik: Diese wurde so implementiert, dass das Spiel reibungslos abläuft und die Regeln von Tic-Tac-Toe korrekt eingehalten werden. Eine klare und zuverlässige Spiellogik sorgt dafür, dass die Benutzer eine konsistente und unterhaltsame Spielerfahrung haben.

Die Implementierung der Spiellogik stellte eine anspruchsvolle Herausforderung dar, da die korrekte Handhabung von Spielerzügen, Gewinnbedingungen und Unentschieden eine präzise Umsetzung erforderte. Durch eine sorgfältige Entwicklung haben wir sicherstellt, dass das Spiel fair und verständlich ist, wodurch die Nutzerfreundlichkeit und Zufriedenheit maximiert werden.

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
Wir konnten alles ziemlich schnell und nach Plan erledigen. Es gab keine wirklichen Schwierichkeiten. Was gut lief, war das schnelle und intensieve Arbeiten am Projekt.

Was lief nicht gut in unserem Projekt?
Wir konnten das Projekt ohne schwerliegenden Problemen abschliessen.
