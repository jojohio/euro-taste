# Euro Taste Rebuild v9

Änderungen gegenüber v8:

- Der 6-Gerichte-Orbit um den Teller läuft wieder dauerhaft gegen den Uhrzeigersinn.
- Auch bei aktivierter reduzierter Bewegung bleibt der Orbit sehr langsam in Bewegung.
- Rezept-Zubereitung wurde auf 5 kompakte, logisch gebündelte Schritte pro Gericht reduziert.
- Schritte sind direkt lesbar und müssen nicht mehr einzeln aufgeklappt werden.
- Ein Klick auf eine Schrittzeile markiert sie als erledigt; Fortschrittsbalken bleibt erhalten.
- DE, EN und PT wurden konsistent angepasst.
- Scroll-Plop/Blur-Reveals bleiben erhalten.

Start:

```bash
npm install
npm run dev
```


## v10
- Main-Page-Reveals sind jetzt scroll-linked und reversibel.
- Länder-Cards, Rezeptkarten, Filter, Projektbereich, Projekt-Schritte, Stats und Rezept-Rail nutzen dieselbe Blur/Scale/Y-Plop-Logik wie die Rezeptseiten.
- Beim Hochscrollen laufen die Reveals rückwärts; beim erneuten Runterscrollen wieder vorwärts.


## v11
- Die Platzhalterbilder wurden durch die vom Nutzer bereitgestellten echten Gerichtsfotos ersetzt.
- Verwendet auf der Startseite, in der Orbit-Ansicht, in den Rezeptkarten und auf den einzelnen Rezeptseiten.