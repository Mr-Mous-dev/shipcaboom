# ShipCaboom

ShipCaboom ist ein einfaches Schiffe-versenken-Spiel mit grafischer Oberfläche (Java Swing). Ziel ist es, das versteckte Schiff des Computers zu treffen, bevor der Computer das eigene Schiff findet.

## Spielprinzip

- Das Spielfeld besteht aus 50 Buttons:
  - Die Felder 0–24 (links) gehören dem Computer.
  - Die Felder 25–49 (rechts) gehören dem Spieler.
- Zu Beginn wählt der Computer zufällig ein Feld (0–24) als sein Schiff.
- Der Spieler wählt durch Klick auf ein Feld (25–49) sein eigenes Schiff.
- Das Spiel startet, sobald beide Schiffe gesetzt sind.
- Der Spieler schießt auf die Computerfelder, indem er auf die Buttons klickt.
- Nach jedem Schuss des Spielers schießt der Computer automatisch auf ein zufälliges, noch nicht beschossenes Spielerfeld.
- Wer zuerst das gegnerische Schiff trifft, gewinnt.

## Bedienung

1. Starte das Programm.
2. Wähle dein Schiff auf der rechten Seite (Felder 25–49).
3. Klicke auf die linken Felder (0–24), um auf das Computerschiff zu schießen.
4. Das Spiel endet, wenn eines der beiden Schiffe getroffen wurde.

## Voraussetzungen

- Java (mindestens Version 8)
- Keine weiteren Bibliotheken notwendig

## Starten

Kompiliere und starte das Programm mit:

```sh
javac SpielShipcaboom.java
java SpielShipcaboom
```
## Volgende Sachen wurden mithilfe Internet oder AI herausgefunden: 
- Wie man Objekte zentriert? 
+ (d.height - getSize().height oder width) / 2;
- Schriftfarbe und Hintergrund ändern
+ setBackground oder set Foreground
- Wie zeigt man Messages?
+ .showMessageDialog
- Wie kann man interne Namen benutzen, um Bedingung zwischen den Buttons herzustellen?
+ .setName
- Wie aktiviert man und deaktiviert man Buttons?
+ .setEnabled(false oder true)
- Wie frage ich nicht gesetzte Variablen?
+ Variable == null