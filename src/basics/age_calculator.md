# Alter berechnen anhand vom Geburtsdatum - Praxisbeispiel
Wir möchten in diesem Kapitel das Alter des Verwenders des Programmes anhand seines Geburtsdatums berechnen. 
Was wir machen:
- Einen Input für das Geburtsjahr erstellen
- Eine Logik zum Alter berechnen erstellen
- Das Alter ausgeben

Fangen wir an mit den `input`. Wir müssen bedenken, dass wie das Ergebnis vom `input` in einer Variable speichern.

Außerdem müssen wir daran denken, dass Ergebnis vom `input` in einen [Integer](casting.md) umzuwandeln, damit wir
damit berechnungen ausführen können.
```py
geburtsjahr = int(input("Gebe dein Geburtsjahr ein"))
```

Weiter gehts mit der Logik. Das aktuelle Jahr ist 2023. Also rechnen wir 2023 - das Geburtsjahr vom Benutzer, um das
Alter zu bekommen. Die Logik sieht so aus:
```py
geburtsjahr = int(input("Gebe dein Geburtsjahr ein"))
alter = 2023 - geburtsjahr
```

Nun müssen wir nur noch das Alter ausgeben:
```py
geburtsjahr = int(input("Gebe dein Geburtsjahr ein"))
alter = 2023 - geburtsjahr
print("Du bist " + alter + " Jahre alt.")
```

Unser Programm funktioniert jetzt schon.

Wenn wir es starten, bedienen wir es so

1. Geburtsjahr in das Feld eingeben
2. Sein Alter vom Computer gesagt bekommen