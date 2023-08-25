# Listen
Wenn wir viele Daten haben, welche wir speichern müssen, ist es äußerst umständlich für jede Date eine eigene
variable zu erstellen. Deswegen gibt es Listen die unter einem Variablennamen mehrere Daten speichern können.

Eine Liste sieht so aus:
```python
fruechte = ["apfel", "banane", "kirsche"]
```

Wenn wir die Liste ausgeben wollen fügen wir einfach `print` hinzu:
```python
fruechte = ["apfel", "banane", "kirsche"]
print(fruechte)
```
Deie Ausgabe sieht dann so aus:
```cmd
["apfel", "banane", "kirsche"]
```

## Auf einzelene Elemente zugreifen
Jeder Eintrag in einer Liste hat eine Nummer. 

In der Informatik fängt man bei 0 an zu zählen.

In unserem Fall ist
```info
apfel = 0, banane = 1, usw.
```
Um jetzt nur Banane in der Konsole auszugeben, verwenden wir:
```python
fruechte = ["apfel", "banane", "kirsche"]
print(fruechte[1])
```

## Elemente hinzufügen
Man kann auch Elemente im Nachhinein einer Liste hinzufügen. Dies funktioniert mit dem Variablennamen, an welchen man
einfach ein `.append()` hängen. 

Man muss bei `.append()` in den Klammern eine Zeichenkette übergeben.

Um zu unserer Liste etwas hinzuzufügen, schreiben wir also:
```python
fruechte = ["apfel", "banane", "kirsche"]
fruechte.append("birne")
```

## Elemente entfernen
Um elemente zu entfernen, schreibt man einfach:
```python
fruechte = ["apfel", "banane", "kirsche"]
fruechte.remove("apfel")
```