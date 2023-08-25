# If-Verzweigungen

If Verzweigungen, zu Deutsch `Wenn, dann` Verzweigung bezeichnet, sind Abfragen, ob bools den Wert True haben.
Man kann jedoch auch zwei oder mehrere Werte vergleichen.

Werte können direkt in der Verzweigung festgelegt werden oder als Variablen verwendet werden.

## Operatoren in If-Verzweigungen

| Operator |                                Beschreibung                                |
|:--------:|:--------------------------------------------------------------------------:|
|   `==`   |    Wenn ein Wert = einem anderem Wert entspricht ist das Ergebnis True     |
|   `!=`   |      Wenn ein Wert nicht dem anderen entspricht ist das Ergebnis True      |
|   `<`    |       Wenn ein Wert kleiner als der andere ist ist das Ergebnis True       |
|   `>`    |       Wenn ein Wert größer als der andere ist ist das Ergebnis True        |
|   `<=`   | Wenn ein Wert kleiner oder gleich ist wie der andere ist das Ergebnis True |
|   `>=`   | Wenn ein Wert größer oder gleich ist wie der andere ist das Ergebnis True  |
|   `&&`   |                       Mehrere Werte müssen True sein                       |
|  `\|\|`  |                       Einer der Werte muss True sein                       |

## If-Verzweigungen verwenden

If-Verzweigungen sind so aufgebaut: `if <Bedingung>:`

Bedingungen setzen sich so zusammen: `<Wert> <Operator> <Wert>`
Dies kann dann so aussehen: `eingabe == "ja"`

Man kann dies außerdem erweitern durch die Oder- und Und-Bedingungen: `eingabe == "Obst" || eingabe == "Gemüse"`

Nach dem Schlüsselwort `if` und der Bedingung kommt ein Doppelpunkt, um den Anfang der Verzweigung zu markieren

Nach dem Doppelpunkt programmiert man in einer nächsten Zeile, **mit einer Einrückung des Codes um 4 Leerzeichen oder
einen Tab** den exklusiven Code für die Bedingung.

## Beispiele zu den Operatoren

### Automarken abfragen

```py
eingabe = input("Schreibe eine Autmarke: ")
if eingabe == "Audi" || eingabe == "BMW" || eingabe == "Mercedes":
    print("Du hast eine Automarke genannt!")
```

### Zahlen unter 50

```py
eingabe = input("Gebe eine Zahl ein: ")
if eingabe > 50:
    print("Deine Zahl ist über 50")
    
if eingabe <= 50:
    print("Deine zahl ist 50 oder weniger.")
```

## Else
Wenn man einen Fall hat, der nur eintreten soll, wenn die If-Verzweigung nicht ausgeführt wurde benutzt man das Wort
`else`. 

Dies Verwendet man dann so:
```py
eingabe = input("Gebe eine Zahl ein: ")
if eingabe > 50:
    print("Deine Zahl ist über 50")
else:
    print("Deine zahl ist 50 oder weniger.")
```
Dieser Code ist genau derselbe wie davor, nur besser. Anstatt zweimal zu überprüfen, ob etwas kleiner/größer als etwas ist,
wissen wir, dass wenn die Zahl nicht über 50 ist unter 50 sein muss. Deswegen ist `else` hier die beste Variante.

Man kann `else` auch mit `if` kombinieren. Dies sieht dann so aus:
```py
eingabe = input("Gebe eine Zahl ein: ")
if eingabe > 50:
    print("Deine Zahl ist über 50")
else if eingabe >= 0:
    print("Deine Zahl ist im Bereich von 0-50")
else:
    print("Deine Zahl ist negativ")
```